# CMS的开发

内容管理系统是一个很泛的概念：从商业门户网站的新闻系统到个人的Weblog都可以称作发布系统。

框架型：本身不包含任何应用实现，只是提供了底层框架，具体应用需要一定的二次开发，比如Cocoon，Vignette；

应用型：本身是一个面向具体类型的应用实现，已经包含了新闻/评论管理，投票，论坛，WIKI等一些子系统。比如：postNuke xoops等；

内容管理系统可建设具有独特个性的网站.“网站模板与网站程序完全分离”和“模板方案”是目前CMS的主流设计特点，让网站的模板设计与程序彻底分开。设计者可以将每个频道、栏目甚至内容页面运用不同的模板，随时能编辑、修改网站界面，更能一键切换预设的模板方案，更换网站界面。

内容管理系统后台管理实现方便、易用、人性化的操作方式，创新采用书签式管理的Web界面，切换方便，节省使用者和浏览者的时间。所见即所得的编辑功能，可以在内容管理系统里直接进行文字的排版处理，还可以在线对图片进行简单处理。系统支持插入Flash、音频、视频、超链接、特殊字符等等。

内容管理系统使用基于角色的用户管理，通过添加不同权限的用户，可以将一个网站的管理权限分配给不同的用户。通过建立具有不同管理权限的用户组，可以将用户分成多种级别：超级管理员、栏目管理员、文档录入员、审核员等 一份内容从最初录入到最后发布到网站上，中间可以经过编辑初审、修改，管理员审批等，保证发布内容的质量。

我们认为内容管理系统是一种位于WEB前端（Web 服务器）和后端办公系统或流程（内容创作、编辑）之间的软件系统。内容管理解决方案重点解决各种非结构化或半结构化的数字资源的采集、管理、利用、传递和增值，并能有机集成到结构化数据的商业智能环境中，如OA,CRM等。内容的创作人员、编辑人员、发布人员使用内容管理系统来提交、修改、审批、发布内容。这里指的"内容"可能包括文件、表格、图片、数据库中的数据甚至视频等一切你想要发布到 Internet、Intranet以及Extranet网站的信息。

项目规范 ： 项目开始时，首先，搭建一致的开发环境 如本次：Node.js。其次，搭建最小的架构，甚至于不使用数据库，然后在mydata文件中编写html代码，最后我学习了简单的使用数据库的简单CMS，应用前端页面，也会使用UI框架。然后使用TextLight的轻量级CMS，它可以作为框架进行其他功能的开发。包括数据库和编码的规范（这个也可以在数据库设计时做数据库规范，编码时在做编码规范）。

在最后，我认为cms也就是内容管理系统，要看它的易用性，灵活性，可扩展性。CMS的使用是一个系统化的过程，由于其强大的功能，我们应该学习基本的服务器与数据库知识，学会产品手册和建立自己的知识库。


