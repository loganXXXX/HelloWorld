logan

<div align=center><img width="350" height="350" src="http://github.global.ssl.fastly.net/images/modules/logos_page/GitHub-Mark.png"/></div>


hello world！
[进阶实战项目，点击这里!](https://github.com/MoonTreee/lucene-trey)
=============


*****再次感谢各位的`star`！***** 


无硅步，不能致远。有什么问题欢迎留言交流！

`一：MVCStudy`
----------

这是一个基于MVC结构开发的小demo，无需引入任何jar包，纯手工开发，方便理解MVC工作模式。

主要功能：用户在页面上输入两个数字，程序进行计算并将结果返回给用户。


`二：SSHPlay`
--------
这是一个SSH框架的整合练习，尚处在开发阶段

数据库：MySql

需求：

1：实现商品信息的增，删，更新操作。

2：已完成功能，在粗陋的界面情况下完成了商品信息的保存和删除。
使用方法：

fork或者直接下载项目到本地，推荐用IDEA打开，修改一下jdbc.properties文件中的相应的属性即可（用户名以及密码）


`三：StrutsStudy`
-----------

Struts框架单独拿出来的练习。


`四：SSH2`:clock12: :clock3:	:clock6:	
--------

新加入了一个基于SS2H框架形成的员工管理信息系统。通过学习，可以较好的理解数据从前端到后台的流程。
请你完成：将 部门表 和 员工信息表 联系起来，实现（诸如 某部门解散，该部门所有员工就被辞退）的过程。


<font color=#0099ff>注意</font>：如果报错“Invocation of init method failed; nested exception is java.lang.NoSuchMethodError”</p>
是因为在Spring AOP Libraries包中有个开头为asm的jar包，而Hibernate3.2 Core Libraries包里有个asm.jar，问题就在这里了，可能会遇到版本不同的时候控制台报出没有此方法的异常。试着将asm的jar直接移除即可。</p>




## SSH2 Update Info 
-----------



:squirrel: 0303：增加员工管理模块

:squirrel: 030600: 实现员工表和部门表的一对多映射

:squirrel: 030601: 完善员工管理模块（并与部门信息关联)

:squirrel: 0311: 理解spring的aop机制，以配置方式利用aop进行用户身份验证

:squirrel: 0323: 优化角色管理，将“系统管理员”的角色同Employee角色进行区分，重构登录模块，并继续以配置方式进行aop的用户身份认证

##  _尝试基于注解的aop，结果几次都失败了，等有时间再来找找原因。聪明的你如果成功了，欢迎交流!_
