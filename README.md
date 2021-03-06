# CI-automation-development-test-release-integration-platform
CI自动化开发测试发布一体化平台搭建

##一、平台介绍
本平台将使用 Phabricator + Xmapp + Git + Gradle + Jenkins 来实现搭建.

###1、Phabricator的详细介绍
在代码审查(Code Review)方面，Facebook做了一个可视化的工具，现已开源，叫Phabricator;工程师可以在页面上非常方便的针对每一段(单行或者多行)代码进行交互讨论;负责审查的工程师可以接受代码改变，可以提出疑问要求原作者继续修改，可以提出自己不适合以推出该代码审查，等等。只有代码被明确接受之后才能被工程师提交到服务器端的代码库，这一点集成到提交工具中强制执行。基本理念就是凡是被很多人不断重复的好的习惯，要将其自动化，绑定到工具之中。以“Don’t make me think”的方式来推广好的practice。目前只支持在linux和mac上安装。

###2、Xmapp
XAMPP是完全免费且易于安装的Apache发行版，其中包含MySQL、PHP和Perl。XAMPP开放源码包的设置让安装和使用出奇容易。它也提供Tomcat等其他服务。

###3、Git
Git是一个开源的分布式版本控制系统，用以有效、高速的处理从很小到非常大的项目版本管理.
    
Git 是 Linus Torvalds 为了帮助管理 Linux 内核开发而开发的一个开放源码的版本控制软件。
    
Torvalds 开始着手开发 Git 是为了作为一种过渡方案来替代 BitKeeper，后者之前一直是 Linux 内核开发人员在全球使用的主要源代码工具。开放源码社区中的有些人觉得 BitKeeper 的许可证并不适合开放源码社区的工作，因此 Torvalds 决定着手研究许可证更为灵活的版本控制系统。尽管最初 Git 的开发是为了辅助 Linux 内核开发的过程，但是我们已经发现在很多其他自由软件项目中也使用了 Git。例如 最近就迁移到 Git 上来了，很多 Freedesktop 的项目也迁移到了 Git 上。

###4、Gradle
Gradle是一个基于Apache Ant和Apache Maven概念的项目自动化建构工具。它使用一种基于Groovy的特定领域语言(DSL)来声明项目设置，抛弃了基于XML的各种繁琐配置。

面向Java应用为主。当前其支持的语言限于Java、Groovy和Scala，计划未来将支持更多的语言。

Gradle是一个基于JVM的构建工具，是一款通用灵活的构建工具，支持maven， Ivy仓库，支持传递性依赖管理，而不需要远程仓库或者是pom.xml和ivy.xml配置文件，基于Groovy，build脚本使用Groovy编写。

###5、Jenkins
Jenkins是基于Java开发的一种持续集成工具，用于监控持续重复的工作。

功能包括：
1、持续的软件版本发布/测试项目。
2、监控外部调用执行的工作。
