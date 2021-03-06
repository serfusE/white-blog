Title: Pelican 自定义模版，Spring Boot, Maven…
Date: 2018-10-08

周一，被专业课老师下达任务，提前学习数据库 Procedure，依然按照三进程任务分类，替代掉第三进程算法，也就是该进程队列：1）Procedure；2）算法课程；3）Design+Code 课程。不过实际上本周的事件都仅仅安排到了完成前两件线程而已，后面一周又有其他课程的任务，同时博客也需要更新了……给我两倍的周末吧~

## Pelican 博客
渲染主页的过程中意识到应该至少先把 [Template Designer Documentation](http://jinja.pocoo.org/docs/2.10/templates/) 泛读过一遍。用比较快的速度读过之后，立即完成主页的渲染，然后 Sketch 制作出剩下的页面，HTML 和 CSS 动画交给小伙伴写，然后再 Jinja 渲染（越到后面会越简单）。能想到可能会比较麻烦的是 MarkDown 的样式渲染。这些基本的做完之后就可以考虑定制 RSS、语法高亮等功能了。

下周结束前，渲染完 2~3 个页面。

至于字体，暂时先不考虑 webfont 好了，就为各个操作系统做一个 fall back 列表吧。

笔记同步更新至：https://github.com/serfusE/dev-blog

## Start with Maven
Google 发现关于 Java SSM 框架的教程资源少的可怜，所以需要自己花点心思**构建知识体系**了。这是一项考验，面面俱到的同时又要确保整体的进度。

完善技术栈第一步，先从之前忽视了的构建工具 Maven 开始，虽说之前一直有用，但实际上对它的实现逻辑并不了解，这次就来好好看看。（笔记同步更新）

下一周，首先不要在 Maven 上耽误太久，然后按照 Spring 官方的建议，直接从 Spring Boot 开始是好的（本周已经快完成了），最后再争取一下控制层入个门。

预计月底的时候能完成构建一个 Spring 项目要用的的基本知识，包括快速开发 Spring Boot、控制层 Spring MVC、渲染引擎 Thymeleaf、数据层 MyBatis 等。