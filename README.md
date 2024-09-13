# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# 10969ssm家庭食谱管理系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1Sh44eDEx6?p=68)


# 绪论
## 1.1研究背景
` `随着网络不断的普及发展，家庭食谱管理系统依靠网络技术的支持得到了快速的发展，首先要从用户的实际需求出发，通过了解用户的需求开发出具有针对性的首页、个人中心、用户管理、食谱分类管理、食谱信息管理、一周食谱健康安排管理、材料信息管理、美食论坛、系统管理功能，利用目前网络给用户带来的方便快捷这一特点对系统进行调整，设计的系统让用户的使用起来更加方便，本系统的主要目的就是给用户带来快捷与高效、安全，用户只要在家中就可以进行操作。同时随着电子商务的发展家庭食谱管理系统已经受到广大用户的关注。

互联网发展至今，已经解决了很多我们解决不了的难题，使得我们工作更加便捷，提高了我们的工作效率。目前各行各业都在运用网络信息管理程序，不同的用户也都接触到信息管理，特别是在各大电商行业广泛的应运起来。通过对当前网络环境发展的分析与总结，改变传统线下家庭食谱管理系统的状态，由于用户的不断增多，使用传统的线下手工模式已经远远不能满足于用户需求了，而且越来越多的商家也在开通线上进行家庭食谱管理系统，同时商家可以利用网络对家庭食谱管理系统进行管理，设计的网站保证信息的完整安全，这样才能提高工作效率，保证系统安全正常的运行。
## 1.2研究现状
在国外他们的信息技术的发展是我国的许多倍，从1946年诞生在美国的世界上第一台计算机开始，国外的信息技术就一直在飞速地发展，一些计算机应用软件也纷纷出现，软件技术也一直在不断完善和更新。软件行业早已遍布各个地方。

在国内，我国信息技术发展起步比较晚，后期慢慢的不断地进行优化和改革，才让我们的信息技术上升到新的阶段。在现在软件开发的技术经过大量研究和生活实践基本能够达到独立开发系统应用的水平，生活中的各个行业也把软件操作替换成传统的记录模式。软件行业正是现在比较热门的行业。

社会主义进入新时代，经济实力越来越强。我们也变得越来越忙碌、对生活的要求也变得更加严格，对快速和方便的服务的需求也在逐渐增加，所以家庭食谱管理系统的开发给用户带来了足够的便利，用户通过系统来满足生活中的需求，因此，由于信息的增加，信息处理系统也随之增加，通过网络来满足现代用户需求。此次开发设计主要是实现家庭食谱管理系统 ，结合java技术以及MYSQL数据库进行设计，弥补目前在线家庭食谱管理系统中的不足，来开发出一款即方便又实用的家庭食谱管理系统 ，并且设计的程序具有界面整洁、功能强大等特性，从全局来说，家庭食谱管理系统的设计解决了信息零散，该系统实现，可以投入到真实环境中，这样不仅能解决以上提及的问题，让信息管理更准则。
## 1.3研究内容
该家庭食谱管理系统的开发和设计根据用户的实际情况出发，对系统的需求进行了详细的分析，然后进行系统的整体设计，最后通过测试使得系统设计的更加完整，可以实现系统中所有的功能，在开始编写论文之前亲自到图书馆借阅SSM 框架书籍，MYSQL数据库书籍等编程书籍，然后针对开发的家庭食谱管理系统 ，去网上查找了很多别人做好的系统，参照他们的设计结果，来对自己的系统进行更加详细的系统的设计，将系统中所有的功能结果一一列举出来，然后进行需求分析，最后对所有的功能模块进行编码，最后完成系统的整体测试，实现系统的正常运行。

这次编写的论文包含了6个部分的内容，具体内容如下：

第一部分绪论：文章主要从课题背景以及研究现状综合阐述了开发此系统的必要性。

第二部分相关技术：系统开发用到的各种技术都大致做出了简介。

第三部分系统分析：对系统的可行性分析以及对所有功能需求进行详细的分析，来查看该系统是否具有开发的可能。

第四部分系统设计：功能模块设计和数据库设计这两部分内容都有专门的表格和图片表示。

第五部分系统实现：进行系统主要功能模块的界面展示。

第六部分系统测试：测试系统的每一个功能是否能够正常运行，是否可以满足用户的需求。

# 2 系统关键技术

## 2.1 SSM框架
当今流行的“SSM组合框架”是Spring + SpringMVC + MyBatis的缩写，受到很多的追捧，“组合SSM框架”是强强联手、各司其职、协调互补的团队精神。web项目的框架，通常更简单的数据源。Spring属于一个轻量级的反转控制框架(IoC)，但它也是一个面向表面的容器(AOP)。SpringMVC常常用于控制器的分类工作模式，与模型对象分开，程序对象的作用与自动取款机进行处理。这种解耦治疗使整个系统的个性化变得更加容易。MyBatis是一个良好的可持续性框架，支持普通SQL查询，同时允许对存储过程的高级映射进行数据的优化处理。大型Java Web应用程序的由于开发成本太高，开发后难以维护和开发过程中一些难以解决的问题，而采用“SSM组合框架”，它允许建立业务层次结构，并为这个问题提供良好的解决方案。

## 2.2 JAVA技术
JAVA语言是目前软件市场上应用最广泛的语言开发程序。可以在多种平台上运用的，兼容性比较强，适应市面上大多数操作系统，不会出现乱码的现像，其扩展性和维护性都更好，具有分析问题和解决问题的能力，是面向过程的程序设计方便我们编写的代码更强壮。

JAVA相对其它语言来说，比较简单，编译起来更方便一些，安全可靠性高。不完全统计，现在全世界大约有2000多万人在使用它，JAVA既可以镶嵌使用又可以独力的使用。JAVA大致可以分成两个部分，一种部分是JAVA负责的编译，另一种是JAVA负责的运行。JAVA和C++语言很相像，但JAVA在编程时是一种以对象为导向的方式来进行编译的，使得编出来的软件可以单机使用，也可以在互联网上使用，检查出错更为方便。JAVA分布式、体系结构中立的特点也使得其存储更快，编议更简单。面向对象包括四个特点，一是封装，就是说在定义类的时候可以实现一定的功能和属性。二是抽象，属于类的一种，可以把一个具有共同属性的类封装在一个抽象里，便于简单编议。三是继承，顾名思义就是带有前者的特性。还有一个就是多态的特点，可以多种一起运用，表现了它可扩展性好。
## 2.3 MYSQL数据库
网站的开发必须配套相应数据库，数据库具有一定的组织结构，能够存放和管理数据信息，在以前数据库的功能仅仅是数据保存和管理操作，但是时代的变迁和发展，现在的数据库演变成了数据处理的方式，数据库从最开始的简单存放数据表格信息到现在的能够存放成千上万数据的大型数据库，期间还是经历了许多的改革。

本次开发的家庭食谱管理系统 使用的数据库是MYSQL数据库，该数据库运行速度快，安全性能也很高，而且对使用的平台没有任何的限制，所以被广泛应运到系统的开发中。MySQL是一个开源和多线程的关系管理数据库系统，MySQL是开放源代码的数据库，具有跨平台性，虽然功能未必强大，导致很多人都了解这个数据库的基本应用，在数据库中，总共建立了10几个表，这里面每个表都是相对应的，都各自有各自的联系，数据库意义重大，如果没有数据库的链接，就没办法运行程序，这显然可以看见数据库与程序的重要性，是紧密相连接的。
## 2.4 B/S结构
B/S（浏览器/服务器）结构是目前主流的网络化的结构模式，它能够把系统核心功能集中在服务器上面，可以帮助系统开发人员简化操作，便于维护和使用。只需要用户在用户端安装360浏览器、谷歌浏览器、QQ浏览器等当前大众浏览器，在电脑里面安装sqlserver、mysql数据库等数据库。安装好的浏览器与服务器端的数据库进行信息数据的交互。很多专门软件能够做到的事情，采用B/S结构模式也能实现，它能够结合Web浏览器技术，ActiveX技术以及多种脚本语言等技术。帮助程序开发者节约了不少开发成本。目前B/S结构成为程序开发主流结构，它最好的地方就是没有地点限制还不用专门安装软件，笔记本或者电脑能够上网就能访问系统。系统使用B/S进行开发在后期系统维护上面就会很省事，不用什么问题都在服务器上面操作，简单的用户端处理就解决部分问题，开发出来的程序跟用户交互性上面也会增强，还可以实时刷新浏览器进行程序局部的数据信息更新。

![](/md/blog.001.png)

图2-1 B/S模式三层结构图

# 3 系统分析
## 3.1 可行性分析
在系统开发之初要进行系统可行分析，这样做的目的就是使用最小成本解决最大问题，一旦程序开发满足用户需要，带来的好处也是很多的。下面我们将从技术上、操作上、经济上等方面来考虑这个系统到底值不值得开发。
### 3.1.1 技术可行性
本家庭食谱管理系统采用SSM 框架、JAVA编程语言和MYSQL数据库进行开发设计，作为计算机专业学生，在学校期间就接触到许多关于编程方面的知识，当然也包括各种编程软件，对他们的了解度也比较熟悉，所以技术开发上面还是有一定把握。
### 3.1.2经济可行性
我在设计该系统的时候主要是从节约成本出发，然后进行具体的系统的设计，在系统的设计过程中由于采用的所有工具以及技术支持全部都是免费的，因此不需要有任何的成本就可以进行该系统的设计。所用到的所有资源都是免费的，只要有网络就可以进行下载使用，不需要支付相应的费用，因此该项目在经济方面是完全可以实行的。
### 3.1.3操作可行性
本人自己就是学生，程序开发经验不足，在界面设计上面不会设计太复杂，要讲究简单好看，操作上要方便，不能让用户觉得不流畅。用户一旦进入操作界面，界面上就会有相应提示，跟着操作提示就可以找到对应的功能操作模块，对于用户来说免培训就能使用。

从上面几个部分的可行性分析得出，这次开发的家庭食谱管理系统在开发上面没有什么大问题，值得开发。
## 3.2 系统性能分析
（1）系统响应效率：页面响应时问应该在3秒以内，最长不能超过4秒，并支持至少10000人同时在线所有系统。

（2）界面简洁清晰：系统界面要求简单明了，容易操作，符合用户操作习惯。

（3）储存性高：因为家庭食谱管理系统中有很多的信息需要存储，因此对于系统的存储量有很大的要求，需要有一个强大的数据库的支持才能确保所有的信息都能安全稳定的进行存储。

（4）易学性：该系统在操作上必须简单好上手，没有很多复杂的操作，只需要简单的进行学习就能操作该系统。

（5）稳定性需求：开发的家庭食谱管理系统要求运行稳定，运行过程中无界面不清楚、字体模糊等现象。
## 3.3 系统功能分析
本家庭食谱管理系统主要包括二大功能模块，即用户功能模块和管理员功能模块。

（1）管理员模块：系统中的核心用户是管理员，管理员登录后，通过管理员功能来管理后台系统。主要功能有：首页、个人中心、用户管理、食谱分类管理、食谱信息管理、一周食谱健康安排管理、材料信息管理、美食论坛、系统管理等功能。管理员用例图如图3-1所示。

![](/md/blog.002.png)

图3-1　管理员用例图

（2）用户：首页、个人中心、我的收藏管理、美食论坛等功能，用户如图3-2所示。

![](/md/blog.003.png)

图3-2 用户用例图
## 3.4系统流程分析
### 3.4.1登录流程
登录模块主要满足管理员以及用户的权限登录，用户登录流程图如图3-3所示。

![](/md/blog.004.png)

图3-3登录流程图
### 3.4.2注册流程
未有账号的用户可进入注册界面进行注册操作，用户注册流程图如图3-4所示。

![](/md/blog.004.png)

图3-4 注册流程图
### 3.4.3添加信息流程
用户在添加信息时，信息编号自动生成，系统会对添加的信息进行验证，验证通过则添加至数据库，添加信息成功，反之添加失败。添加信息流程如图3-5所示。

![](/md/blog.005.png)

图3-5添加信息流程图
### 3.4.4删除信息流程
用户可选择要删除的信息进行信息删除操作，在删除信息时系统提示是否确定删除信息，是则删除信息成功，系统数据库将信息进行删除。删除信息流程图如图3-6所示。

![](/md/blog.006.png)

图3-6删除信息流程图

# 4　系统设计
## 4.1系统概要设计
本家庭食谱管理系统选择B/S结构(Browser/Server,浏览器/服务器结构)和基于Web服务两种模式。适合在互联网上进行操作，只要用户能连网，任何时间、任何地点都可以进行系统的操作使用。系统工作原理图如图4-1所示：

![](/md/blog.007.png)

图4-1 系统工作原理图
## 4.2系统结构设计
整个系统是由多个功能模块组合而成的，要将所有的功能模块都一一列举出来，然后进行逐个的功能设计，使得每一个模块都有相对应的功能设计，然后进行系统整体的设计。

本家庭食谱管理系统结构图如图4-2所示。

![](/md/blog.008.png)

图4-2 系统功能结构图
## 4.3系统顺序图设计
### 4.3.1登录模块顺序图
登录模块主要满足了管理员以及用户的权限登录，登录模块顺序图如图4-3所示。

![](/md/blog.009.png)

图4-3 登录顺序图
### 4.3.2添加信息模块顺序图
管理员以及用户登录后均可进行添加信息操作，添加信息模块顺序图如图4-4所示。

![](/md/blog.010.png)

图4-4 添加信息顺序图
## 4.4数据库设计
一个好的数据库可以关系到程序开发的优劣，数据库设计离不开表结构的设计，还有表与表之间的联系，以及系统开发需要设计的数据表内容等信息。在进行数据库设计期间，要结合实际情况来对数据库进行针对性的开发设计[12]。
### 4.4.1数据库E-R图设计
本家庭食谱管理系统采用的是MYSQL数据库，数据存储快，因为家庭食谱管理系统 ，主要的就是对信息的管理，信息内容比较多，这就需要好好的设计一个好的数据库，分类要清楚，不能添加信息的时候，造成信息太过混乱，设计好的数据库首先就需要先把各个实体之间的关系表达明确，系统的E-R图如下图所示：

1、用户管理实体图如图4-5所示：
######### ![](/md/blog.011.png)
图4-5 用户管理实体图

2、食谱信息管理实体图如图4-6所示：

![](/md/blog.012.png)

图4-6 食谱信息管理实体图

3、一周食谱健康安排管理实体图如图4-7所示：

![](/md/blog.013.png)

`  `图4-7 一周食谱健康安排管理实体图
### 4.4.2数据库表设计
将数据库概念设计的E-R图转换为关系数据库。在关系数据库中，数据关系由数据表组成，但是表的结构表现在表的字段上。

表名：cailiaoxinxi

功能：材料信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|cailiaomingcheng|varchar|200|材料名称|||
|tupian|varchar|200|图片||shangpinxinxi|
|shiwugongxiao|bigint||食物功效|||
|shiwudapei|bigint||食物搭配|||
|shiwujinji|varchar|200|食物禁忌|||




表名：shipufenlei

功能：食谱分类

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shipufenlei|varchar|200|食谱分类|||




表名：shipuxinxi

功能：食谱信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shipumingcheng|bigint||食谱名称|||
|tupian|bigint||图片|||
|shipufenlei|longtext|4294967295|食谱分类|||
|pengrenfangshi|longtext|4294967295|烹饪方式|||
|zuofa|longtext|4294967295|做法|||
|gongxiao|longtext|4294967295|功效|||
|shizhang|longtext|4294967295|时长|||
|yuancailiao|longtext|4294967295|原材料|||
|dapeijinji|longtext|4294967295|搭配禁忌|||




表名：yizhoushipujiankanganpai

功能：一周食谱健康安排

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|biaotimingcheng|varchar|100|标题名称|||
|tupian|varchar|100|图片|||
|xingqiyi|varchar|100|星期一|||
|xingqier|varchar|100|星期二|||
|xingqisan|varchar|100|星期三|||
|xingqisi|varchar|100|星期四|||
|xingqiwu|varchar|100|星期五|||
|xingqiliu|varchar|100|星期六|||
|xingqitian|varchar|100|星期天|||




表名：yonghu

功能：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yonghuhao|varchar|200|用户号|||
|mima|varchar|200|密码|||
|yonghuxingming|varchar|200|用户姓名|||
|touxiang|varchar|200|头像|||
|xingbie|int||性别|||
|shoujihaoma|varchar|200|手机号码|||
|youxiang|varchar|200|邮箱|||






第5章 系统详细设计

5.1前台首页功能模块

家庭食谱管理系统 ，在前台首页可以查看首页、食谱信息、一周食谱健康安排、材料信息、美食论坛、公告信息、个人中心、后台管理等内容，如图5-1所示。

![](/md/blog.014.png)

图5-1前台首页功能界面图



`    `登录，在用户页面可以填写用户名、密码、信息进行登录，如图5-2所示。


![](/md/blog.015.png)

图5-2用户登录界面图

食谱信息，在食谱信息页面通过填写食谱名称、图片、食谱分类、烹饪方式、做法、功效、时长、原材料、搭配禁忌、点击次数等信息进行添加我的收藏。如图5-3所示。在材料信息页面通过填写食物功效、食物搭配、食物禁忌等信息进行操作，如图5-4所示。

![](/md/blog.016.png)

图5-3食谱信息界面图

![](/md/blog.017.png)

图5-4材料信息界面图

5.2管理员功能模块

管理员登录，通过填写注册时输入的用户名、密码、角色进行登录，如图5-5所示。

![](/md/blog.018.png)

图5-5管理员登录界面图




管理员登录进入家庭食谱管理系统可以查看首页、个人中心、用户管理、食谱分类管理、食谱信息管理、一周食谱健康安排管理、材料信息管理、美食论坛、系统管理等信息。

用户管理，在用户管理页面中可以通过填写用户名、密码、用户姓名、头像、性别、手机号码、邮箱等内容进行修改、删除，如图5-6所示。还可以根据需要对食谱分类管理进行详情，修改或删除等详细操作，如图5-7所示。

![](/md/blog.019.png)

图5-6用户管理界面图

![](/md/blog.020.png)

图5-7食谱分类管理界面图

一周食谱健康安排管理，在一周食谱健康安排管理页面中可以填写标题名称、图片、星期一、星期二、星期三、星期四、星期五、星期六、星期天等信息，并可根据需要对已有一周食谱健康安排管理进行修改或删除等操作，如图5-8所示。

![](/md/blog.021.png)

图5-8一周食谱健康安排管理界面图

美食论坛管理，在美食论坛管理页面中可以填写帖子标题、用户名、状态等信息，并可根据需要对已有美食论坛管理进行详情、修改或删除等操作，如图5-9所示。

![](/md/blog.022.png)

图5-9美食论坛管理界面图

轮播图；该页面为轮播图管理界面。管理员可以在此页面进行首页轮播图的管理，通过新建操作可在轮播图中加入新的图片，还可以对以上传的图片进行修改操作，以及图片的删除操作如图5-10所示。

![](/md/blog.023.png)

图5-10轮播图界面图

公告信息，在公告信息页面中可以查看标题 简介 图片等内容，并且根据需要进行详情，修改或删除等详细操作，如图5-11所示。

![](/md/blog.024.png)

图5-11公告信息界面图

5.3用户功能模块

用户登录进入家庭食谱管理系统可以查看首页、个人中心、我的收藏管理、美食论坛等内容。我的收藏管理，在我的收藏管理页面中通过填写收藏名称、收藏图片等信息，还可以根据需要对我的收藏管理进行修改、删除如图5-12所示。

![](/md/blog.025.png)

图5-12我的收藏管理界面图


# 










