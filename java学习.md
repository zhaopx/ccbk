## Java学习 ##

### 初步了解 ###

1. 使用工具:Eclipse
2. java首先要下载一个JDK，配置环境变量，这个网上一搜就很多(http://developer.51cto.com/art/200907/134780.htm)。Myeclipse和Tomcat的集成、项目的发布网(http://www.blogjava.net/Harriet/archive/2007/11/23/162565.html)上都有相应的步骤的。
资料很多择其中前一点点看看就好了，其余的用着用着就熟悉了。可以先分别看看struts，然后spring然后hibernate，然后看他们的集成。写两个DEMO就明白了，用熟悉了再去整那些原理
3. JAVA开发经常会用到一些外部的jar包，这个和.NET里面的DLL一样的东西，在web工程里面，引用jar包通常就是拷贝到WebRoot\WEB-INF\lib目录下面就可以了。如果不行就要添加到工程引用中去：工程->鼠标右键->Properties->Java Build Path->Libraies->Add JARS选择要引用的jar包 OK即可。在JAVA工程中，src是源代码目录,WebRoot是页面目录，lib是jar包目录
>
-  先说说Struts2框架，常用在展示层，前台页面展示与控制页面跳转。建立一个JavaWed工程，都会有一个web.xml文件，是整个工程的主配置文件。其它框架的集成首先是在这个配置文件里面进行的。Struts也有一个主配置文件struts.xml，工程中所有配置的Action都是在这个配置文件中配置的。Action是Struts的核心，其实就是控制页面跳转用的，每个页面和后台的数据交互或者跳转到另外的页面都通过action进行。Struts的具体使用看看相关的文档，自己写个登录的demo就明白了。
- Hibernate 用做数据库的访问，也就是所谓的持久层，用法比直接写sql访问稍微简单，可以简单的看看hibernate的使用，先别研究的那么深。
- Spring 通常用作控制层，在系统架构设计上使用的比较多，核心思想是Ioc和AOP，实际代码层面还麻烦一些，其实就是采用接口编程方式，将直接采用new实例化对象变成set、get注入的方式。
哦，忘记了，

### 纷享使用的架构体系 ###

1. **找比较了解架构的人帮着统一讲一遍**

### 线上资料 ###

1. [8张图理解Java](http://www.importnew.com/11725.html "8张图理解Java")

## MySQL学习 ##

### 线上资料 ###

1. [mysql数据库开发常见问题及优化](http://www.importnew.com/23232.html "mysql数据库开发常见问题及优化")

## 视频学习笔记 ##

1. 基础01
	1. JDK（java工具开发包）包含JRE（java允许环境），JRE包含JVM（java虚拟机）
	2. 系统变量CLASSPATH配置的时候前面需要加.;
2. 基础02
3. 基础03
4. 手机视频下载到09
	 






