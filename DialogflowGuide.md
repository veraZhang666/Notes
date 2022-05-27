
<a name="index">**目录**</a>
</br>
<a href="#0">1. 概念解释</a></br>
&emsp;<a href="#1">1.1 公司业务的相关的概念</a></br>
&emsp;&emsp;<a href="#2">1.1.1 公司项目与场景</a></br>
&emsp;<a href="#3">1.2 谷歌名词概念解释</a></br>
&emsp;&emsp;<a href="#4">1.2.1 谷歌项目与代理</a></br>
&emsp;&emsp;<a href="#5">1.2.2 谷歌的服务</a></br>
&emsp;&emsp;<a href="#6">1.2.3 谷歌代理与公司项目</a></br>
&emsp;&emsp;&emsp;<a href="#7">1.2.3.1 公司项目和谷歌代理的关系</a></br>
&emsp;&emsp;&emsp;<a href="#8">1.2.3.2 何为模板代理</a></br>
&emsp;&emsp;&emsp;<a href="#9">1.2.3.3 为什么要设置多个模板代理</a></br>
&emsp;&emsp;&emsp;<a href="#10">1.2.3.4 模板代理的版本控制</a></br>
&emsp;&emsp;&emsp;<a href="#11">1.2.3.5 父模板代理与“复制品”的关系</a></br>
&emsp;&emsp;&emsp;<a href="#12">1.2.3.6 谷歌项目、代理、意图的命名规范</a></br>
&emsp;<a href="#13">1.3 公司业务与谷歌服务的融合</a></br>
&emsp;&emsp;<a href="#14">1.3.1 父模板代理及其环境</a></br>
<a href="#15">2 实践操作</a></br>
&emsp;<a href="#16">2.1 登录google cloud platform</a></br>
&emsp;<a href="#17">2.2 新建谷歌项目</a></br>
&emsp;&emsp;<a href="#18">2.2.1 步骤1</a></br>
&emsp;&emsp;<a href="#19">2.2.2 步骤2</a></br>
&emsp;<a href="#19">2.3 为该项目创建服务账号 </a></br>
&emsp;&emsp;<a href="#21">2.3.1 什么是服务账号？</a></br>
&emsp;&emsp;<a href="#22">2.3.2 创建服务账号</a></br>
&emsp;<a href="#23">2.4 最佳做法与解决方案</a></br>
&emsp;&emsp;<a href="#24">2.4.1 谷歌技术人员给出的建议</a></br>
&emsp;&emsp;<a href="#25">2.4.2 具体步骤</a></br>
&emsp;<a href="#26">2.5 设置环境变量</a></br>
&emsp;&emsp;<a href="#27">2.5.1 linux, mac 用户的环境变量设置</a></br>
&emsp;<a href="#28">2.6 代理的操作 </a></br>
&emsp;&emsp;<a href="#29">2.6.1 代理的创建</a></br>
&emsp;&emsp;&emsp;<a href="#30">2.6.1.1 通过控制台创建</a></br>
&emsp;&emsp;&emsp;<a href="#31">2.6.1.2 代理地区的手动初始化</a></br>
&emsp;&emsp;&emsp;<a href="#32">2.6.1.3 通过客户端创建</a></br>
&emsp;&emsp;&emsp;<a href="#33">2.6.1.4 代理的时区、语言、区域表</a></br>
&emsp;&emsp;<a href="#34">2.6.2 代理的导出</a></br>
&emsp;&emsp;&emsp;<a href="#35">2.6.2.1 使用控制台导出</a></br>
&emsp;&emsp;&emsp;<a href="#36">2.6.2.2 使用客户端库导出</a></br>
&emsp;&emsp;<a href="#37">2.6.3 代理的导入</a></br>
&emsp;&emsp;&emsp;<a href="#38">2.6.3.1 通过控制台导入</a></br>
&emsp;&emsp;&emsp;<a href="#39">2.6.3.2 通过客户端库导入</a></br>
&emsp;&emsp;<a href="#40">2.6.4 代理的删除</a></br>
&emsp;&emsp;&emsp;<a href="#41">2.6.4.1 通过控制台删除</a></br>
&emsp;&emsp;&emsp;<a href="#42">2.6.4.2 通过客户端库删除</a></br>
&emsp;<a href="#43">2.7 Dialogflow 控制台面板功能介绍</a></br>
&emsp;&emsp;<a href="#44">2.7.1 在控制台测试代理 </a></br>
&emsp;<a href="#45">2.8 代理各组件概念与操作</a></br>
&emsp;&emsp;<a href="#46">2.8.1 概念</a></br>
&emsp;&emsp;&emsp;<a href="#47">2.8.1.1 意图</a></br>
&emsp;&emsp;&emsp;<a href="#48">2.8.1.2 实体类型</a></br>
&emsp;&emsp;&emsp;<a href="#49">2.8.1.3 流</a></br>
&emsp;&emsp;&emsp;<a href="#50">2.8.1.4 页面</a></br>
&emsp;&emsp;&emsp;<a href="#51">2.8.1.5 状态处理程序 </a></br>
&emsp;&emsp;&emsp;&emsp;<a href="#52">2.8.1.5.1 路由 </a></br>
&emsp;&emsp;&emsp;&emsp;<a href="#53">2.8.1.5.2 路由组 </a></br>
&emsp;&emsp;&emsp;&emsp;<a href="#54">2.8.1.5.3 事件处理 </a></br>
&emsp;&emsp;&emsp;<a href="#55">2.8.1.6 页面、流、意图的关系</a></br>
&emsp;&emsp;<a href="#56">2.8.2 流的操作</a></br>
&emsp;&emsp;&emsp;<a href="#57">2.8.2.1 增删导入导出</a></br>
&emsp;<a href="#58">2.9 页面的操作 </a></br>
&emsp;&emsp;<a href="#59">2.9.1 设置页面初始回复 </a></br>
&emsp;&emsp;<a href="#60">2.9.2 参数收集</a></br>
&emsp;&emsp;<a href="#61">2.9.3 将意图加入到页面</a></br>
&emsp;&emsp;<a href="#62">2.9.4 条件设置 </a></br>
&emsp;&emsp;<a href="#63">2.9.5 添加事件处理 </a></br>
&emsp;&emsp;<a href="#64">2.9.6 页面的执行顺序 </a></br>
&emsp;&emsp;<a href="#65">2.9.7 意图的操作</a></br>
&emsp;&emsp;&emsp;<a href="#66">2.9.7.1  默认的意图</a></br>
&emsp;&emsp;&emsp;<a href="#67">2.9.7.2 新建意图 </a></br>
&emsp;&emsp;&emsp;<a href="#68">2.9.7.3 上传训练句子到意图 </a></br>
&emsp;<a href="#69">2.11 实体</a></br>
&emsp;&emsp;<a href="#70">2.11.1 “普通实体”和会话实体</a></br>
&emsp;&emsp;<a href="#71">2.11.2 系统实体</a></br>
&emsp;&emsp;<a href="#72">2.11.3 创建实体类型</a></br>
&emsp;&emsp;<a href="#73">2.11.4 上传实体到实体类型</a></br>
&emsp;&emsp;<a href="#74">2.11.5 系统实体表</a></br>
&emsp;&emsp;<a href="#75">2.11.6 日期和时间系统实体类型</a></br>
&emsp;&emsp;&emsp;<a href="#76">2.11.6.1 单个日期实体（sys.date）</a></br>
&emsp;&emsp;&emsp;<a href="#77">2.11.6.2 单个时间实体（sys.time)</a></br>
&emsp;&emsp;&emsp;<a href="#78">2.11.6.3 日期+时间组合实体类型（sys.date-time）</a></br>
&emsp;&emsp;&emsp;<a href="#79">2.11.6.4 日期区间实体(sys.date-period)</a></br>
&emsp;&emsp;&emsp;<a href="#80">2.11.6.5 时间区间实体（sys.time-period）</a></br>
&emsp;&emsp;<a href="#81">2.11.7 实体的original值和resolved值（sys.time-period）</a></br>
&emsp;<a href="#82">2.12 流的版本和环境</a></br>
&emsp;&emsp;<a href="#83">2.12.1 概念</a></br>
&emsp;&emsp;<a href="#84">2.12.2 创建建流版本</a></br>
&emsp;&emsp;<a href="#85">2.12.3 创建环境</a></br>
<a href="#86">3 最佳做法与避坑指南</a></br>
&emsp;<a href="#87">3.1 语料收集方法</a></br>
&emsp;<a href="#88">3.2 问题发现与避免</a></br>



# <a name="0">1. 概念解释</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
## <a name="1">1.1 公司业务的相关的概念</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
### <a name="2">1.1.1 公司项目与场景</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
- 公司场景：截止当前为止，公司的场景分为6类，即：商超、展厅、写字楼、医院、餐饮、酒店。<br>
- 公司项目：以上六大场景分别对应六大类的公司项目，每一个大类的项目有国内与海外之分。如，海外商超项目与国内商超项目。 此文档仅讨论海外项目。<br>
- 商家项目：每个场景的项目的产品的最终使用者是商家，比如一个商家购买了一台商超服务机器人，公司运营人员会给该商家开启一个项目，商家从该项目的管理后台上传必要资料，以使用机器人服务，包
括语义服务。 <br>
- 商家项目id：所有场景下的商家都有唯一的项目id，机器人id和商家项目id具有绑定关系，比如一家餐厅购买了4台餐饮服务机器人，那么该商家的项目对应了4个机器人id。<br>
- 机器人id：所有场景下的机器人都有唯一的设备id <br>
<br>
公司语义服务器根据该器人id，和其所属的商家项目id来请求对应的谷歌代理，并返回结果给APP。<br>
<br>
以下为一个语义请求字段：<br>
其中“project”字段为商家项目id，“deviceID”为机器人设备id,"ask"为用户发言 <br>
```python
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
'''
```
## <a name="3">1.2 谷歌名词概念解释</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
### <a name="4">1.2.1 谷歌项目与代理</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

1. 什么是谷歌项目？<br>
简单来说，这是谷歌为了用户使用他们的服务而设立的。为了使用谷歌的服务，如谷歌地图、STT、TTS,必须建立一个谷歌项目，想要使用谷歌的某服务必须开启对应服务的API。<br>
关于项目管理我们的做法：<br>
目前我们的做法是将谷歌项目当作一类服务的容器，这样便于项目管理和账单查看。 比如,谷歌项目“项目1”只用于Dialoflow CX 代理，“项目2”只用于STT、TTS,“项目3”只用于Google map，注意“项目1”、“项目2”、“项目3”为自定义项目名字，请读者根据规范建立项目名。<br>


2. 什么是代理？<br>
谷歌代理（Agent)是一个功能的抽象，比如订票代理、订房代理、订餐代理，其中订票机器人只负责订票的业务。<br>
本文档所说的代理是Dialogflow CX的代理（Agent)，我们可以在通过代理实现对话机器人搭建。一个谷歌项目下最多可创建1000个代理，谷歌在全球设立了12个大区，创建代理时需选择一个区域，区域代表了该代理存放的地理位置，这将影响到服务访问速度。<br>

3. 什么是流？<br>
流决定了对话的走向，一个代理可以由一个或多个流组成。谷歌提供流级别的版本控制，即可以为每个流打一个或多个版本。 <br>

4. 什么是代理环境？<br>
谷歌代理本身没有版本可言，只有流才有版本控制，那么谷歌怎么做到代理的版本控制呢？<br>

我们可以在Dialogflow控制台(简称控制台）建立环境，环境的名字由我们自定义，代理环境可以被理解为一个文件夹，它对各个版本的流只是一个指向关系。在环境页面，我们需要指定每个流的版本（详细操作流程），如果不指定该流的版本，那么该代理就不具备这个流的功能。 <br>

5. 草稿和环境有什么区别？<br>
从版本的角度来讲，代理可草稿和环境代理。开发人员在控制台编辑的代理叫草稿，环境代理是上述中我们自定义环境中指向的各个版本的流组成的代理。开发人员将草稿代理调试通过后，我们才将该流打版本。 我们需要自定义环境，方便公司研发、生产、测试时访问不同的代理（稍后会讲解具体做法）。<br>

草稿和环境代理在字段上的区别：<br>
草稿代理: 地址没有'/environment/'字段，如：projects/future-area-343501/locations/asia-southeast1/agents/xxxxx <br>
环境代理：地址中有'/environment/'字段，如：projects/future-area-343501/locations/asia-southeast1/agents/xxxxx/environments/xxxx<br>

<img width="900" alt="截屏2022-05-17 下午11 53 26" src="https://user-images.githubusercontent.com/30898964/168820871-44ad95c2-0ff2-493d-9b72-09bee7b07a82.png">

### <a name="5">1.2.2 谷歌的服务</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

1. 我们用到了哪些谷歌服务？<br>

- STT服务，即语音识别，谷歌提供多语种的语音识别、语种识别。
- TTS服务，即语音播报，谷歌提供多语种的男女生播报，截止当前谷歌尚未支持童声（2022-5)
- Dialogflow CX，即谷歌的对话搭建平台，提供意图识别、对话搭建。
- 谷歌地图
<pr>
注：使用这些服务需要先建立谷歌项目，然后开通对应的API。


<img width="1135" alt="截屏2022-05-17 下午9 07 05" src="https://user-images.githubusercontent.com/30898964/168818016-2584397a-9196-4d13-beca-915867373164.png">

### <a name="6">1.2.3 谷歌代理与公司项目</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

    1. 商家代理和谷歌代理的对应关系

    每个商家项目对应唯一一个谷歌代理，代理名为商家项目id，下图中代理的“Display name”为商家项目ID。

 
<img width="900" alt="截屏2022-05-17 下午11 53 26" src="https://user-images.githubusercontent.com/30898964/168855043-86d8a211-b28b-4860-a5e3-bc7d8cad06c8.png">



### <a name="7">1.2.3.1 公司项目和谷歌代理的关系</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

    一个公司场景的项目对应同一种功能的谷歌代理，比如餐饮场景对应餐饮代理，餐饮代理只具有餐饮业务的语义功能。该代理存放了餐饮场景下该商家项目的意图、实体数据（比如菜名、菜口味等)。 
    根据公司研发管理流程，我们现有研发、测试、生产环境，因此我们需要基于此来划分谷歌项目和代理。 


#### <a name="8">1.2.3.2 何为模板代理？</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>


    在理解模板代理之前先要弄清楚什么是动态实体和静态实体。

    动态实体： 指的是商家在管理平台自定义的字段。如商家名、菜名名、客房名、公司名等。我们约定动态实体命名以“DYN_” 开头。
    静态实体： 静态实体是相对动态而言的，可分为武汉人机协作平台（简称平台）预设的实体和语法用途的实体，平台预设的实体命名以“DEF_”开头，比如在餐饮场景中，食材和口味是我们预设的，在平台
    商家菜品配置页面中，以下拉列表呈现，商家只能选择，不能填写。语料用途的实体以“GRA_"开头。这是为了优化训练句子而设置的，比如， "do you have an empty table? "在这句话中，empty有
    很多近义词,下面句子的表达了同样的意思。
    do you have a vacant table?
    do you have a free table?
    do you have an unoccupied table?

    如果有些单词有十几个同义词，我们需要写十几句话。这样做的缺点是：
    a.不方便管理
    b.短语高频出现在训练语料导致意图误触发： 比如单输入“do you have” 也会触发意图。
    所以我们决定通过建立一个实体类型的方式来达到句子同义词扩充的目的。此处我们新建实体类型GRA_EMPTY,其实体集合为：empty/cacant/free/unoccupied


    模板代理是我们根据公司业务抽象而来，而谷歌本身没有模板代理的概念。模板代理产生的原因是为了做到商家的数据分割、场景的业务意图统一。拿餐饮场景来举例，开发人员维护一个模板代理，我们
    希望餐饮场景下的所有项目都具有同样的语义功能，每次新增一个餐饮项目，一个谷歌空代理会被创建，该餐饮项目的代理会把模板代理复制一份，然后直接将其覆盖到该商家代理，这样此商家代理就具有
    了模板代理的所有功能。 值得注意的是，不同的商家配置了不同的菜名、口味等。如何保证商家的数据隔离呢？ 拉取模板代理后，我们会判断哪些是动态实体，然后将该商家的动态实体更新到与之对应的
    谷歌代理。


#### <a name="9">1.2.3.3 为什么要设置多个模板代理</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>


一个场景且一个语言的代理只有一个父模板代理，如香港(英文)餐饮模板代理（名：HkRestaurantEnglishTemplate），但有多个“复制品”。如美国（英文）餐饮模板代理（名：UsaRestaurantEnglishTemplate)。 <br>

a.为了区分公司场景<br>
每个公司场景的机器人都有有不同的业务需求，餐饮代理只负责餐饮相关业务，酒店代理只负责酒店相关业务，在命名上也要区分开（见目录“谷歌项目和代理命名规则”）。<br>

b.为了区分代理的语言 <br>
谷歌代理支持多语种意图服务，虽然可以在一个意图里可以放入多个语言的训练句子，但是这样的做法谷歌不建议，我们当前的做法是一个代理只”说“语种语言，意思一个代理的语料只能是一种语言。<br>

c.为了语义服务响应速度 <br>
在新建代理的时候我们必须选择一个地理区域，这个地理区域决定了该代理的响应速度。举个例子，比如餐饮机器人被部署在美国，那么该餐饮模板代理的位置该是美国或者靠近美国的地区（见目录“代理的创建”。<br>



#### <a name="10">1.2.3.4 模板代理的版本控制</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

上面提到一个谷歌代理具有流级别的版本控制功能，我们为可以为每个流保存一个或多个版本，然后自定义环境来指向每个流的其中一个版本，这样就达到了代理版本的控制。现在我们的做法是，在模板代理里设置3个环境，即研发、生产、测试，然后根据开发情况指向所需要流的版本。因为每个环境的代理都有唯一的地址，我们可以通过环境id来访问不同版本的代理。如下图：<br>

<img width="900" alt="截屏2022-05-18 上午8 56 00" src="https://user-images.githubusercontent.com/30898964/168935522-30b98997-4b73-423c-a60f-6ea94a25b94e.png">
<img width="900" alt="截屏2022-05-18 上午8 57 14" src="https://user-images.githubusercontent.com/30898964/168935620-be5bf150-6abd-4253-8ebc-b940e735a43e.png">


#### <a name="11">1.2.3.5 父模板代理与“复制品”的关系</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

##### 什么是父模板代理？
<p>
   父模板代理是bot开发人员的主要操作对象，是根据公司业务取名而来，谷歌本身没有父模板代理或模板代理概念。对于一个语言下的公司场景，我们只设置一个父模板代理，其他地区的同样场景和同样语言的代理是从父模板复制而来。我们约定将香港的模板代理作为父模板代理，而全球其他地区的同场景同语言的模板代理只从父模板代理复制。比如“香港（英文）餐饮代理”是父模板，“美国（英文）餐饮代理"就是香港英文餐饮代理的复制品。
</p>
   
##### 父模板代理的环境
<p>
当前我们在父模板代理中自定义研发、生产、测试环境，但其“复制品”代理无环境，复制品从父模板代理复制后默认保存在草稿代理。简单来说，“复制品”代理存在的意义只是为了地区访问速度而设置。为每个复制品代理设置环境无意义。商家项目的代理会遵从地理位置就近的原则，从最近的模板代理的草稿拉去数据。 因此在每次语义版本迭代的时候，代理通过研发和测试无误后，我们将生产环境指向该代理。然后将该代理导出，再手动导入到“复制品”代理。
</p>

#### <a name="12">1.2.3.6 谷歌项目、代理、意图的命名规范</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

    a.模板代理的命名约定
    
    命名规则如下：
    第一部分代表大区名， "Hk"代表香港 
    第二部分代表场景，“Office”代表写字楼 
    第三部分代表语言，“English”代表英语 
    例如，“美国写字楼（英语）模板代理”命名为“UsaOfficeEnglishTemplate“，同理：
    - HkOfficeEnglishTemplate 香港写字楼（英语）模板代理
    - UsaOfficeEnglishTemplate 美国写字楼（英语）模板代理
    - HkHotelEnglishTemplate 香港酒店（英语）模板代理
    - UsaHotelEnglishTemplate 美国酒店（英语）模板代理
       
    b.意图命名约定
    
    意图命名规范： 语言+场景+行为意图名 
    第一部分为语言，如“english“代表英语，其他语言请参照英文翻译
    第二部分为场景，第二部分由公司场景名或“public"组成，
        其中公司场景名为：
        餐饮 对应 ”restaurant“ 
        酒店 对应 "hotel" 
        写字楼 对应 "office"
        商超 对应 “shopping”
        医院 对应 ”hospital“
        展厅 对应 ”exhibition“    
        展厅 对应 ”exhibition“
        ”public“为机器人所有场景机器人公有意图，如： ”返回“、”开灯“、”问机器人名字“，”打招呼“。
    第三部分是行为表达的英语，如查询、预约、取号等。查询类意图用 query_xxx, ”xxx“为对象名。如英语查询营业时间的意图命名为 "english_public_query_businiess_time",因为查询营业    
    时间是公共意图，所以这里用”public“。其他意图根据情况取名，但是注意取名要要统一，表达要简要。意图取名不能重复，全小写。
    对于每个意图，如果有否定意图，其否定意图的命名为直接在肯定意图的结尾加”_neg“, 如”english_public_query_businiess_time_neg“是查询营业时间的否定意图。
    
    
    c.实体类型命名约定
    
    上面详细解释了何为动态实体、自定义实体、语法用途的实体。
    以”GRA_"开头为语法用途的实体
    以”DEF_"开头为平台定义的实体
    以”DYN_"开头为动态实体


    d.谷歌项目的命名约定
    
    模板代理的存放位置:
    现在公司的做法是只设立一个谷歌项目用于存放所有代理的父模板和“复制品”代理。将一个语言一个场景下的香港模板代理作为父模板代理。
    如：HkRestaurantEnglishTemplate、HkHoteltEnglishTemplate 分别为餐饮场景、酒店场景的父模板代理。
    
    项目的取名：
    谷歌地图项目：名字固定为“GoogleMap”
    
    语音识别、语音播报项目：名字固定为 “STTProject”
    
    测试环境谷歌项目：名字固定为“TestProject”，用于存放所有场景下测试环境的商家代理。
    
    研发环境谷歌项目：名字固定为“DevelopmentProject”，用于存放所有场景下研发环境的商家代理。
    
    生产环境的谷歌项目: 地区名+公司场景名+语言+Project”.
    注:一个谷歌项目最多能建立1000个代理，生产环境的谷歌项目用于商家代理，随着商家的客户的新增，谷歌代理数量同比增多。所以，商家谷歌代理会存在多个。
    当一个生产环境谷歌项目的代理占用量到达一定比例的时候，需要提前新建谷歌项目并初始化代理地区（初始化代理区域见目录“代理的创建”）
    
    命名例子如下：
    UsaRestaurantEnglishProject 美国餐饮英语生产环境项目
    HkRestaurantEnglishProject 香港餐饮英语生产环境项目
    HkOfficeEnglishProject  美国写字楼英语生产环境项目
    UsaOfficeEnglishProject 美国写字楼英语生产环境项目
     
     
## <a name="13">1.3 公司业务与谷歌服务的融合</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>


### <a name="14">1.3.1 父模板代理及其环境</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>


#### 我们设立研发环境的谷歌项目（DevelopmentProject）和测试环境的谷歌项目（TestProject）、生产环境的谷歌项目。那么这三个项目从哪里复制模板代理数据？
<p>
在上面提到了我们只在父模板代理里自定义研发、测试、生产环境，谷歌研发项目中所有的代理只从父模板代理的研发环境复制。同理，谷歌测试项目中所有代理只从父模板代理的测试环境复制。而生产环境的谷歌代理处理方式则不同，我们需要把父模板的生产环境的代理导入到各大区的“复制品”模板代理。语义服务数据库存有一表，该表指明了生产环境的某商家项目该从哪个模板代理复制。从模板代理处拉取代理数据后，该商家代理会清空所有数据并用模板代理的数据直接覆盖当前代理(包括意图、实体等)。然后，该商家代理会自动更新动态实体，并自动训练。
</p>

<img width="800" alt="image" src="https://user-images.githubusercontent.com/30898964/168944420-3f23efa7-dc45-4624-9e2c-a511c64cedea.png">

<p>
我们有六大场景，每个场景都有与之对应的模板代理项目、研发环境谷歌项目、测试环境谷歌项目、生产环境谷歌项目。具体关系如下图所示。其中，模板代理项目的用于存放父模板代理和“复制品”代理，研发环境谷歌项目用于存放公司研发环境的代理，测试环境谷歌项目（TestProject）用于存放公司测试环境的代理，这些代理一般是由测试部门同事新建。
</p>
    
<img width="862" alt="截屏2022-05-18 下午3 04 13" src="https://user-images.githubusercontent.com/30898964/168977930-25642ff0-02ef-4828-95b8-5d1e2320f51f.png">


# <a name="15">2 实践操作</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

## <a name="16">2.1 登录google cloud platform</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

[登录链接](https://console.cloud.google.com/user-preferences/cloud-profile)

## <a name="17">2.2 新建谷歌项目</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

### <a name="18">2.2.1 步骤1：</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

<img width="1009" alt="截屏2022-05-27 上午11 31 07" src="https://user-images.githubusercontent.com/30898964/170623635-7753fef3-3908-4b89-9580-4eaff12d0d55.png">

### <a name="19">2.2.2 步骤2：</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

注：一个google 账号可以创建25个项目，如需要创建更多项目，需要申请开通。<br>
 <br>
<img width="612" alt="截屏2022-05-27 上午11 32 20" src="https://user-images.githubusercontent.com/30898964/170623753-6b752cb9-03e8-40cc-b95c-73b8f019b160.png">


稍等几分钟，刷新 google cloud platform, 刚创建的项目已经展示在项目列表里。<br>

<img width="1000" alt="截屏2022-05-27 上午11 32 35" src="https://user-images.githubusercontent.com/30898964/170623781-7928d887-a6bb-4c58-bf17-5c3c6770ffd9.png">


## <a name="20">2.3 为该项目创建服务账号 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

### <a name="21">2.3.1 什么是服务账号？</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

是一个供计算机用的虚拟账号，用来访问Google Cloud资源。
[链接](https://cloud.google.com/iam/docs/service-accounts?hl=zh-cn&_ga=2.98308319.-139742340.1639388700)

### <a name="22">2.3.2 创建服务账号</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
步骤1:<br>

<img width="859" alt="截屏2022-05-27 上午11 33 23" src="https://user-images.githubusercontent.com/30898964/170623865-9d8fa7d9-7ed0-4f8e-a396-193c0afae741.png">

步骤2:<br> 

<img width="604" alt="截屏2022-05-27 上午11 33 46" src="https://user-images.githubusercontent.com/30898964/170623888-1b0fad4d-b758-4f89-b7be-d9f8a8f59deb.png">

步骤3:<br>

<img width="624" alt="截屏2022-05-27 上午11 33 57" src="https://user-images.githubusercontent.com/30898964/170623910-3477cf31-af02-4284-b123-faea3f17233b.png">


步骤4:<br>
 
为该服务账号创建其密匙 <br>
 <br>
<img width="1008" alt="截屏2022-05-27 上午11 34 14" src="https://user-images.githubusercontent.com/30898964/170623953-ad07d4d3-8614-467c-b225-cd89b0be19a6.png">

<img width="1011" alt="截屏2022-05-27 上午11 34 52" src="https://user-images.githubusercontent.com/30898964/170624027-14587c6d-2a20-4e5d-8510-cf200d3420e3.png">

选择json,点击创建后自动下载json格式的密匙，稍后将会用到。

<img width="1008" alt="截屏2022-05-27 上午11 35 20" src="https://user-images.githubusercontent.com/30898964/170624066-77a692fb-ee53-4b03-a4c9-46b61b566c88.png">

## <a name="23">2.4 最佳做法与解决方案</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

### <a name="24">2.4.1 谷歌技术人员给出的建议：</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
为一个谷歌项目创建其对应的服务账号，如果有多个谷歌项目，就需要多个服务账号，这样方便账单的计算。 这样基于最小权限原则，对项目管理也相对安全。 <br>
虽然基于最小原则会更安全，但因在linux环境变量中只能设置一个json密匙。我们用到了多个谷歌项目，多把服务账号密匙会造成不好管理。所以我们只生成其中一个谷歌项目的服务账号密匙，这一个密匙用来做所有谷歌代理项目的访问密匙。<br>

一把密匙访问多项目的做法： <br>
将其中一个服务账号作为主账号，其功能是生成json密匙，我们可以根据需求将主账号的服务账号作为owner角色添加到其他账号。 谷歌的服务账号本身并没有主次等级关系，这样做完全基于公司的的业务管理需求。
以此达到了使用一把json密匙，访问到多个dialogflow cx项目 <br>

### <a name="25">2.4.2 具体步骤：</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
假如现在有两个谷歌项目，项目名为分别为projectTest1，catering Robot。 这两个项目都已经通过上面的方式建立了自己的服务账号，我们想要做到用catering Robot的密匙访问projectTest1. <br>

步骤1：
复制catering Robot的服务账号。

<img width="1011" alt="截屏2022-05-27 上午11 36 07" src="https://user-images.githubusercontent.com/30898964/170624145-fedb0daf-9b19-4a86-b8c8-8cd7189a06b5.png">

步骤2：
添加catering robot的服务账号到projectTest1，并给予owner权限。<br>

<img width="915" alt="截屏2022-05-27 上午11 36 45" src="https://user-images.githubusercontent.com/30898964/170624208-f5861569-8126-4254-8d00-4865e5c8902a.png">

<img width="899" alt="截屏2022-05-27 上午11 36 57" src="https://user-images.githubusercontent.com/30898964/170624230-549199fd-74ed-428c-83d7-d4fe8e847c31.png">


## <a name="26">2.5 设置环境变量</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

[链接](https://cloud.google.com/iam/docs/service-accounts?hl=zh-cn&_ga=2.98308319.-139742340.1639388700)

拿到上一步下载的json密匙绝对路径

### <a name="33">2.5.1 windows 用户的环境变量设置</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

前提：windows+pycharm  <br>

以下配置方法生效范围为整个pycharm项目目录

假设你的json密匙绝对路径为：C:\Users\admin\xxxx\xxxbcb6202b4.json

环境变量格式： GOOGLE_APPLICATION_CREDENTIALS=C:\Users\admin\xxxx\xxxbcb6202b4.json

选中pycharm项目中任一py文件，单击右上角。

<img width="798" alt="截屏2022-05-27 上午11 37 41" src="https://user-images.githubusercontent.com/30898964/170624314-67d15d8b-9927-490b-98be-0b7d063d5bf7.png">

<img width="463" alt="截屏2022-05-27 上午11 38 03" src="https://user-images.githubusercontent.com/30898964/170624344-82857484-4870-4bf9-aaeb-88f428bad0c2.png">

在红色框出输入GOOGLE_APPLICATION_CREDENTIALS=C:\Users\admin\xxxx\xxxbcb6202b4.json

点击apply，这样你就可以访问谷歌项目了。

<img width="1011" alt="截屏2022-05-27 上午11 38 24" src="https://user-images.githubusercontent.com/30898964/170624384-2ab9d5f2-3b66-425c-9970-e1b70641e54e.png">



### <a name="27">2.5.1 linux, mac 用户的环境变量设置</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

可以直接把json密匙路径配置到用户环境变量，生效范围为该linux系统的用户，当然你也可也设置linux系统级的环境变量（参照链接：https://www.cnblogs.com/lihao-blog/p/6945040.html）

下面展示把json密匙配置到linux用户级的环境变量。

1 进入用户的根目录

cd  $HOME 或 cd ~

$ vim  .bashrc

2 然后打开.bashrc若不存在则新建.bashrc文件

vim  .bashrc

3 在.bashrc页面最后加上想要加的路径

export PATH=/var/www_r/www_bot/catering-robot-aecbcb6202b4.json

请将json密匙的地址替换为你的绝对路径。

<img width="544" alt="截屏2022-05-27 上午11 39 11" src="https://user-images.githubusercontent.com/30898964/170624451-3c7241aa-3b2e-4d6b-8d5a-16dcd809d015.png">


4 最后执行

source ~/.bashrc

搞定！


## <a name="28">2.6 代理的操作 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
### <a name="29">2.6.1 代理的创建</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
我们可以通过API、客户端、控制台创建代理,这里仅展示通过控制台、客户端创建代理。
#### <a name="30">2.6.1.1 通过控制台创建</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

登录后，在project下拉框，你会发现刚刚创建的google could 项目 projectTest已经显示到了这里。
1.点击 Enable API ->create agent

下面截图说明：

Displayname: 代理名字，一个location下的代理名字不能重复，

location：代理所在的google服务器的区域，这会影响到意图识别的访问速度，建议就近原则。代理位置一旦选定，不可以改变。 

Default language：代理使用的语言，这决定了意图识别、实体的主要语言，一个代理只能选中一门语言作为主识别语言。 虽然你可以把多国语言作为训练语句加入意图，但这样做不利于管理。 

Time zone：代理所用的时区，时区决定了代理所用的时间，这将影响系统实践类实体的返回结果。
<img width="609" alt="截屏2022-05-27 上午11 39 43" src="https://user-images.githubusercontent.com/30898964/170624528-e2d0367a-9702-4bff-978b-09e33f5a5d23.png">


代理创建说明：
dialogflow代理id为谷歌自动生成，创建代理成功后可以通过API或者客户端库拿到代理的id，也可以在控制台的导航栏查看代理的id。

<img width="1014" alt="截屏2022-05-27 上午11 40 04" src="https://user-images.githubusercontent.com/30898964/170624565-66ad98a2-51ab-43fb-a7c8-fab2410fa6cb.png">


一个google dialogflow cx项目（也叫google cloud项目）下可以创建1000个代理，具体参数限制如下表。
<img width="873" alt="截屏2022-05-27 上午11 40 20" src="https://user-images.githubusercontent.com/30898964/170624598-e75db3ec-03c0-4b6f-9a14-72e10a513296.png">


#### <a name="31">2.6.1.2 代理地区的手动初始化</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

为什么要初始化代理的地区？

我们需要先初始化代理地区，然后才能新建位于该地区的谷歌代理。代理地区初始化必须在控制台手动完成。如果不初始化某个地区，当我们使用api创建位于该地区的代理时，会发生代理创建失败的错误！<br>
在控制台“新建代理”的页面就可以把该谷歌项目下的所有代理地区初始化。 所以每次新建一个谷歌项目（用于存放代理的项目）第一件要做的事就是初始化代理地区。<br>
具体操作如下：<br>
step1： 在控制台点击“Create Agent”<br>
step2： 对于代理的“location”下拉列表中的每一个地区都执行下面两张图的操作。如果该地区没有初始化，当选中这个location的时候会出现“You have selected a location that has not been configured yet.”<br>

<img width="500" alt="截屏2022-05-24 下午2 18 13" src="https://user-images.githubusercontent.com/30898964/169962078-93a295dd-1e9e-48d7-8ac9-9b0af1009b17.png"><img width="500" alt="截屏2022-05-24 下午2 18 12" src="https://user-images.githubusercontent.com/30898964/169962164-a6709f75-11df-4a66-852a-1ab2413e3fc4.png">

#### <a name="32">2.6.1.3 通过客户端创建</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

通过客户端创建代理需要传入的参数：</br>
project_id：项目id， 最简单的方法是直接复制Dialogflow控制台导航栏的url并截取相关部分。</br>
location：代理所在的谷歌服务器区域，目前已经开通12个服务区域，见下表。</br>
time_zone：代理所使用的时区，这会直接影响到系统时间类实体的返回结果，因为系统时间实体的提取是依靠当前代理选取的timezone为准。</br>
language_code：代理所使用的主识别语言。</br>
display_name： 给代理取名，注意一个区域下的代理名字不能重复</br>

注：当通过API或客户端创建代理时，如果报错：“Location settings have to be initialized before creating the agent in location: asia-northeast1. Code: FAILED_PRECONDITION“，请将该项目的代理location初始化，初始化方法见上一小节 </br>

运行代码前须知：<br>
> 先安装客户端库，安装命令为：$pip install google-cloud-dialogflow-cx <br>
> 确保已经配置好该代理所属项目的json密匙，并将密匙下载到本地，然后加入到环境变量（见”最佳做法与解决方案“）。  <br>

无权限的几种情况：<br>
- 没把该代理所属项目的密匙添加到环境换辆。见”最佳做法与解决方案“<br>
- 把其他项目的密匙加入了环境变量。<br>
<br>
解决方式：<br>
方法1：将一个项目的密匙作为唯一的访问谷歌代理的密匙，在其他谷歌项目给予这个项目owner权限（见”最佳做法与解决方案“） <br>
方法2：使用本项目的密匙，使用”一次性环境“变量。<br>
mac或linux用户， 在终端或命令行输入：$export GOOGLE_APPLICATION_CREDENTIALS=“{密匙的绝对路径}",<br>
如：export GOOGLE_APPLICATION_CREDENTIALS="/Users/xxx/xx/xxx/xxxx801182eb71.json" 然后通过命令行运行谷歌dialogflow相关代码，关掉该终端的窗口后，GOOGLE_APPLICATION_CREDENTIALS环境变量失效。下次需要重新打开终端并输入命令。<br>

请根根据实际情况传入参数。<br>
[文档链接](https://googleapis.dev/python/dialogflow-cx/latest/dialogflowcx_v3beta1/agents.html)

新建代理的示例代码：<br>

```python
from google.cloud.dialogflowcx_v3beta1.types import CreateAgentRequest,CreateAgentRequest,Agent
from google.cloud.dialogflowcx_v3beta1.types.agent import ListAgentsRequest,ExportAgentRequest,RestoreAgentRequest
from google.cloud.dialogflowcx_v3beta1.services.agents import AgentsClient
import uuid

def crateAgent(project_id='catering-robot',location='asia-northeast1',time_zone='Asia/Hong_Kong',language_code='en'):
    agent = Agent()
    agent.display_name = 'AgentExampleName' # 自定义代理的名字
    agent.default_language_code = language_code
    agent.time_zone = time_zone
    parent = f'projects/{project_id}/locations/{location}'
    create_agent_request = CreateAgentRequest(parent=parent,agent=agent)
    agentClient = AgentsClient(client_options={"api_endpoint": f"{location}-dialogflow.googleapis.com"})
    agent_response= agentClient.create_agent(create_agent_request)
    return agent_response
    
```
返回结果：<br>
name: 为代理的id，全局唯一，为谷歌自动生成。 <br>
display_name：我们刚为代理取的名字<br>

    name: "projects/catering-robot/locations/asia-northeast1/agents/af11663a-757a-4067-bd7d-78aed12a7750"
    display_name: "AgentExampleName"
    default_language_code: "en"
    time_zone: "Asia/Hong_Kong"
    start_flow: "projects/catering-robot/locations/asia-northeast1/agents/af11663a-757a-4067-bd7d-78aed12a7750/flows/00000000-0000-0000-0000-000000000000"
    advanced_settings {
      logging_settings {
      }
    }


#### <a name="33">2.6.1.4 代理的时区、语言、区域表</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

请查看谷歌官方文档以得到最新列表，此附录跟新时间为2022.5.24<br>
区域：<br>
```python
'''
us-central1 (Iowa, USA)
us-east1 (South Carolina, USA)
us-west1 (Oregon, USA)
asia-northeast1 (Tokyo, Japan)
asia-south1 (Mumbai, India)
asia-southeast1 (Jurong West, Singapore)
australia-southeast1 (Sydney, Australia)
northamerica-northeast1 (Montréal, Québec, Canada)
europe-west1 (St. Ghislain, Belgium)
europe-west2 (London, England, UK)
europe-west3 (Frankfurt, Germany)
global (Global serving, data-at-rest in US)
'''
```

语言：<br>
```python
'''
af — Afrikaans
am — Amharic
ar — Arabic
az — Azerbaijani
be — Belarusian
bg — Bulgarian
bn — Bengali
bs — Bosnian
ca — Catalan
ceb — Cebuano
co — Corsican
cs — Czech
cy — Welsh
da — Danish
de — German
el — Greek
en — English
eo — Esperanto
es — Spanish
et — Estonian
eu — Basque
fa — Persian
fi — Finnish
fil — Filipino
fr — French
fy — Frisian
ga — Irish
gd — Scots
gl — Galician
gu — Gujarati
ha — Hausa
hi — Hindi
hmn — Hmong
hr — Croatian
ht — Haitian
hu — Hungarian
hy — Armenian
id — Indonesian
ig — Igbo
is — Icelandic
it — Italian
iw — Hebrew
ja — Japanese
jv — Javanese
ka — Georgian
kk — Kazakh
km — Khmer
kn — Kannada
ko — Korean (South Korea)
ku — Kurdish
ky — Kyrgyz
la — Latin
lb — Luxembourgish
lt — Lithuanian
lv — Latvian
mg — Malagasy
mi — Maori
mk — Macedonian
ml — Malayalam
mn — Mongolian
mr — Marathi
ms — Malay
mt — Maltese
ne — Nepali
nl — Dutch
no — Norwegian
ny — Chichewa
or — Odia
pa — Punjabi
pl — Polish
ps — Pashto
pt — Portuguese (European)
pt-br — Portuguese (Brazilian)
ro — Romanian
ru — Russian
rw — Kinyarwanda
sd — Sindhi
si — Sinhala
sk — Slovak
sl — Slovenian
sm — Samoan
sn — Shona
so — Somali
sq — Albanian
sr — Serbian
st — Sesotho
su — Sundanese
sv — Swedish
sw — Swahili
ta — Tamil
te — Telugu
tg — Tajik
th — Thai
tk — Turkmen
tr — Turkish
tt — Tatar
ug — Uyghur
uk — Ukrainian
ur — Urdu
uz — Uzbek
vi — Vietnamese
xh — Xhosa
yi — Yiddish
yo — Yoruba
zh-cn — Chinese (Simplified)
zh-hk — Chinese (Hong Kong)
zh-tw — Chinese (Traditional)
zu — Zulu
'''
```

时区：<br>
``` python
'''
(GMT+1:00) Africa/Casablanca
(GMT-9:00) America/Anchorage
(GMT-4:00) America/Barbados
(GMT-3:00) America/Buenos_Aires
(GMT-6:00) America/Chicago
(GMT-7:00) America/Denver
(GMT-8:00) America/Los_Angeles
(GMT-5:00) America/New_York
(GMT+6:00) Asia/Almaty
(GMT+7:00) Asia/Bangkok
(GMT+5:30) Asia/Colombo
(GMT+4:00) Asia/Dubai
(GMT+8:00) Asia/Hong_Kong
(GMT+4:30) Asia/Kabul
(GMT+5:45) Asia/Kathmandu
(GMT+6:30) Asia/Rangoon
(GMT+9:00) Asia/Tokyo
(GMT+5:00) Asia/Yekaterinburg
(GMT-1:00) Atlantic/Cape_Verde
(GMT-2:00) Atlantic/South_Georgia
(GMT+9:30) Australia/Darwin
(GMT+10:00) Australia/Sydney
(GMT-12:00) Etc/GMT+12
(GMT+2:00) Europe/Kaliningrad
(GMT) Europe/London
(GMT+1:00) Europe/Madrid
(GMT+3:00) Europe/Moscow
(GMT+12:00) Pacific/Fiji
(GMT-10:00) Pacific/Honolulu
(GMT-11:00) Pacific/Midway
(GMT+11:00) Pacific/Noumea
(GMT+13:00) Pacific/Tongatapu
(GMT-9:00) US/Alaska
'''
```


### <a name="34">2.6.2 代理的导出</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
#### <a name="35">2.6.2.1 使用控制台导出</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
步骤1：</br>
</br>
![image](https://user-images.githubusercontent.com/30898964/150994138-4e1a7d7a-3f05-46a4-91aa-bb2f5b4bf02c.png)
步骤2：</br>
</br>
![image](https://user-images.githubusercontent.com/30898964/150997846-3822be2d-1bc7-49db-b099-822f6eec67dd.png)

#### <a name="36">2.6.2.2 使用客户端库导出</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

[文档链接](https://googleapis.dev/python/dialogflow-cx/latest/dialogflowcx_v3beta1/agents.html)

这里只是为了展示代理导出的功能才使用while True，在实际项目中，请不要这样使用。</br>
下面代码段的功能是导出指定环境的代理,当然如果不指定环境，导出的将是草稿代理。</br>
拿到指定环境的代理地址最直接的方法是从控制台复制，如下图：</br>
</br>

![image](https://user-images.githubusercontent.com/30898964/151000104-690ec26e-ffa7-43ff-adbd-4b56956a6148.png)


```python
from google.cloud.dialogflowcx_v3beta1.types import CreateAgentRequest,CreateAgentRequest,Agent
from google.cloud.dialogflowcx_v3beta1.types.agent import ListAgentsRequest,ExportAgentRequest,RestoreAgentRequest
from google.cloud.dialogflowcx_v3beta1.services.agents import AgentsClient
import time


# 此段代码的的功能是将代理导出为二进制文件，导出的代理为在自定义环境中的代理
def exportAgent2binary_from_environment(agent_path_environment):
    agent_binary_document=''

    agent_path = agent_path_environment.split('/environment')[0]
    location = AgentsClient.parse_agent_path(agent_path)['location']
    agentClient = AgentsClient(client_options={"api_endpoint": f"{location}-dialogflow.googleapis.com"})
    request = ExportAgentRequest(name=agent_path,environment=agent_path_environment)
    export_operation = agentClient.export_agent(request)
    while export_operation.done==False:
        time.sleep(1)
        print('not completed yet')
    else:
        response =export_operation.result()
        agent_binary_document = response.agent_content
    return agent_binary_document


# 此段代码的的功能是将代理导出为二进制文件，导出的代理为草稿
def exportAgent2binary_from_draft(from_agent_path):
    agent_binary_document=''

    location = AgentsClient.parse_agent_path(to_agent_path)['location']
    agentClient = AgentsClient(client_options={"api_endpoint": f"{location}-dialogflow.googleapis.com"})
    request = ExportAgentRequest(name=to_agent_path)
    export_operation = agentClient.export_agent(request)
    while export_operation.done==False:
        time.sleep(1)
        print('not completed yet')
    else:
        response =export_operation.result()
        agent_binary_document = response.agent_content
    return agent_binary_document

if __name__ == '__main__':
    # 请将您的实际代理路径传入
    from_agent_path_draft = 'projects/catering-robot/locations/asia-northeast1/agents/45486b7f-c80c-447e-b41d-73bcdfa33ded'
    from_agent_path_env='projects/catering-robot/locations/asia-northeast1/agents/45486b7f-c80c-447e-b41d-73bcdfa33ded/environments/dea15f7d-1ef8-4bd5-8892-1331670a6fd8'
    exportAgent2binary_from_environment(from_agent_path_env)
    exportAgent2binary_from_draft(from_agent_path_draft)


```

### <a name="37">2.6.3 代理的导入</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
#### <a name="38">2.6.3.1 通过控制台导入</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

步骤1：
![image](https://user-images.githubusercontent.com/30898964/151000728-1e3709d1-e8e3-41de-8522-c01a2979176f.png)
步骤2：
选中被需要被导入的代理->上传本地的代理文件->导入 </br>
注意：根据需要备份被导入的代理，一旦执行restore操作，将会把现有草稿代理覆盖，之前草稿代理的所有数据会被清空。
![image](https://user-images.githubusercontent.com/30898964/151000911-11d2ff7b-c764-4bd4-8074-e40ee51181ef.png)


#### <a name="39">2.6.3.2 通过客户端库导入</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
步骤：</br>
1. 先导出一个代理，拿到该代理的二进制文件；</br>
2. 通过新建一个代理或者使用现有的代理，然后执行导入操作；</br>
以下代码段仅展示效果，可参照客户端库文件了解详细导入操作。</br>

[文档链接](https://googleapis.dev/python/dialogflow-cx/latest/dialogflowcx_v3beta1/agents.html)

``` python 
from google.cloud.dialogflowcx_v3beta1.types import CreateAgentRequest,CreateAgentRequest,Agent
from google.cloud.dialogflowcx_v3beta1.types.agent import ListAgentsRequest,ExportAgentRequest,RestoreAgentRequest
from google.cloud.dialogflowcx_v3beta1.services.agents import AgentsClient
import uuid
import time

def restore_agent(agent,agent_binary):
    location = AgentsClient.parse_agent_path(agent)['location']
    agentClient = AgentsClient(client_options={"api_endpoint": f"{location}-dialogflow.googleapis.com"})
    request = RestoreAgentRequest(name=agent,agent_content=agent_binary)

    restore_operation = agentClient.restore_agent(request=request)
    start = time.time()
    while restore_operation.done==False:
        time.sleep(1)

        print('not completed yet')
    else:
        end = time.time()
        print(f'agent updated, timeout:{end-start}')
        
if __name__ == '__main__':
    agent_binary_document = exportAgent2binary_from_draft(from_agent_path_draft) # 被导出的代理二进制，可以为从草稿代理导出或环境代理导出
    agent_to_be_restored= 'projects/catering-robot/locations/asia-northeast1/agents/XXXX' # 被导入的草稿代理地址，注意只能导入到草稿代理，不能导入到环境代理。
    restore_agent(agent_to_be_restored,agent_binary_document)


```

### <a name="40">2.6.4 代理的删除</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
#### <a name="41">2.6.4.1 通过控制台删除</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
步骤1：
![image](https://user-images.githubusercontent.com/30898964/151003260-1087ad8a-5bf7-4a7e-a9e7-719578b717c8.png)
步骤2：
![image](https://user-images.githubusercontent.com/30898964/151003345-e5242c6d-2154-450b-92ac-560c9648f050.png)


#### <a name="42">2.6.4.2 通过客户端库删除</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
待更新......</r>
通过客户端库删除代理的方法和创建代理类似，可参照谷歌文档。 

## <a name="43">2.7 Dialogflow 控制台面板功能介绍</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>


<img width="600" alt="截屏2022-05-26 上午1050" src="https://user-images.githubusercontent.com/30898964/170485518-591c8bca-c00e-4575-be6b-eb24ad5babfb.png">
<img width="600" alt="截屏2022-05-26 上午1050" src="https://user-images.githubusercontent.com/30898964/170485532-260b6d0e-c661-4683-aed1-7fe860f4d18e.png">

按钮说明：<br>
Agent settings中的NLU type：<br>
这里是默认选择了标准NLU, 标准NLU会在更改草稿后自动训练，如果选择Advanced NLU，每次更新流就必须手动训练，这个选项适合大型流。 </br>

Classification thredshould：<br>
意图检测的阈值，如果意图匹配的置信度分数小于阈值，则会调用[无匹配事件](https://cloud.google.com/dialogflow/cx/docs/concept/handler#event-built-in)


### <a name="44">2.7.1 在控制台测试代理 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

点击右边test Agent可对创作好的代理进行测试。

我在测试窗口中输入了 when is your store hours 

测试窗口:</br>

- Default start flow ：代表流名字，这里指页面Strore Hours所在的流名。

- Strore Hours： 代表页面名字,这里指意图store.hours所在的页面名字。

- store.hours： 是当如输入测试语句后所命中的意图名。

- 点击小本本图标可以看到当前会话返回的详细json参数。

- 点击垃圾箱的图标会清除当前会话的所有数据，再次输入语句测试的时候就会生成一个新的session id测试控制台的代理。

- Execution steps： 点击下拉框可以看到当前会话的从开始到当前状态的执行步骤。

- Environment: Draft:  这里的意思是当前测试的是草稿代理，如果您建立了代理版本打开测试代理就会弹出代理版本供您选择测试。

<img width="900" alt="截屏2022-05-26 上午1050" src="https://user-images.githubusercontent.com/30898964/170486137-03db21a3-2caf-48d2-98b1-13f16f507ee5.png">
<img width="900" alt="截屏2022-05-26 上午10 450" src="https://user-images.githubusercontent.com/30898964/170486141-da3acd67-0387-4379-a3bb-603368b9386e.png">

## <a name="45">2.8 代理各组件概念与操作</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
### <a name="46"> 2.8.1 概念</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
#### <a name="47"> 2.8.1.1 意图</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

意图：表达用户的意图，一个代理可以定义多个意图，我们需要根据业务对用户意图进行分类，意图分类也叫意图匹配。比如餐饮场景下的用户意图有查看菜单、查看菜品等。

#### <a name="48"> 2.8.1.2 实体类型</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

- 实体类型：可以认为是某一个概念，比如人名、地名、公司名、菜名、店铺名。
- 实体：某一个概念的实例，比如张三、深圳、科卫机器人、红烧肉、星巴克。张三属于人名实体类型，深圳属于地名实体类型。
- 
#### <a name="49"> 2.8.1.3 流</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

流分为默认初始流（Default start flow）和非初始流，非初始流也是开发人员自定义的流（见下图）。<br>
<p>
每个代理有且仅有一个默认初始流，初始流无法删除,这是对话的入口。对于构造简单的代理，您可能只需要这一个流。如果业务量多或者对话逻辑太复杂，我们可以根据功能模块的划分，自定义多个流，一个流执行一类的操作，这样方便流的管理和后期流的版本控制。比如你想搭建一个定外卖的bot，这个bot需要点餐、下订单、支付三个功能，那么我们就设计三个流，即点餐流、下订单流、支付流，负责点餐的开发人员只需要维护点餐的流。将来点餐模块的功能如果有变动，只修改点餐流并不会对其他流造成影响。
</p>
- 多个流之间可以相互协作，可以共享整个对话的数据。 
- 默认初始流的ID为00000000-0000-0000-0000-000000000000
- 每个流都有一个默认的start page，在调用该代理的API或使用客户端时，可以通过 pageId=START_PAGE 判断是否为开始流。

![image](https://user-images.githubusercontent.com/30898964/170424511-0bc514da-287c-4c12-87f9-620029d3136a.png)

#### <a name="50"> 2.8.1.4 页面</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

<p>
页面可以分为默认初始流的开始页面、自定义流开始页面、非开始页面，开始页面无法删除。非开始页面指的是默认初始流和自定义流中的非开始页面，非开始页面的功能都一样。 而默认初始流和自定义初始流的功能不一样，其主要区别如下：
</p>

- 区别1：非开始页面比默认流开始页和自定义流开始页面多了一个Entry fulfilement，这是用于进去页面时的引导话术设置。
- 区别2：默认开始流的开始页面有欢迎意图（Default welcome Intent）,这是代理默认就有的，该意图无删除，也无法改名。如果我们想自定义打招呼的意图且给意图换个名字，我们能做的就是把默认欢迎意图中的训练句子全删掉，这样默认欢迎意图就不会被触发。
- 区别3：默认初始流的开始页面和自定义流的开始页面有默认的事件处理，我们可以在这里设置对仅该流有效的全局事件处理（详情见下一节“状态处理程序”）。 
- 区别4：开始页面中不可以设置参数收集，而非开始页面可以设置。

![image](https://user-images.githubusercontent.com/30898964/170432127-1a7fd63e-4a2f-4cb8-8ec4-9311079f4b9c.png)

页面的特点：<br>

- 反映一个对话当前在什么状态，下图为一个简单的订餐bot，这里有三个页面，每个页面反应了订餐的状态。
- 页面是一个容器，一个页面可以“装”很多意图，只有把意图加入了该页面，当对话进行到该页面时候，这些意图才可能被触发。
- 一个页面包含了导向对话的逻辑操作。
- 在一个页面可以设置回复语句。

<img width="300" alt="截屏2022-05-26 上午10 44 50" src="https://user-images.githubusercontent.com/30898964/170402753-6e40d385-d9ba-4968-b2a6-e091f5512d93.png">

#### <a name="51"> 2.8.1.5 状态处理程序 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>


状态处理程序包含路线和事件处理，路线包括路线和路线组。事件处理用于接收各种预期外的事件发生，比如匹配不到意图时该如何响应，网络钩子请求超时该如何响应。

<img width="600" alt="截屏2022-05-26 上午10 44 50" src="https://user-images.githubusercontent.com/30898964/170443310-49574722-c87d-4a3f-9113-9571e69c8d8f.png">



##### <a name="52"> 2.8.1.5.1 路由 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>


当用户的输入匹配某个意图和/或会话状态的某个条件得以满足时，系统将调用路由。本文档所说的路由和路线可以理解为一个东西。
下图为路由设置页面：<br>
![image](https://user-images.githubusercontent.com/30898964/170441910-c253ef68-a977-43c7-9c0c-a0b5530eb647.png)


###### 路由的条件

- 当用户的输入匹配某个意图时，触发静态 fulfillment，即回复文字。
- 当用户的输入匹配某个意图时，触发启用网络钩子请求。
- 当我们设置了参数收集时，用户的输入满足了一定条件，条件检查会触发会话转换到其他页面。比如参数收集完毕后该怎么跳转，用户输入的参数小于50时该怎么跳转。
- 设置为 true 并强制页面转换的条件检查。

例1:<br>
如果您的需求是在页面添加一些意图，命中到其中一个意图后就做相关的操作，不涉及任何参数收集。你可以把多个意图加入到添加到该页面中，在添加意图到页面的时候指定接下来的操作即可。 注意当添加一个意图的时候条件意图只能选择条件“或”，即"Match at least one rule",因为在该页面意图只能被命中一个。

![image](https://user-images.githubusercontent.com/30898964/170439916-2c880ab6-aa5b-46c9-ad32-d30ad1a7da83.png)



例2:<br>

假如你需要问用户有几位用餐，然后拿到用户的人数再进行下一步操作。这时候你需要先定义要收集的参数，这里为客人数量“num”，参数类型为系统数字实体类型。然后再定义参数收集完毕后要进型的其他操作（比如页面的走向）。

![image](https://user-images.githubusercontent.com/30898964/170450003-a2b1bfbf-85bb-478a-be47-d97063fc623d.png)


###### 路由引导的页面走向

我们可以在路由页面里设置当前页面的走向。<br>

![image](https://user-images.githubusercontent.com/30898964/170453905-d9175864-770d-4c18-ba62-99b5d6ae322e.png)

    单选框“页面”的功能解释： 

    Start 当前流的开始页面
    End Flow 结束当前流
    End Session 结束对话
    Previous Page 转到上一页
    Current Page 转到当前页
    xxxx         转到某个自定义页

    单选框“流”的功能解释：
    
    Default Start Flow 转到默认开始流
    xxxx    转到某个自定义流



##### <a name="53"> 2.8.1.5.2 路由组 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>


路由组可被理解为一“打包袋”，要打包的是路由，这里举两个例子说明。<br>

例1：假设你在设计一个订票代理，这是一个多轮对话的代理，你想做到的功能是在订票流程执行的时候，用户随时问一些票务或者携带物品类的信息，bot都可以回答。我们可以把这些意图归为常见问题，将种类意图添加到路由组并设置好响应的回复话术。然候把路由组添加到开始页面。<br>

例2：如果你希望在代理和用户对话的任何时候支持用户问天气， 先把问天气的意图加入路由，然候设置好天气API网络钩子和相关回复语句。再把该路由组加入到开始页面。<br>

路由组的生效范围是什么？<br>

我们可以将路由组加入三个地方，即默认初始流的开始页面、自定义流开始页面、某个流的非初始页面。<br>
- 默认初始流的开始页面：生效范围仅是默认初始流，在默认初始流中的任何页面可被触发。
- 自定义流开始页面：生效范围是当前自定义流，当前自定义流中的任何页面都被触发。
- 非初始页面：如果路由组被添加到非初始页面，不管这个页面在默认初始流还是自定义流，生效法范围仅是当前页面。


新建路由组：<br>
有两种方法新建路由组。第一种是在代理界面左边工具条里新建，第二种是在页面里新建，在页面新路由组会新建并将该路由组添加到该页面。 如果通过第一种方法新建的话，还需要在某个页面添加这个路由组。<br>

方法1：<br>
![image](https://user-images.githubusercontent.com/30898964/170458772-76225db4-7ac0-4693-bca2-4b2d5690d5b8.png)

方法2：<br>
![image](https://user-images.githubusercontent.com/30898964/170458400-6df0cb2f-82ec-4342-bfba-e4cf24722b19.png)


##### <a name="54">  2.8.1.5.3 事件处理 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

        
事件处理程序用于处理非预期的事件，比如用户无输入、意图无匹配等，分为流级别和页面级别的处理程序，流级别的事件处理需要在流的初始页面设置，生效范围为整个流的所有页面。 页面级的时间处理程序生效范围为当前页面。 页面和流事件处理程序有优先级之分，如果某个事件被触发，在当前页中如果没设置该事件的处理程序，那么代理区寻找在流中是否设置了该事件的处理程序。<br>
每个流都有针对 no-match 和 no-input 内置事件的事件处理脚本。这些事件处理脚本会在您创建流时自动创建，并且不能删除。<br>
内置事件的列表链接： https://cloud.google.com/dialogflow/cx/docs/concept/handler?hl=zh-cn <br>

#### <a name="55">  2.8.1.6 页面、流、意图的关系</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

简单的来说，页面是包含意图的容器，流是页面的容器。页面决定了对话的走向。<br>
<br>

<img width="700" alt="截屏2022-05-26 上午10 44 57" src="https://user-images.githubusercontent.com/30898964/170404965-73bc2721-a977-49a8-9a73-045e35b1d633.png">
<img width="700" alt="截屏2022-05-26 上午10 51 49" src="https://user-images.githubusercontent.com/30898964/170405835-01618a83-1ca6-45e3-a0f8-49fc1de35176.png">


### <a name="56">2.8.2 流的操作</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

#### <a name="57">2.8.2.1 增删导入导出</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

流的操作有三种方式:</br>
1.通过API ([链接](https://cloud.google.com/dialogflow/cx/docs/concept/flow))。 </br>
2.通过客户端([链接](https://googleapis.dev/python/dialogflow-cx/latest/dialogflowcx_v3beta1/services.html#google.cloud.dialogflowcx_v3beta1.services.flows.FlowsClient))。</br>
3.通过控制台，下面展示了通过控制台创建流。</br>

创建流：</br>
![image](https://user-images.githubusercontent.com/30898964/170471522-53a137ed-af9a-48e5-aa95-0ae20eaedf53.png)

删除流：</br>

![image](https://user-images.githubusercontent.com/30898964/170471773-bcaf8866-f5af-4177-8c42-313e94313e9c.png)

导入流：</br>
![image](https://user-images.githubusercontent.com/30898964/170472211-e591c827-634f-4b6e-9d01-513cba46d922.png)

导出流：</br>
![image](https://user-images.githubusercontent.com/30898964/170472299-65897127-f030-4d64-9ea2-b8ca47cfd044.png)


建议的做法：</br>

删除某个流的时候需要注意与之关联的页面、流等信息，要确保删除后其他页面或者流不受影响，如果该流以后可能需要，可以选择导出存到本地，或者为该流保存一个版本，关于流的版本，请参照流的版本控制。</br>


## <a name="58">2.9 页面的操作 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
### <a name="59">2.9.1 设置页面初始回复 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

初始回复（entry fulfilment)和其他回复（fulfilment)，可以将初始回复理解为进入该页面的导向语句，比如顾客在上一步完成了点餐，现在进入了下订单的页面，在下订单的页面初始流中，我们可以设置这样的说法：“现在我将帮助您支付订单”。 如果设置了初始回复，那么一进入该页面就会被触发。 
![image](https://user-images.githubusercontent.com/30898964/170469944-740a43a6-cdd1-47ed-9688-dd5d3b78f29d.png)

   
### <a name="60">2.9.2 参数收集</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

参数分为：<br>
    - 意图参数
    - 表单参数
    - 会话参数

1.意图参数</br>
    
意图参数在为意图添加训练语句时，系统会自动提取并添加。 </br>
意图使用参数来提取在意图匹配时最终用户提供的数据。以下数据用于定义意图参数：
- 名称（也称为 ID 或显示名）：用于标识参数的名称。
- 实体类型：与参数关联的实体类型。
- 为列表：如果为 true，则该参数会被视为值列表。当你想通过一个意图收集多个同类型实体时使用。
- 在日志中隐去 (Redact in log)：如果设置为 true，最终用户提供的参数数据会隐去。</br>

![image](https://user-images.githubusercontent.com/30898964/151097170-0595a7ae-922e-4bf4-bf86-11e0963ead21.png)

![image](https://user-images.githubusercontent.com/30898964/151097364-6449150b-c65a-4bf3-9d5f-c17f2e2917fd.png)

    列表实体的的标记的说明：
    例子：我希望收集用户喜欢的颜色。
    在上图训练语句中，我在一条训练语句中标记了color类型的实体中的两个参数,勾选了右边的is List方框,效果是提取到了用户说的所有颜色实体。
![image](https://user-images.githubusercontent.com/30898964/151097723-2e21ce78-ef94-4871-9e68-75fd4c3aa17c.png)


    在日志中隐去的说明：
    例如，假设最终用户输入“My address is 1600 Amphitheatre Parkway”，则 address 参数会设置为“1600 Amphitheatre Parkway”。日志记录的文字将为“My address is        
    $address_redacted”。
    意图参数的引用说明：
    - $intent.params.parameter-id.original 引用实体原名
    - $intent.params.parameter-id.resolved 引用用户说出的实体名

2.表单参数</br>

- 为每个页面定义一个表单，该表单上列出应从该页面的最终用户处收集的参数，可以理解为槽位填充。</br>
- 表单参数按照参数的顺序收集。</br>。
- 当前页面可以访问其他页、流的表单参数。访问方式为$session.params.xxx, 访问当前页面的表单参数方式为$page.params.xxx</br>
- 所有的表单参数都会被写入会话参数，在会话期间收集的参数，有效范围为一轮会话，当会话结束时，所有参数会被清空。</br>
注意： 在收集参数的时候注意在先前页或者流中是否已经收集了这个参数，如果已经收集了，假设参数名为name，这时候你在当页再次收集同名参数，就不会产生一个参数收集的执行，系统认为参数已经被收集了，没必要再收集一次。如果在当前页在路由中你加入了参数收集完毕的条件路由，此时将会直接执行该路由。</br>

2.1 表单参数的状态判断：</br>
$page.params.status = "FINAL"  检查当前页面的整个表单是否已填充</br>
$page.params.parameter-id.status = "UPDATED" 检查上轮对话中是否填充了特定表单参数</br>

![image](https://user-images.githubusercontent.com/30898964/151092738-51cf7d58-8a31-44fb-a6ad-e5950ddc0a69.png)

2.2 设置表单参数：</br>
点击页面的Parameters->填写右侧的参数收集表</br>
Requried的意思是如果你设置了参数的默认值，这里如果勾选Required，就会收集该参数值，而不使用默认值。</br>
isList 和 Redact in Log 的意思请参照上面的解释。</br>

3.会话参数：</br>

当在运行时设置任何类型的参数时，该参数将被写入会话并成为会话参数。这些参数在设计时未明确定义。您可以在会话期间随时引用这些会话参数。</br>
引用会话参数</br>
会话参数引用可用于以下类型的 fulfillment 的静态响应消息中：</br>

页面条目 fulfillment</br>
路由 fulfillment</br>
事件处理程序 fulfillment</br>
表单提示 fulfillment</br>
表单重新提示 fulfillment</br>
引用方式：</br>

$session.params.parameter-id
如：$session.params.color color为收集参数的时候填写的参数名

### <a name="61">2.9.3 将意图加入到页面</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

方式一： 通过控制台</br>
先创建好意图，再到页面路由界面将意图加入。

![image](https://user-images.githubusercontent.com/30898964/170476729-e8440069-6f42-46c7-9ab4-7ec21ffd8cc0.png)

![image](https://user-images.githubusercontent.com/30898964/170476862-f0f162da-55c9-4a56-94b7-ca8cc9543f09.png)
方式二：通过python库

本次将代理、流、页面的地址写入到配置文件（ "mypackage/__init__.py"），方便管理。将流加入页面的意图的py文件为"flowManager.py"

__init__.py 

```python
from google.cloud.dialogflowcx_v3beta1.services.agents import AgentsClient
from google.api_core.client_options import ClientOptions
import sys
sys.path.append('..')


# 要操作的代理,替换为你的代理
AGENT="projects/future-area-343501/locations/asia-southeast1/agents/xxxx" 
PROJECT_ADDRESS = "projects/future-area-343501/locations/asia-southeast1/agents/"
PROJECT_ID = AgentsClient.parse_agent_path(AGENT)['project']
LOCATION_ID=AgentsClient.parse_agent_path(AGENT)['location']
AGENT_ID = AgentsClient.parse_agent_path(AGENT)['agent']
OPTIONS = ClientOptions(api_endpoint=LOCATION_ID + "-dialogflow.googleapis.com")
# 代理的ID
PARENT = "projects/" + PROJECT_ID + "/locations/" + LOCATION_ID + "/agents/" + AGENT_ID


# 初始流ID
FLOW_ID = "00000000-0000-0000-0000-000000000000"

# 流ID，FLOW_NAME为初始流ID
FLOW_NAME = "projects/" + PROJECT_ID + "/locations/" + LOCATION_ID + "/agents/" + AGENT_ID + "/flows/" + FLOW_ID
# 初始流的初始页面ID
PAGE = FLOW_NAME+ "/pages/" + "END_SESSION"

# 代理语言
LANGUAGE_CODE='en'

client_options = None
agent_components = AgentsClient.parse_agent_path(AGENT)
location_id = agent_components["location"]
if location_id != "global":
    api_endpoint = f"{location_id}-dialogflow.googleapis.com:443"
    client_options = {"api_endpoint": api_endpoint}


```

flowManager.py
这段代码的功能是将当前代理的所有意图加入默认初始流的开始页面。

```python

from google.cloud.dialogflowcx_v3beta1.services.flows import FlowsClient
from google.cloud.dialogflowcx_v3beta1.types import Flow,TransitionRoute,Fulfillment,ResponseMessage,EventHandler
from google.cloud.dialogflowcx_v3beta1.types import UpdateFlowRequest
import  intentManager
from google.cloud.dialogflowcx_v3beta1.types.intent import ListIntentsRequest
from google.cloud.dialogflowcx_v3beta1.services.intents import IntentsClient
from mypackage import *

def list_intent_id_display_name():
    '''
    :return: {'意图名'：'意图id'}
    '''
    intentClient = IntentsClient(client_options=OPTIONS)
    list_intent_request = ListIntentsRequest(parent=PARENT)
    intent_pager = intentClient.list_intents(request=list_intent_request)
    intent_lists = intent_pager.intents
    d = {}
    for intent in intent_lists:
        d[intent.display_name] = intent.name
    return d


def update_flow_all():
    # 获取当前代理的所有意图display name和意图id
    intent_map = intentManager.list_intent_id_display_name()
    intent_list = list(intent_map.keys()) # 拿到意图display name 组成的列表

    intent_list.remove('Default Negative Intent')

    flowsclient = FlowsClient(client_options=OPTIONS)

    routes_list = []

    for i,intent_name in enumerate(intent_list):

        print(f'已将{intent_name}加入初始流中')
        intent_id = intent_map[intent_name]

        # 设置fulfilment的回复文字，这里设置为意图名
        fulfillment = Fulfillment(messages=[ResponseMessage(text=ResponseMessage.Text(text=[intent_name]))])
        routes = TransitionRoute(intent = intent_id,trigger_fulfillment = fulfillment,target_page=PAGE)
        routes_list.append(routes)

    routes_list.append(TransitionRoute(intent = PROJECT_ADDRESS+AGENT_ID+"/intents/00000000-0000-0000-0000-000000000000",trigger_fulfillment = Fulfillment(messages=[ResponseMessage(text=ResponseMessage.Text(text=["default"]))]),target_page=PAGE))
    event_handlers_list = []
    # 为该页面注册事件处理程序
    event1 = EventHandler(event="sys.no-match-default", trigger_fulfillment=Fulfillment(
        messages=[ResponseMessage(text=ResponseMessage.Text(text=["I didn't get that. Can you say it again?"]))]))
    event2 = EventHandler(event="sys.no-input-default", trigger_fulfillment=Fulfillment(
        messages=[ResponseMessage(text=ResponseMessage.Text(text=["I didn't get that. Can you say it again?"]))]))
    event_handlers_list.append(event1)
    event_handlers_list.append(event2)

    #加入意图的目标流，这里为默认初始流
    flow = Flow(name=FLOW_NAME,transition_routes = routes_list,display_name="Default Start Flow",event_handlers=event_handlers_list)
    request = UpdateFlowRequest(flow=flow)
    flowsclient.update_flow(request=request)

    return


if __name__ == '__main__':
  
    update_flow_all()


```


### <a name="62">2.9.4 条件设置 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

a. 条件“或”</br>

当你设置了多个条件，当其中一个条件被满足，这个路由就会被触发。</br>
![image](https://user-images.githubusercontent.com/30898964/151087713-5aa0f331-62b2-4292-9cba-c7981acc27d0.png)

b. 条件“和”</br>

当你设置了多个条件，所有的条件都满足，这个路由才会被触发。</br>
例子：假设你在对话中收集了顾客年龄信息，你现在需要根据顾客的年龄给出不同的回复。</br>
当满足条件 20<顾客年龄<30 才被触发  </br>
![image](https://user-images.githubusercontent.com/30898964/151086934-4929d087-5224-4d89-bc19-9a8504697eb3.png)

c. 自定义表达式 Customize expression</br>

自定义表达式，请将条件判断语句写到这里。</br>
自定义表达式请参照链接： [链接](https://cloud.google.com/dialogflow/cx/docs/reference/condition)</br>
![image](https://user-images.githubusercontent.com/30898964/151086144-9dfdeaf7-a3c4-4c8d-a60c-4dc82c7a5422.png)

d. Fulfillment</br>

在这里设置代理的回复语句，如果你写了多行，将会以随机的方式选出一句作为回复语句。</br>

e.Transition</br>

当意图路由或者条件路由被触发的时候，页面的走向。</br>


### <a name="63">2.9.5 添加事件处理 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

点击页面 "Add state handler" -> 勾选Event Handler，如下图：</br>
![image](https://user-images.githubusercontent.com/30898964/151100522-a96b7600-6197-45de-aa14-63e1617a0f49.png)

![image](https://user-images.githubusercontent.com/30898964/151104323-75a365b3-c0d2-4b57-986c-417aa2f1f58a.png)

上图为设置事件处理的页面，具体说明如下：</br>
![image](https://user-images.githubusercontent.com/30898964/151104633-975c1b24-6334-4b8c-b189-c892f96b44e1.png)

### <a name="64">2.9.6 页面的执行顺序 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

当进入一个页面时候，页面的执行顺序为：</br>
Entry fulfillment -> Parameter收集（如果有）-> Routes 和 Route Groups（如果有） -> EventHandler（如果我们为当前页设置了事件处理,如果没设置默认调Dafault Start Flow的事件处理。</br>

![image](https://user-images.githubusercontent.com/30898964/151007620-1b705164-7de0-4c8b-a477-2e014571ea30.png)


### <a name="65">2.9.7 意图的操作</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>


#### <a name="66">2.9.7.1  默认的意图</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

创建代理时，系统会为您创建默认欢迎意图、和默认的负意图。这两个意图都不能被删除。 
当预料中存在大量的重复句子，导致用户输入无意义的短句误触发意图，我们把这些所谓无意义的短句加入到负意图后，这些表达就不会触发任何意图了，谷歌官方提醒我们不要把太多的短句加入负意图，因为加入大量的短句会对模型造成负面影响。 在探索Dialogflow初期，


####  <a name="67">2.9.7.2 新建意图 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

当用户输入或说出某些内容时，Dialogflow 会将该输入与意图训练短语进行比较，以找到最佳匹配。此过程称为“意图匹配”。只有与范围内的意图路由（具有意图要求的状态处理程序）关联的意图才会发生意图匹配。</br>

在搜索匹配意图时，Dialogflow 根据“意图置信度分数”（也称“置信度分数”）为潜在匹配项评分。取值范围从 0.0（完全不确定）到 1.0（完全确定）。 在对意图进行评分后，可能会出现以下两种结果：</br>

- 如果得分最高的意图的置信度得分大于或等于分类阈值设置，则系统会将其返回为匹配项。
- 如果没有任何意图满足阈值，则系统会调用无匹配事件。


我们可以在控制台，或者通过API或Dialogflow客户端库对意图增删改。详情参照链接[链接](https://cloud.google.com/dialogflow/cx/docs/concept/intent) </br>
注： 在Dialogflow cx中一个意图最多只允许2000条训练语句,一个意图只能标记<=19个实体类型。 </br>

创建意图的方式：</br>
点击manage -> create->填入意图名，收集参数（如需要）</br>

![image](https://user-images.githubusercontent.com/30898964/151105237-624db33e-8422-4a1a-bf2f-ec26b9813631.png)


批量新建意图的代码



####  <a name="68">2.9.7.3  上传训练句子到意图 </a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>


这段代码的功能是上传无需标记实体的训练句子到代理的某个意图

``` python 
#上传无需被标记的训练句子
from google.cloud.dialogflowcx_v3beta1.services.agents import AgentsClient
from google.cloud.dialogflowcx_v3beta1.types import Intent, UpdateIntentRequest,ListEntityTypesRequest
from google.cloud.dialogflowcx_v3beta1.services.intents import IntentsClient
from google.api_core.client_options import ClientOptions
from google.cloud import dialogflowcx


# 从代理处获得实体类型和id

AGENT ='projects/catering-robot/locations/us-central1/agents/ebb79c10-7630-479b-8886-e281455d7275'
SYS_NUMBER_ENTITY_TYPE_ID = "projects/-/locations/-/agents/-/entityTypes/sys.number"
LOCATION_ID = AgentsClient.parse_agent_path(AGENT)['location']
OPTIONS = ClientOptions(api_endpoint=LOCATION_ID + "-dialogflow.googleapis.com")



def get_trainingPhrase_obj_list(traning_phrase_list):
    train_list = []
    for phrase in traning_phrase_list:
        part1 = Intent.TrainingPhrase.Part()
        part1.text = phrase
        train1 = Intent.TrainingPhrase()
        # 一个训练句子由可以由很多个part组成，多个part的情况适用于需要标记实体，这里我不需要标记实体，所以列表里只有一个part
        train1.parts = [part1]
        # 训练句子在意图中出现的次数
        train1.repeat_count=1
        train_list.append(train1)
    return train_list


def uploadTraining_no_mark(intent_id,intent_display_name,traning_phrase_list_no_mark):
    intent = Intent()
    intent.name = intent_id  # 意图的id
    intent.display_name = intent_display_name  # 意图名字
    intent.training_phrases = get_trainingPhrase_obj_list(traning_phrase_list_no_mark) # 拿到句子part列表
    request = UpdateIntentRequest(intent=intent)
    intent_client = IntentsClient(client_options=OPTIONS)
    intent_client.update_intent(request=request)
    print(f'训练句子上传成功', intent_display_name, len(traning_phrase_list_no_mark))


if __name__ == '__main__':
    # 要上传的意图id
    # 请先去代理新建号空意图，然后选中，直接从导航栏处复制看可得到意图id
    # 意图id格式： intent_id = 'projects/xxxx/locations/xxxx/agents/xxxx/intents/xxxx'
    intent_id='projects/catering-robot/locations/us-central1/agents/ebb79c10-7630-479b-8886-e281455d7275/intents/5d3a490c-920a-4360-befc-9fd3dcee476d'
    # # 这是已经在代理处新建好的意图display name

    traning_phrase_list_no_mark = ['I am hungry','I am starving','I want to eat something'] # 即将被上传的训练句子
    intent_display_name='restaurant_foreign_want_to_eat'
    uploadTraining_no_mark(intent_id,intent_display_name,traning_phrase_list_no_mark)


``` 



这段代码的功能是上传需要标记实体的训练句子到代理的某个意图
```python

from google.cloud.dialogflowcx_v3beta1.services.agents import AgentsClient
from google.cloud.dialogflowcx_v3beta1.types import Intent, UpdateIntentRequest,ListEntityTypesRequest
from google.cloud.dialogflowcx_v3beta1.services.intents import IntentsClient
from google.api_core.client_options import ClientOptions
from google.cloud import dialogflowcx




# 从代理处获得实体类型和id

AGENT ='projects/catering-robot/locations/us-central1/agents/ebb79c10-7630-479b-8886-e281455d7275'
SYS_NUMBER_ENTITY_TYPE_ID = "projects/-/locations/-/agents/-/entityTypes/sys.number"
LOCATION_ID = AgentsClient.parse_agent_path(AGENT)['location']
OPTIONS = ClientOptions(api_endpoint=LOCATION_ID + "-dialogflow.googleapis.com")


# 拿到我们在谷歌自定义的所有实体类型和id
def list_entity_types():
    '''
    :param agent:
    :return: {'实体名'：'实体id路径'}
    '''
    # 系统实体类型的默认id
    entity_types_client = dialogflowcx.EntityTypesClient(client_options=OPTIONS)
    list_entity_types_request = dialogflowcx.ListEntityTypesRequest(parent=AGENT)
    resp = entity_types_client.list_entity_types(list_entity_types_request)

    entity_dict = {}

    for x in resp:
        entity_dict[x.display_name] = x.name
        # 系统实体有默认的id，我们无法直接获取，你需要再训练句子中需要标记系统实体，请在这里加入，可查阅文档找到更多系统实体类型ID
        entity_dict['sys.number'] = SYS_NUMBER_ENTITY_TYPE_ID
    return entity_dict


# 拿到句子片段列表
def get_partials(sententce_list, mark_dic):
    '''
    :param sententce_list:[i want invitation code,'show me the company list']
    :param mark_dic:{‘GRA_COMPANY’:['company','firm'],'GRA_INVITATION_CODE':["invitation code"]}
    :return:[['I', 'want', ['invitation-code']],[],...[]]
    '''
    mark_words = list(mark_dic.values())
    mark_words_1_dimension = []
    for i in range(len(mark_words)):
        for j in range(len(mark_words[i])):
            mark_words_1_dimension.append(mark_words[i][j]) #  #['unoccupied'], ['table', 'seats'], ['number'], ['delicious']]多维变1维 ['unoccupied','table', 'seats','number','delicious']

    big_list = []

    for sent in sententce_list:
        in_list = []
        for word in mark_words_1_dimension:
            word = word.replace('-', ' ')
            if word in sent:
                in_list.append(word)
        in_list = list(set(in_list))  # 在训练句子中需要被标记的单词或者短句
        for x in in_list:
            if ' ' in x:
                sent = sent.replace(x, x.replace(' ', '-'))  # ['invitation code'] => [invitation-code']
        sent_words = sent.split(" ")
        for i in range(len(sent_words)):
            for mark_word in in_list:
                mark_word = mark_word.replace(' ', '-')
                if sent_words[i] == mark_word:
                    sent_words[i] = [mark_word]
        big_list.append(sent_words)
    return big_list



# 拿到训练列表，列表元素是谷歌part类型，每个part指明了该段短句的文字和是参数id（如果需要被标记）
def get_trainingPhrase_obj_list(mark_dic,training_phrase_list):

    train_list = []
    big_list = get_partials(training_phrase_list, mark_dic)

    for sentlist in big_list:
        train1 = Intent.TrainingPhrase()
        part_list = []
        for sent in sentlist:
            if sent:
                part1 = Intent.TrainingPhrase.Part()
                part2 = Intent.TrainingPhrase.Part()
                part2.text = ' '

                if isinstance(sent, list):
                    mark_word = sent[0]
                    part1.text = mark_word.replace('-',' ')  # ['I', 'want', ['invitation-code']] =>['I', 'want', ['invitation code']]
                    part1.parameter_id = mark_word
                else:
                    sent = sent.strip()
                    part1.text = sent

                part_list.append(part1)
                part_list.append(part2)

        train1.parts = part_list
        train1.repeat_count = 1
        train_list.append(train1)
    return train_list

def get_parameterType(mark_dic):
    # 获取代理现有实体类型和id
    entity_type_dict=list_entity_types()
    # 系统实体
    parame_list = []
    for entity_type,entity_value_list in mark_dic.items():
            for entity_value in entity_value_list:
                param = Intent.Parameter()
                param.id = entity_value
                param.entity_type = entity_type_dict[entity_type]
                # 设置实体类型为非列表
                param.is_list = False
                parame_list.append(param)
    return parame_list

def uploadTraining_with_mark(intent_id,intent_display_name,traning_phrase_list,mark_dic):
    intent = Intent()
    intent.name = intent_id  # 意图的id
    intent.display_name = intent_display_name  # 意图名字
    train_phrases= get_trainingPhrase_obj_list(mark_dic,traning_phrase_list) # 拿到句子part列表
    intent.training_phrases =train_phrases
    intent.parameters = get_parameterType(mark_dic)
    request = UpdateIntentRequest(intent=intent)
    intent_client = IntentsClient(client_options=OPTIONS)
    intent_client.update_intent(request=request)
    print(f'训练句子上传成功', intent_display_name, len(train_phrases))



if __name__ == '__main__':
    # mark_dic 需要被标记的实体类型，键是实体类型，值是参数id，注意"mushroom-pizza"中间有空格
    # 这是因为参数id不能有空格，这里对于两个以上单词的实体，我们用中划线替换多个单词之间的空格
    # 但是训练句子还是原样上传，实体不含中划线
    mark_dic = {'DYN_DISH_NAME': ['burger','pizza','mushroom-pizza'],
                'sys.number': ['two']
                }

    # 这是在代理里已经新建好意图的display name
    intent_display_name = 'restaurant_english_want_to_eat'
    
    # 这里请替换为你的意图id， 意图id格式： intent_id = 'projects/xxxx/locations/xxxx/agents/xxxx/intents/xxxx'
    intent_id = 'projects/catering-robot/locations/us-central1/agents/ebb79c10-7630-479b-8886-e281455d7275/intents/5d3a490c-920a-4360-befc-9fd3dcee476d'
    traning_phrase_list_mark = ['i want to eat burger', 'i want to eat pizza', 'i want two burgers','i want to have mushroom pizza']
    uploadTraining_with_mark(intent_id, intent_display_name, traning_phrase_list_mark, mark_dic)
    

```


## <a name="69">2.11 实体</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
实体分系统实体和自定义实体，这些系统实体可以匹配许多常见数据类型。例如，有用于匹配日期、时间、颜色、电子邮件地址等类型的系统实体。自定义实体是开发者根据需求自定义的实体。</br>
### <a name="70">2.11.1 “普通实体”和会话实体</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
<p>
会话”表示 Dialogflow 代理与最终用户之间的对话。您可以在会话期间创建名为“会话实体”或“用户实体”的特殊实体。 会话实体可以扩展或替换自定义实体类型，并且仅在为其创建的会话期间存在。   
Dialogflow 将所有会话数据（包括会话实体）存储 20 分钟，也就是说从当前会话结束的那一刻开始，在20分钟内，如果没有通过同样的session id来访问该代理，该会话的实体就被被清空。
"普通实体"是相对会话而言，这里指的是长期有效的实体，比如自定义实体和代理的系统实体。
</p>

### <a name="71">2.11.2 系统实体</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
系统实体为Dialogflow系统自带的实体，我们只需要标记系统实体类型中的一个实体，dialogflow就会帮我们识别该实体类型下其他的实体。常用的系统实体包括数字、日期、 地址、城市没名等，详情参照官方文档 https://cloud.google.com/dialogflow/cx/docs/reference/
sys.number的实体地址为： "projects/-/locations/-/agents/-/entityTypes/sys.number"
sys.date-time的实体地址为： "projects/-/locations/-/agents/-/entityTypes/sys.date-time"
这些实体地址可以在Dialogflow cx官方文档中找到，当通过api上传训练句子时，如果你需要标记系统实体，就需要把系统实体加入到你的实体类型和id字典。


### <a name="72">2.11.3 创建实体类型</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

通过api创建实体类型：

```python

from google.cloud.dialogflowcx_v3.types.entity_type import EntityType
from google.cloud import dialogflowcx
from google.api_core.client_options import ClientOptions
from google.cloud.dialogflowcx_v3.types.entity_type import EntityType
from google.cloud.dialogflowcx_v3beta1.services.agents import AgentsClient
from google.cloud.dialogflowcx_v3.services.entity_types import EntityTypesClient

AGENT ='projects/catering-robot/locations/us-central1/agents/ebb79c10-7630-479b-8886-e281455d7275'
SYS_NUMBER_ENTITY_TYPE_ID = "projects/-/locations/-/agents/-/entityTypes/sys.number"
LOCATION_ID = AgentsClient.parse_agent_path(AGENT)['location']
OPTIONS = ClientOptions(api_endpoint=LOCATION_ID + "-dialogflow.googleapis.com")

def list_entity_types():
    '''
    :param agent:
    :return: {'实体名'：'实体id路径'}
    '''
    # 系统实体类型的默认id
    entity_types_client = dialogflowcx.EntityTypesClient(client_options=OPTIONS)
    list_entity_types_request = dialogflowcx.ListEntityTypesRequest(parent=AGENT)
    resp = entity_types_client.list_entity_types(list_entity_types_request)

    entity_dict = {}

    for x in resp:
        entity_dict[x.display_name] = x.name
    return entity_dict

def creat_entity(entity_name):
    # 拿到现有实体列表， 如有已经存在，就不再创建
    entity_dict = list_entity_types()
    existed_entities_types = list(entity_dict.keys())
    if entity_name in existed_entities_types:
        print('已经存在实体',entity_name)
    else:
        entityTypesClient = EntityTypesClient(client_options=OPTIONS)
        name = entity_name
        kind = EntityType.Kind.KIND_MAP
        entity_type = EntityType(display_name=name, kind=kind)
        entity = entityTypesClient.create_entity_type(parent=AGENT,entity_type=entity_type)
        print('实体创建成功',entity)


if __name__ == '__main__':

    creat_entity('DEF_TASTE')

```
### <a name="73">2.11.4 上传实体到实体类型</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>


```python

from google.cloud.dialogflowcx_v3.types.entity_type import EntityType
from google.cloud import dialogflowcx
from google.api_core.client_options import ClientOptions
from google.cloud.dialogflowcx_v3.types.entity_type import EntityType
from google.cloud.dialogflowcx_v3beta1.services.agents import AgentsClient
from google.cloud.dialogflowcx_v3.services.entity_types import EntityTypesClient

AGENT ='projects/catering-robot/locations/us-central1/agents/ebb79c10-7630-479b-8886-e281455d7275'
SYS_NUMBER_ENTITY_TYPE_ID = "projects/-/locations/-/agents/-/entityTypes/sys.number"
LOCATION_ID = AgentsClient.parse_agent_path(AGENT)['location']
OPTIONS = ClientOptions(api_endpoint=LOCATION_ID + "-dialogflow.googleapis.com")

# 传入单个实体类型和实体的字典，返回列表，列表元素为dialogflow实体对象
def make_one_type_entity(entity_dict):
    entity_names = list(set(entity_dict.keys()))

    list_of_entity_items = []
    for name in entity_names:
        if isinstance(name,float):
            name = int(name)
            name = str(name)
        entity_to_add = EntityType.Entity(value=name, synonyms=entity_dict[name])
        list_of_entity_items.append(entity_to_add)
    return  list_of_entity_items

def list_entity_types():
    '''
    :param agent:
    :return: {'实体名'：'实体id路径'}
    '''
    # 系统实体类型的默认id
    entity_types_client = dialogflowcx.EntityTypesClient(client_options=OPTIONS)
    list_entity_types_request = dialogflowcx.ListEntityTypesRequest(parent=AGENT)
    resp = entity_types_client.list_entity_types(list_entity_types_request)

    entity_dict = {}

    for x in resp:
        entity_dict[x.display_name] = x.name
    return entity_dict

# 更新实体、会直接覆盖原有实体。这里更新单个实体类型
def update_one_entity(entity_display_name,entity_dic):
    print('实体上传中...',entity_display_name)


    all_entity_from_google = list_entity_types()
    entity_item_list = make_one_type_entity(entity_dic) # 拿到实体集合

    entity_type = EntityType(name=all_entity_from_google[entity_display_name],
                                 display_name=entity_display_name,
                                 entities=entity_item_list,
                                 kind=EntityType.Kind.KIND_MAP)

    list_entity_types_request = dialogflowcx.UpdateEntityTypeRequest(entity_type = entity_type)

    # 更新实体
    entity_types_client = dialogflowcx.EntityTypesClient(client_options=OPTIONS)
    entity_types_client.update_entity_type(list_entity_types_request)
    print('实体上传成功',entity_display_name)

if __name__ == '__main__':
    # creat_entity('DEF_TASTE')

    entity_dic = {"sweet":['sweet','sugary']}
    update_one_entity('DEF_TASTE', entity_dic)

```


### <a name="74">2.11.5 系统实体表</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

```python
'''
@sys.address
@sys.airport
@sys.any
@sys.cardinal
@sys.color
@sys.currency-name
@sys.date
@sys.date-period
@sys.date-time
@sys.duration
@sys.email
@sys.flight-number
@sys.geo-capital
@sys.geo-city
@sys.geo-city-gb
@sys.geo-city-us
@sys.geo-country
@sys.geo-country-code
@sys.geo-county-gb
@sys.geo-county-us
@sys.geo-state
@sys.geo-state-gb
@sys.geo-state-us
@sys.given-name
@sys.language
@sys.last-name
@sys.location
@sys.music-artist
@sys.music-genre
@sys.number
@sys.number-integer
@sys.number-sequence
@sys.ordinal
@sys.percentage
@sys.person
@sys.phone-number
@sys.place-attraction
@sys.place-attraction-gb
@sys.place-attraction-us
@sys.street-address
@sys.temperature
@sys.time
@sys.time-period
@sys.unit-area
@sys.unit-area-name
@sys.unit-currency
@sys.unit-information
@sys.unit-information-name
@sys.unit-length
@sys.unit-length-name
@sys.unit-speed
@sys.unit-speed-name
@sys.unit-volume
@sys.unit-volume-name
@sys.unit-weight
@sys.unit-weight-name
@sys.url
@sys.zip-code
```
### <a name="75">2.11.6 日期和时间系统实体类型</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

Dialogflow 日期时间类实体大致分为五类： <br>

#### <a name="76">2.11.6.1 单个日期实体（sys.date）</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

<p>
返回结果中参数为“月、日、年”
例1：
I want to book for today. 标记today为sys.date
</p>


                "date-time": {
                  "type": "@sys.date-time",
                  "original": "today",
                  "resolved": {
                    "year": 2022,
                    "day": 24,
                    "month": 5
                  }
                }

<p>
例2：
I want to book for May 2nd
I want to book for May second 
I want to book for May 2 
标记 May 2 nd、May second、May 2为sys.date 

注：如果当前代理的时间已经过了5月2号，返回的结果为下一年的5月2号，如：
Dialogflow参数返回示例：
</p>
    


          "date": {
            "resolved": {
              "month": 5,
              "day": 2,
              "year": 2023
            }}   


<p>
当前代理时间已经超过了要用户所说的时间，但是我们想要提取今年该如何做到？
加上“今年”，即 ”I want to book for May 2 this year“. 
</p>

#### <a name="77">2.11.6.2 单个时间实体（sys.time)</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>


<p>
返回结果中参数为“时、分、秒、毫秒”
例1： I want to book at 3 pm 
Dialogflow参数返回示例：
</p>


    "time": {
                "type": "@sys.time",
                "resolved": {
                  "hours": 15,
                  "minutes": 0,
                  "nanos": 0,
                  "seconds": 0
                }
                }

<p>
可以标记下面的任意一种表达作为时间实体类型sys.time，谷歌会自动识别。 
4:30:00 PM、4 pm、4:30:00 AM、4:30 pm、4, three thirty
注：类似“3 o’clock”的特殊表达，谷歌并未针对“o’clock”做时间解析，但是，我们可以通过标记整数为实体类型“sys.time”达到效果，但存在一定问题，比如下面这三句都提取到了同样时间实体：
I want to book for 3 视情况而定
I want to book for 3 o’clock 正确
I want to book for 3 animals 不合理
</p>

#### <a name="78">2.11.6.3 日期+时间组合实体类型（sys.date-time）</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

<p>
这是日期和时间的组合实体类型，日期和时间实体可只出现一个，或两个同时出现。
先需要在训练句子中标记任何时间、日期、完整日期时间为系统实体类型"sys.date-time",这样Dialogflow就会解析用户说的日期时间，并把用户说的日期时间作为一个参数返回。
标记后，谷歌返回的实体类型都为“sys.date-time”，参数字段分为下面三种情况：

- 如果用户发言包含日期和时间，返回字段有“月、日、年、时、分、秒、毫秒”
- 如果用户发言只包含日期，返回字段有“月、日、年”
- 如果用户发言只包时间，返回字段有“时、分、秒、毫秒”

例子1：
I want to book today at 4:30 pm 
返回参数结果：
</p>

    "date-time": {
                      "type": "@sys.date-time",
                      "original": "tomorrow at 4:30 pm",
                      "resolved": {
                        "month": 5,
                        "year": 2022,
                        "seconds": 0,
                        "hours": 16,
                        "nanos": 0,
                        "minutes": 30,
                        "day": 24
                      }
                    }

<p>
例子2:
I want to book for today
返回参数结果：
</p>


            "date-time": {
                  "type": "@sys.date-time",
                  "original": "today",
                  "resolved": {
                    "year": 2022,
                    "day": 24,
                    "month": 5
                  }
                }

<p>
例子3：
I want to book for 4:30 pm
返回参数结果：
</p>

    "date-time": {
                "type": "@sys.date-time",
                "original": "4:30 pm",
                "resolved": {
                  "seconds": 0,
                  "nanos": 0,
                  "hours": 16,
                  "minutes": 30
                }}

#### <a name="79"> 2.11.6.4 日期区间实体(sys.date-period)</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

<p>
日期区间实体为两个日期的组合，建议标记“from {日期1} to {日期2} ”等英文表达为sys.date-period实体类型。返回字的实体类型为“sys.date-period”,参数里有“endDate”、“startDate”，分别为结束日期、开始日期。

例句1: 
I want to book from Monday to Friday

返回参数结果:
</p>

    "type": "@sys.date-period",
                "original": "from monday to friday",
                "resolved": {
                  "endDate": {
                    "day": 27,
                    "month": 5,
                    "year": 2022
                  },
                  "startDate": {
                    "month": 5,
                    "day": 23,
                    "year": 2022
                  }
                }
              }
            }

<p>
例句2: 
I want to book from May 24 to May 26.
返回参数结果:
</p>

          "date-period": {
            "resolved": {
              "endDate": {
                "month": 5,
                "year": 2022,
                "day": 26
              },
              "startDate": {
                "month": 5,
                "year": 2022,
                "day": 24
              }
            }}


#### <a name="80"> 2.11.6.5 时间区间实体（sys.time-period）</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

<p>
时间区间实体是两个时间实体类型的组合，比如，从下午3点到下午4点， “from 3pm to 4 pm”，只返回一个实体类型，返回参数的字段包含”startTime” 和”endTime”
例1：
I want to book from 4pm to 5pm
返回参数结果: <br>
</p>

    "time-period": {
                    "startTime": {
                      "minutes": 0,
                      "nanos": 0,
                      "hours": 16,
                      "seconds": 0
                    },
                    "endTime": {
                      "minutes": 0,
                      "hours": 17,
                      "seconds": 0,
                      "nanos": 0
                    }
                  }
                }

### <a name="81"> 2.11.7 实体的original值和resolved值（sys.time-period）</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

<p>
谷歌内置名词动词的单复数转换、动词时态的转换、动词变名词（suggest->suggestion)。 有些时候用户说出的单词不在训练语料中，但通过词型的自动转换，谷歌能找出该单词的其他词形。我们可以查看谷歌的响应字符串来判断单词的原始值（用户发言）和该单词在语料中的形式。
大概分为如下几种情况讨论： 
</p>   

 - 情况 1: 输入句子的实体值在实体类型中能找到。
    original 为用户输入的原实体值 resolved 为谷歌实体类型里的值,如下图:<br>
    例句:let me know your ability<br>
    谷歌返回结果: <br>


            "Parameters": {
            "skills": {
            "original": "ability", 
            "resolved": "ability",
            "type": "@gra_skills"
            } },


<img width="468" alt="截屏2022-05-18 下午2 47 47" src="https://user-images.githubusercontent.com/30898964/168975318-82e3f3b3-bffb-471a-905f-a15f4a081031.png">

  - 情况 2: 输入句子的实体值经过谷歌自动处理单复数后，在实体类型的实体集中能找到。

      例句:let me know your powers<br>
      截图说明：
      powers 不在实体类型 GRA_SKILLS 里，但是谷歌做了单数转换，powers 的单数 power 在实 体类型 GRA_SKILLS 里。<br>
      original 为用户输入的原实体值(powers) resolved 为谷歌实体类型里的值(power)。<br>
      original 为用户输入的原实体值 resolved 为谷歌实体类型里的值。<br>
 
 <img width="600" alt="截屏2022-05-18 下午2 49 48" src="https://user-images.githubusercontent.com/30898964/168975604-99dac0a8-95e4-4695-ab61-e2e7be8bc5dc.png">



## <a name="82">2.12 流的版本和环境</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
### <a name="83">2.12.1 概念</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
草稿：没有环境的代理为草稿，我们在控制台编辑的代理叫草稿。</br>
草稿流：草稿代理种的流为草稿流。</br>
我们可以保存一个草稿流为一个版本，这个版本的流相当于一个快照，包含了该流中原有的实体、路由、意图、网络钩子等信息。</br>
环境：</br>
我们可以新建多个环境用来做开发和测试工作等，在一个环境中我们可以根据需要选择各种版本的流，这些流构成一个代理的版本。</br>
- 每个代理的环境数量上限：20 个</br>
- 每个流的版本数量限制：20个</br>

### <a name="84">2.12.2 创建建流版本</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

 关于代理的所有操作dialogflow都提供API、客户端库、控制台三种方式，流的版本创建亦是如此,具体步骤如下：
 
![image](https://user-images.githubusercontent.com/30898964/151107494-aae0c51b-27bd-4acc-97fc-c1e8763a4304.png)

![image](https://user-images.githubusercontent.com/30898964/151107615-3199c392-6867-44b1-b90c-8dbc7352f515.png)

![image](https://user-images.githubusercontent.com/30898964/151107655-3296c338-d45b-4453-b22e-9109f9c4a33c.png)


### <a name="85">2.12.3 创建环境</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

请根据下图步骤操作：</br>
![image](https://user-images.githubusercontent.com/30898964/151107693-fe002a08-03a1-443b-a222-0413e077a1aa.png)

![image](https://user-images.githubusercontent.com/30898964/151107905-73a1a33a-9610-4e32-bf55-9fe5e785ab74.png)

拿到环境的id：</br>
单击下图右侧中间的copy图标可复制环境的完整路径。</br>
![image](https://user-images.githubusercontent.com/30898964/151108186-e1147d8f-1c63-490b-aef6-cd40c498ae19.png)


# <a name="86">3 最佳做法与避坑指南</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
## <a name="87">3.1 语料收集方法</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>
   
    语料的收集与创建需遵循一定原则，为了保证意图识别模型的收敛，需要注意以下几点:
    
    1.包含口语化说法
    Yo (hi)
    Sup (what’s up 你怎么样) Bro (brother 兄弟)
    
    2. 包含正式用语
    I require xx 我需要 xx
    I don't detest xx 我厌恶 xx I don't despise xx 我厌恶 xx
    
    3.尽量只用一句话作训练句子
    正确:I’d like the see the menu. 
    错误:I wise to see the menu, may I ?
    
    原因分析： may I 这里可以省略，因为 I wish to see the menu 已经足够表达用户意图。 
    
    
    4. 尽量用句子主干部分作为训练句子
    错误:
    Can I please see the menu.
    Is it possible for me to see the menu.
    
    正确: See the menu 
    
    原因分析：因为 is it poosible/can i please 后可跟任何从句，句子主干部分不是is it possible, 且please该作为停用词。太多大量非表达主干意思的短句会导致短句误触发意图。所以这
    里省去。
    
    5. 去掉程度词、量词、副词等非表达句子主要意思的句子成分。
    如下图红色部分的字体，我们需要把它们从训练句子中去掉。
    
    
<img width="800" alt="截屏2022-05-18 下午12 07 21" src="https://user-images.githubusercontent.com/30898964/168955241-cad7f134-6c9c-4746-a559-14ed4a0a29ca.png">

    6. 可选择的句类 
<img width="700" alt="截屏2022-05-18 下午12 09 17" src="https://user-images.githubusercontent.com/30898964/168955435-ec519acd-ec6d-4fa5-8d7c-5567f166940b.png">
    
    7. 时态与语态 
    可以根据意图需求选择训练句子的时态和语态，大多数情况用一般现在时。但对于有些些意图，如表达“已经预约”，需要使用过去式或者被动语态。
    e.g I made an appointment/my appointment was made yestoday.
    
    8. 实体的构建
    语法用途的实体需要行涵盖尽可能多的同义词，或者该实体的子类（视情况而定），最好测一下谷歌的拾音。

## <a name="88">3.2 问题发现与避免</a><a style="float:right;text-decoration:none;" href="#index">[Top]</a>

   起初我们遇到了各种意图误触发的问题，可以采用如下的解决方法来减少误触发。

    1. 意图太类似导致的误触发
    
    *原因：
    语料的质量对模型识别率产生了极大的影响，因此每个意图的语料必须有区分性，区分性意思是避免将同类意思训练句子放入多个意图，这样会导致较高的误触发。基于公司的场景，大部分的业务需求都是
    查询操作，比如查找设施、查找商铺等。这从决定了需要将大量的查询类的英语句子加入意图，最开始我们的做法是将查询类的句子放入多个意图，这导致了高误触发率。每个意图“长得像”，似乎都是查询 
    类的句子，而唯一不同的只是实体。 
    
    *解决方法：
    最后我们从行为的角度讲训练句子进行划分，依靠“行为”+“实体”来进行意图判断。常见的行为抽象如：想要某物、查询某物、喜欢某物。比如意图“查看菜单”可理解为 “查询某物”+“菜单实体”和“想要
    某物”+“菜单实体”。 那么行为意图+实体= ？业务意图，这是由产品经理决定。

    2. 谷歌内置单词自动变形导致的误触发
    
    谷歌内置了单词的自动变形导致的误触发,谷歌内置的单词变形主要分为一下几种：
    单复数变形: eggs<->egg 
    动词时态变形:booking<->book<->booked
    
    一个例子：
    我们需要做两个意图，一个是“想要订做”，另一个是“已经订座”。为了扩充句子多样化表达，我们将英语中预定的动名词、现在时和过去式、过去分词都放入了一个实体类型。
    
    问题导致：连个意图有较高的误触发。
    
    导致原因：谷歌自动做了动词的名词形式、过去式、过去分词和动词原型的自动转换。
    
    具体我们是这么做导致误触发的：
    实体类型：GRA_BOOK 
    实体集：book/booked/booking/reservation/reserve
  
    意图1：want_to_book
        训练句子： I want to book a table/book a table for me/ book a table  # 标记 book为实体类型GRA_BOOK
    意图2：already_booked
        训练句子： I booked a table/I have a table booked # 标记 booked 为实体类型GRA_BOOK
    原因分析： 因词型的自动转换，意图2中训练句子 “ I booked a table” 相当于 “ I book a table”，这根意图1中 “I book table”有较高的相似性，二两个意图
    都是关于订做的意图，所以谷歌认为这两个意图的语句都很相似，最终导致了较高的意图误触发。
   
    解决方法：
    后来在训练句子中关于单词预定的任何词形都不标记。
    

    3. 输入短语导致的触发意图
    
    单输入无意义的短语，如"can you"也会触发意图。
    
    导致原因:
    1）将 can you/could you/would you please 等无意义的停用词加入了语料
    2) 问法太类似,大部分意图都有 I would like to/I want to，导致单输入 I want to 也会触发意图。    
    
    改进方式:
    1）去掉停用词、只保留表达句子意思的主干部分。
    2）将导致误触发的短语加入“默认负意图”。
    
   <img width="329" alt="截屏2022-05-18 下午12 33 35" src="https://user-images.githubusercontent.com/30898964/168957804-01972591-02c3-44a7-8918-d344450efe85.png">


    4. 正意图的问法触发了否定意图
    
    导致原因:
    1）正负样本不均衡，正意图的训练句子太少， 例子，正意图 200 个训练句子，负意图 700 个训练句子。
    2) 有些正意图的训练语句没有与之对应的否定句。 
    
    解决方法:
    1) 正反意图语料数量上平衡。
    2) 为每一条肯定训练语句添加与之对应的否定句。

    5. 实体标记的建议做法
    
    - 避免使用虚假的实体进行实体标记（如下图），我们应该将真实的实体值加入训练句子进行标记，这样有助于降低每个意图之间的相似性，从而达到提高模型识别率。 
    - 尽量使用一个实体类型中的不同实体进行标记,如果只用其中一个实体进行标记的话，会导致提取不到该实体类型中的其他实体。

   <img width="541" alt="截屏2022-05-18 下午12 35 17" src="https://user-images.githubusercontent.com/30898964/168957963-0d7e091e-be76-49f4-9ce2-3b2f2a03e868.png">


    6. 实体提取的问题
    
    a. 实体类型提取错误
        检查路径：一个实体是否存在与两个实体类型->该实体是否存在于系统实体类型

    b. 实体type为空
        检查路径：检查一个实体是否存在于两个实体类型 -> 是否使用了正则或组合实体。
        一个实体存在于两个实体类型是是实体类型为空的主要原因，这个为谷歌后台的bug，谷歌正在尝试解决。 

    c. 带编号的实体
    
    带编号的实体通常指楼层实体、房间编号实体等含有基数词或序数词的实体。
    拿楼层实体来举例，在英语楼层表达中，一楼可以叫做 first floor, floor 1, ground floor, 1F。期初我们试过用正则实体和组合实体来表达，但导致了实体类型提取错误和实体type为空的问题。
    
    - 实体类型提取错误的原因：
    在英语中，负一楼为basement level 1，一楼为level 1， 实体之间存在嵌套关系。 负一楼在实体类型1中，一楼在实体类型2中。所有当用户问“I want to go to basement level 1”可能提取到实类 
    型2，即: level 1
    
    - 实体type为空的原因：
    在大多数情况下，实体type为空的原因是因为一个实体存在于两个实体类型中。dialogflow无法判断该实体到底属于哪个实体类型。 

    解决方法:
    对于可以穷举的实体，用枚举的方法把实体列出来，放在同一个实体类型中，这样就解决了type为空和实体类型误识别的问题。 截图为楼层实体的做法。 

<img width="972" alt="截屏2022-05-27 下午1 19 50" src="https://user-images.githubusercontent.com/30898964/170634490-91dca8fa-047b-43f1-9f10-ae06264d2d78.png">



    7. 不同渠道相同句子的测试结果差异问题
    
       我们可以通过控制台测试代理，或者通过调用谷歌API测试的代理，但有时候会产生测试结果差异的问题。我们遇到了如下几类问题：
        - 使用网页测试偶尔会出现不同电脑可能测试结果不同；
        - 在显示模型训练结束的情况下，使用接口测试前后测试提取实体的结果可能不一样，这个概率比较低，在大批量测试时可能会出现；
        - 偶尔出现更新实体并自动train成功后，新增实体不能识别；
        - 我们业务中的动态实体所在的训练语句泛化性不如静态实体;
        
        主要体现在：
        
        意图中使用同样的句式，使用稍微泛化的问法测试时，动态实体可能就提取不出来。例如对于whether_have_xxx意图中，有训练语句is there dyn_company_name和is there company，
        其中dyn_company_name和company是槽。若使用is there microsoft in building(microsoft是动态公司名称)和is there company in building时，is there microsoft in 
        building这句话就无法提取出microsoft实体，但is there company in building就可以提取出company实体。
        
        
 #### 语料利器
 
 查同义词：https://www.thesaurus.com/browse/
 句子转述：https://app.wordtune.com/ 
 



































