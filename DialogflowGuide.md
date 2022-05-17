
<a name="index">**目录**</a>
</br>
<a href="#0">1. 概念解释</a> </br>
&emsp;<a href="#1">1.1公司业务的相关的概念</a> </br>
&emsp;&emsp;<a href="#2">1.1.1 公司项目与场景</a> </br>
&emsp;<a href="#3">1.2 谷歌名词概念解释</a>  
&emsp;&emsp;<a href="#4">1.2.1 谷歌项目与代理</a>  
&emsp;&emsp;<a href="#5">1.2.2 谷歌的服务</a>  
&emsp;&emsp;<a href="#6">1.2.3 谷歌代理</a>  
&emsp;&emsp;<a href="#7">1.2.4 何为模板代理</a>  
&emsp;&emsp;&emsp;<a href="#8">1.2.4.1 为什么要设置多个模板代理</a>  
&emsp;&emsp;&emsp;<a href="#9">1.2.4.2 父模板代理与“复制品”的关系</a>  
&emsp;&emsp;&emsp;<a href="#10">1.2.4.3 项目和代理命名规则</a>  
&emsp;&emsp;&emsp;<a href="#11">1.2.4.4 模板代理的存放位置</a>  
&emsp;&emsp;&emsp;<a href="#12">1.2.4.5 谷歌项目的命名规则</a>  



&emsp;<a href="#11">1.3 公司业务与谷歌服务的融合</a>


# <a name="0">1. 概念解释</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
## <a name="1">1.1公司业务的相关的概念</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
### <a name="2">1.1.1 公司项目与场景</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
- 公司场景：截止当前为止，公司的场景分为6类，即：商超、展厅、写字楼、医院、餐饮、酒店。<br>
- 公司项目：以上六大场景分别对应六大类的公司项目，每一个大类的项目有国内与海外之分。如，海外商超项目与国内商超项目。 此文档仅讨论海外项目。<br>
- 商家项目：每个场景的项目的产品的最终使用者是商家，比如一个商家购买了一台商超服务机器人，公司运营人员会给该商家开启一个项目，商家从该项目的管理后台上传必要资料，以使用机器人服务，包
括语义服务。 <br>
- 商家项目id：所有场景下的商家都有唯一的项目id，机器人id和商家项目id具有绑定关系，比如一家餐厅购买了4台餐饮服务机器人，那么该商家的项目对应了4个机器人id。<br>
- 机器人id：所有场景下的机器人都有唯一的设备id <br>
公司语义服务器根据该器人id，和其所属的商家项目id来请求对应的谷歌代理（稍后会讲到），并返回结果给APP。<br>
<br>
以下为一个语义的请求字段：<br>
其中“project”字段为商家项目id，“deviceID”为机器人设备id <br>

```python
'''
{
    "type": 0,
    "project": "62342feb4a6c213fc8c09632",
    "deviceID": "YHPR1120B00811SZGM4321020142",
    "area": "",
    "ask": "hi here",
    "userData": "{{$timestamp}}",
    "robotType": 4,
    "pageID": 0,
    "requestID": "",
    "version": "v1.0.0"
}
```
'''


## <a name="3">1.2 谷歌名词概念解释</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
### <a name="4">1.2.1 谷歌项目与代理</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
#### 什么是谷歌项目？
简单来说，这是谷歌为了用户使用他们的服务而设立的。使用谷歌的服务，如谷歌地图/STT/TTS,就必须建立一个谷歌项目。想要使用某谷歌服务必须开启对应服务的API。<br>
一个谷歌项目下可创建1000个代理，谷歌在全球设立了12个大区，创建代理时需选择一个区域，区域代表了该代理存放的地理位置，这将影响到服务访问速度。<br>
目前我们的做法是将谷歌项目当作一类服务的容器，这样便于项目管理和账单查看。 比如,谷歌项目“PROJECT1”只用于Dialoflow，“Project2”只用于STT/TTS,“ROJECT3”只用于Google map<br>

![image](https://user-images.githubusercontent.com/30898964/168820871-44ad95c2-0ff2-493d-9b72-09bee7b07a82.png)

### <a name="5">1.2.2 谷歌的服务</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

#### 我们用到了哪些谷歌服务？

- STT服务，即语音识别，谷歌提供多语种的语音识别、语种识别。<br>
- TTS服务，即语音播报，谷歌提供多语种的男女生播报，截止当前谷歌尚未支持童声（2022-5）<br>
- Dialogflow CX，即谷歌的对话搭建平台，提供意图识别、对话搭建。<br>
- 谷歌地图

<img width="1135" alt="截屏2022-05-17 下午9 07 05" src="https://user-images.githubusercontent.com/30898964/168818016-2584397a-9196-4d13-beca-915867373164.png">

### <a name="6">1.2.3谷歌代理</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

#### 谷歌代理和其环境
谷歌代理（Agent)是一个功能的抽象，比如订票代理、订房代理、订餐代理。<br>
从版本的角度来讲，代理又可以分为草稿代理和环境代理。<br>
草稿： 在控制台编辑的代理叫草稿，草稿代理的地址没有'/environment/'字段， 如：projects/future-area-343501/locations/asia-southeast1/agents/xxxxx <br>
环境代理： 谷歌提供自定义新建环境来达到代理的版本控制，我们自定义一个环境，取名为“develop”，然后在该环境的页面指定每个流的版本信息。如： <br>
projects/future-area-343501/locations/asia-southeast1/agents/89346e48-8fb0-4b7b-891d-16738cd337ef/environments/xxxx <br>

### 商家代理和谷歌代理的对应关系

每个商家项目对应唯一一个谷歌代理，代理名为商家id，示例实例如下：<br>
<br>

<img width="1015" alt="截屏2022-05-17 下午11 53 26" src="https://user-images.githubusercontent.com/30898964/168855043-86d8a211-b28b-4860-a5e3-bc7d8cad06c8.png">




#### 什么是流？
流决定了对话的走向，一个代理可以有1个或多个流组成。谷歌提供流级别的版本控制，即可以为每个流打一个版本。 <br>

### <a name="7">1.2.4 公司项目和谷歌代理的关系</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

#### 公司项目和谷歌代理的关系
一个公司场景的项目对应同一种功能的谷歌代理，比如餐饮场景对应餐饮代理，餐饮代理只具有餐饮业务的语义功能。该代理存放了餐饮场景下该商家项目的意图、实体数据（比如菜名、菜口味等)。 <br>

根据公司研发管理流程，我们现有研发、测试、生产环境，因此我们需要基于此来划分谷歌项目和代理。 <br>

#### 何为模板代理？
在讲模板代理之前先要理解动态实体和静态实体？<br>
动态实体： 指的是商家在管理平台输入的字段。如商家名、菜名名、客房名、公司名等。我们约定动态实体命名以“DYN_” 开头。<br>
静态实体： 静态实体是相对动态而言的，可分为平台预设的实体和语法用途的实体，平台预设的实体命名以“DEF_”开头，语料用途的实体以“GRA_"开头。<br>

模板代理是我们根据公司业务抽象而来，而谷歌本身没有模板代理的概念。模板代理产生的原因是为了做到商家的数据分割、场景的业务意图统一。拿餐饮场景来举例，开发人员维护一个模板代理，我们希望餐饮场景下的所有项目都具有同样的语义功能，每次新增一个餐饮项目，一个谷歌空代理会被创建，该餐饮项目的代理会把模板代理复制一份，然后直接将其覆盖到该商家代理，这样此商家代理就具有了模板代理的所有功能。 值得注意的是，不同的商家配置了不同的菜名、口味等。如何保证商家的数据隔离呢？ 拉取模板代理后，我们会判断哪些是动态实体，然后讲该商家的动态实体更新到与之对应的谷歌代理。



#### <a name="8">1.2.4.1 为什么要设置多个模板代理</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

#### 为什么要设置多个模板代理？
一个场景下一个语言的代理只有一个父模板代理（如：香港(英文)餐饮模板代理,名：Hk_Restaurant_English_Template），但有多个“复制品”。例如,美国（英文）餐饮模板代理.

##### 为了区分公司场景
每个公司场景的机器人都有有不同的业务需求，餐饮代理只负责餐饮相关业务，酒店代理只负责酒店相关业务，在命名上也要区分开。<br>


##### 为了区分代理的语言 
谷歌代理支持多语种意图服务，虽然可以在一个意图里放入多个语言的训练句子并训练模型，但是这样的做法谷歌不建议，我们当前的做法是一个代理是”说“语种语言，意思一个代理的语料只能是一种语言。<br>


##### 为了语义服务响应速度 
在新建代理的时候我们必须选择一个地理区域，这个地理区域决定了该代理的响应速度。举个例子，比如餐饮机器人被部署在美国，那么该餐饮模板代理的位置该是美国或者靠近美国的地区。

#### <a name="9">1.2.4.2 </a>父模板代理与“复制品”的关系<a style="float:right;text-decoration:none;" href="#index">[Top]</a>
#### 父模板代理与“复制品”的关系

#### <a name="10">1.2.4.3 模板代理的命名规则</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

#### 模板代理的命名约定

命名规则如下：<br>
第一部分代表大区名， "Hk_"代表香港 <br>
第二部分代表场景，“Office_”代表写字楼 <br>
第三部分代表语言，“English”代表英语 <br>
所以，Usa_Office_English_Template 是美国写字楼（英语）模板代理 <br>
- CHk_Office_English_Template <br>
- Usa_Office_English_Template <br>
- Hk_Hotel_English_Template <br>
- Usa_Hotel_English_Template <br>






#### <a name="11">1.2.4.4  模板代理存放位置</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

每一个场景下的每个语言只有一个父模板代理，我们将所有场景的父模板代理放入到一个谷歌项目下，当前我们放入HkRestaurantTemplate下，但是后期会将项目名称规范化。<br>
<img width="1272" alt="截屏2022-05-17 下午11 11 05" src="https://user-images.githubusercontent.com/30898964/168845560-a787b013-91f8-4a7c-810c-b6e8e114cb92.png">

#### <a name="12">1.2.4.5 谷歌项目的命名规则</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>







2）谷歌研发、测试、生产环境项目会从模板代理与之对应的环境复制该版本的代理（如下图）,拉取后该公司项目的代理会清空所有数据并上传模板代理(包括意图、实体等)。然后，该公司项目代理会更新自己的动态实体，并完成自动训练。


每个公司场景都有与之对应的谷歌项目、模板代理、生产环境谷歌项目、测试环境谷歌项目、研发环境谷歌项目。

当前我们根据业务和开发需求，将谷歌代理分为了几个大类：

















