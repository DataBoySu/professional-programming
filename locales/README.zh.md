<!--START_SECTION:navbar-->
<div align="center">
  <a href="../README.md">🇺🇸 English</a> | <a href="README.zh.md">🇨🇳 中文</a>
</div>
<!--END_SECTION:navbar-->

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

## 目录

- [Professional Programming - about this list](#professional-programming---about-this-list)
  - [Principles](#principles)
  - [Contributing to this list](#contributing-to-this-list)
  - [Must-read books](#must-read-books)
  - [Must-read articles](#must-read-articles)
  - [Other general material and list of resources](#other-general-material-and-list-of-resources)
    - [Other lists](#other-lists)
    - [Books](#books)
    - [Articles](#articles)
    - [Axioms](#axioms)
    - [Courses](#courses)
  - [Topics](#topics)
    - [Accounting](#accounting)
    - [Algorithm and data structures](#algorithm-and-data-structures)
    - [API design & development](#api-design--development)
    - [Attitude, habits, mindset](#attitude-habits-mindset)
      - [Procrastination](#procrastination)
    - [Authentication/authorization](#authenticationauthorization)
    - [Automation](#automation)
    - [Best practices](#best-practices)
    - [Beyond software engineering & random](#beyond-software-engineering--random)
    - [Biases](#biases)
    - [Business](#business)
    - [Buy vs. Build](#buy-vs-build)
    - [Cache](#cache)
    - [Career growth](#career-growth)
      - [Choosing your next/first opportunity](#choosing-your-nextfirst-opportunity)
      - [Getting to Staff Eng](#getting-to-staff-eng)
    - [Characters sets](#characters-sets)
    - [Chess](#chess)
    - [Clouds](#clouds)
    - [Code reviews](#code-reviews)
    - [Coding & code quality](#coding--code-quality)
    - [Communication](#communication)
    - [Compilers](#compilers)
    - [Configuration](#configuration)
    - [Continuous Integration (CI)](#continuous-integration-ci)
    - [Data analysis & data science](#data-analysis--data-science)
    - [Databases](#databases)
      - [NoSQL](#nosql)
      - [Postgres](#postgres)
    - [Data formats](#data-formats)
    - [Data science/data engineering](#data-sciencedata-engineering)
    - [Debugging](#debugging)
    - [Design (visual, UX, UI, typography)](#design-visual-ux-ui-typography)
    - [Design (OO modeling, architecture, patterns, anti-patterns, etc.)](#design-oo-modeling-architecture-patterns-anti-patterns-etc)
      - [Design: database schema](#design-database-schema)
      - [Design: patterns](#design-patterns)
      - [Design: simplicity](#design-simplicity)
    - [Dev environment & tools](#dev-environment--tools)
    - [Docker](#docker)
    - [Documentation](#documentation)
    - [Dotfiles](#dotfiles)
    - [Editors & IDE](#editors--ide)
      - [Vim](#vim)
    - [Email](#email)
    - [Engineering management](#engineering-management)
    - [Exercises](#exercises)
    - [Experimentation](#experimentation)
    - [Functional programming (FP)](#functional-programming-fp)
    - [Games development](#games-development)
    - [Graphics](#graphics)
    - [Hardware](#hardware)
    - [HTTP](#http)
    - [Humor](#humor)
    - [Incident response (oncall, alerting, outages, firefighting, postmortem)](#incident-response-oncall-alerting-outages-firefighting-postmortem)
      - [Postmortem](#postmortem)
    - [Internet](#internet)
    - [Interviewing](#interviewing)
    - [Kubernetes](#kubernetes)
    - [Large Language Model (LLM)](#large-language-model-llm)
    - [Learning & memorizing](#learning--memorizing)
    - [Licenses (legal)](#licenses-legal)
    - [Linux (system management)](#linux-system-management)
    - [Low-code/no-code](#low-codeno-code)
    - [Low-level, assembly](#low-level-assembly)
    - [Machine learning/AI](#machine-learningai)
    - [Math](#math)
    - [Marketing](#marketing)
    - [Network](#network)
    - [Observability (monitoring, logging, exception handling)](#observability-monitoring-logging-exception-handling)
      - [Logging](#logging)
      - [Error/exception handling](#errorexception-handling)
      - [Metrics](#metrics)
      - [Monitoring](#monitoring)
    - [Open source](#open-source)
    - [Operating system (OS)](#operating-system-os)
    - [Over-engineering](#over-engineering)
    - [Performance](#performance)
    - [Personal knowledge management (PKM)](#personal-knowledge-management-pkm)
    - [Personal productivity](#personal-productivity)
    - [Perspective](#perspective)
    - [Privacy](#privacy)
    - [Problem solving](#problem-solving)
    - [Product management for software engineers](#product-management-for-software-engineers)
    - [Project management](#project-management)
    - [Programming languages](#programming-languages)
      - [Python](#python)
      - [JavaScript](#javascript)
      - [Garbage collection](#garbage-collection)
    - [Programming paradigm](#programming-paradigm)
    - [Public speaking (presenting)](#public-speaking-presenting)
    - [Reading](#reading)
    - [Refactoring](#refactoring)
    - [Regex](#regex)
    - [Releasing & deploying](#releasing--deploying)
      - [Versioning](#versioning)
      - [Checklists](#checklists)
      - [Feature flags](#feature-flags)
      - [Testing in production](#testing-in-production)
    - [Reliability](#reliability)
      - [Integration patterns (dependency management)](#integration-patterns-dependency-management)
      - [Resiliency](#resiliency)
    - [Search](#search)
    - [Security](#security)
    - [Research papers](#research-papers)
    - [Shell (command line)](#shell-command-line)
    - [SQL](#sql)
    - [State](#state)
    - [System administration](#system-administration)
    - [System architecture](#system-architecture)
      - [Architecture patterns](#architecture-patterns)
      - [Microservices/splitting a monolith](#microservicessplitting-a-monolith)
    - [Scalability](#scalability)
    - [Site Reliability Engineering (SRE)](#site-reliability-engineering-sre)
    - [Technical debt](#technical-debt)
    - [Testing](#testing)
    - [Tools](#tools)
    - [Type system](#type-system)
    - [Typography](#typography)
    - [Version control (Git)](#version-control-git)
    - [Work ethics, productivity & work/life balance](#work-ethics-productivity--worklife-balance)
    - [Web development](#web-development)
    - [Writing (communication, blogging)](#writing-communication-blogging)
  - [Resources & inspiration for presentations](#resources--inspiration-for-presentations)
  - [Keeping up-to-date](#keeping-up-to-date)
  - [Concepts](#concepts)
  - [My other lists](#my-other-lists)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# 专业编程 - 关于这份列表

> 给我六个小时砍倒一棵树，我会用前四个小时磨斧头。(亚伯拉罕·林肯)

为程序员提供的全栈资源集合。

本页的目标是让你成为一名更熟练的开发者。你将只找到那些真正令人着迷的资源，或者已成为不朽经典的内容。

## 原则

- 本页并非旨在全面。我试图保持简洁，避免过于繁重。
- 所选文章具有主观性。
- 我不一定同意或支持那些资源中所写的每一句话。同样适用于作者：我不支持他们所说的一切，以及他们将来会说的任何内容。

项目：

- 🧰 : 资源列表
- 📖 : 书籍
- 🎞 : 视频/电影片段/电影/演讲
- 🏙 : 幻灯片/演示文稿
- ⭐️ : 必读
- 📃 : 论文

## 贡献给这份列表

欢迎打开 PR 贡献！

我不会添加所有内容：如上所述，我试图保持列表简洁。

## 必读书籍

我发现这些书非常鼓舞人心：

- 📖 [The Pragmatic Programmer: From Journeyman to Master](https://pragprog.com/titles/tpp20/): 实用性最强、最鼓舞人心和最有用的编程书籍之一。
- 📖 [Code Complete: A Practical Handbook of Software Construction](http://www.amazon.com/Code-Complete-Practical-Handbook-Construction/dp/0735619670): 《The Pragmatic Programmer》的很好补充，为你提供谈论代码所需的框架。
- 📖 [Release It!](https://smile.amazon.com/Release-Design-Deploy-Production-Ready-Software/dp/1680502395): 这本书超越了代码，为你提供构建生产就绪软件的最佳实践。它将为你提供大约3年的真实世界经验。
- 📖 [Scalability Rules: 50 Principles for Scaling Web Sites](https://smile.amazon.com/Scalability-Rules-Principles-Scaling-Sites/dp/013443160X)
- 📖 [The Linux Programming Interface: A Linux and UNIX System Programming Handbook](http://www.amazon.com/The-Linux-Programming-Interface-Handbook/dp/1593272200): 除了教你几乎所有关于Linux的知识外，这本书还将给你关于软件如何演进的见解，以及拥有简单而优雅接口的价值。
- 📖 [Structure and interpretation of Computer Programs](https://web.mit.edu/6.001/6.037/sicp.pdf) (免费): 计算机科学领域最有影响力的教科书之一（在MIT编写和使用），SICP在计算机科学教育中具有重要影响。[Byte](../<https://en.wikipedia.org/wiki/Byte_(magazine)>) 推荐 SICP "给那些真正对职业感兴趣的程序员"。

有一些免费书籍可用，包括：

- 📖 [Professional software development](http://mixmastamyk.bitbucket.io/pro_soft_dev/): 非常完整，是本页的良好补充。免费章节主要集中在软件开发过程：设计、测试、编写代码等，而不是技术本身。
- 🧰 [vhf/free-programming-books](https://github.com/vhf/free-programming-books)
- 🧰 [EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books/tree/main/books)

## 必读文章

- [给新软件工程师的实用建议](http://product.hubspot.com/blog/practical-advice-for-new-software-engineers)
- [关于成为高级工程师](http://www.kitchensoap.com/2012/10/25/on-being-a-senior-engineer/)
- [软件开发中的经验教训](http://henrikwarne.com/2015/04/16/lessons-learned-in-software-development/): 这是一篇能将多年辛苦学到的经验浓缩在一篇短文中的文章。必读。
- [我从艰难中学到的东西](https://blog.juliobiason.me/thoughts/things-i-learnt-the-hard-way/)
  - 先写规范，再写代码
  - 测试能带来更好的 API
  - 未来思考就是未来浪费
  - 文档是你写给未来自己的情书
  - 有时候，让应用程序崩溃比什么都不做更好
  - 理解并远离cargo cult
  - “适合的工具做适合的事”只是在推动一个议程
  - 学习函数式编程的基础
  - 日期始终使用时区
  - 一直使用UTF-8
  - 创建库
  - 学会监控
  - 明确优于隐含
  - 公司寻找的是专家，但保留的是通才
  - 处理用户数据最安全的方式是不收集它
  - 该停止的时候，就是该停止的时候
  - 你对代码的使用负有责任
  - 当事情还没完成时，不要说“完成了”
  - 注意别人对你的反应
  - 警惕微小的侮辱
  - 保持一个“我不知道的事情”的列表
- [你是一个好程序员的迹象](https://skatgame.net/mburo//courses/350/signs-that-you-re-a-good-programmer.html)（这里并非所有内容都很好 - 有些观点可能适得其反）
  - 先尝试实验的本能
  - 对代码和设计的情感疏离
  - 渴望修复未出问题的东西
  - 对难以理解的事物着迷
  - 有教学的冲动
  - 不可腐蚀的耐心
  - 对完美的破坏性追求
  - 对平台的百科全书式掌握
  - 用代码思考
  - 在罗马，做罗马人做的事
  - 创建自己的工具
  - 对等级制度漠不关心
  - 对失败感到兴奋
  - 对环境漠不关心
  - 用冲动代替承诺
  - 被经历驱动
- [我作为初级开发人员学到的7个绝对真理](https://monicalent.com/blog/2019/06/03/absolute-truths-unlearned-as-junior-developer/)
  - 在职业生涯早期，你在支持性的团队中一年内可以学到的东西，是独自编码的10倍。
  - 每家公司都有问题，每家公司都有技术债务。
  - 在缺乏实际经验的领域过于坚持自己的观点是相当傲慢的。
  - 许多会议演讲涉及的是概念证明，而不是现实场景。
  - 处理遗留代码是完全正常的。
  - 架构比挑剔细节更重要。
  - 在适当的情况下，应专注于自动化而非文档。
  - 有一些技术债务是健康的。
  - 高级工程师必须发展除编程之外的许多技能。
  - 我们在某些领域仍然是初级的。
- [如何构建优质软件](https://knowledge.csc.gov.sg/ethos-issue-21/how-to-build-good-software/)
  - 对基本工程实践的一个良好高级摘要。
  - 不良软件的根本原因与特定工程选择的关系较小，而与开发项目管理方式的关系更大。
  - 没有绝对意义上的优质工程：它取决于你的需求和遇到的实际问题。
  - 软件应被视为一个静态产品，而应被视为开发团队集体理解的活生生体现。
  - 软件项目很少因为太小而失败；它们失败是因为变得太大了。
  - 警惕伪装成问题陈述的官僚目标。如果我们的最终目标是改善公民的生活，我们需要明确承认那些使他们生活变差的事情。
  - 构建软件不是为了避免失败；而是要尽可能快地战略性地失败，以获取构建优质产品所需的信息。
- [如何成为一名-10倍工程师](https://taylor.town/-10x)
  - 抵消10名工程师的产出。
  - 在技术讨论中扣押10名工程师。
  - 在云成本上浪费10周的工资。
  - 在糟糕的架构上浪费400小时的工程时间。
  - 产生400小时的错误排查。
- [如果我能给15年前的自己一些编程建议](https://mbuffett.com/posts/programming-advice-younger-self/)
  - 如果你（或你的团队）经常自找麻烦，那就修理那把枪。
  - 评估你在质量和速度之间的权衡，确保它适合你的环境。
  - 花时间磨利斧头几乎总是值得的。
  - 如果你无法轻松解释为什么某事困难，那么它就是偶然的复杂性，这可能值得解决。
  - 尝试更深入地解决错误。
  - 不要低估挖掘历史以调查某些错误的价值。
  - 坏代码会给你反馈，完美代码不会。在写坏代码和好代码之间，倾向于写坏代码。
  - 让调试更容易。
  - 在团队中工作时，你通常应该提出问题。
  - 发布节奏非常重要。认真思考什么能让你快速且频繁地发布。
- [专家通才](https://martinfowler.com/articles/expert-generalist.html)，martinfowler.com，提出了对“T型工程师”的有趣看法
  - 专家通才的特征：好奇心，协作性，客户导向，重视基础知识，通才与专才技能的结合，对相关领域的同理心
  - 评估专家通才：招聘和职业发展
  - 培养专家通才：从工具到基础
    - “为什么我们的注意力总是偏向于工具专长？这并不是因为人们目光短浅或懒惰；而是因为基础在噪音中难以看到。”
  - 专家通才仍然需要专才
  - LLM时代中的专家通才
    - “与专才类似，LLM可以快速回答专家通才在新领域工作时会遇到的问题。”
    - “他们不是寻找“答案”，而是提示他们生成问题，解释机制，并提供示例，甚至提供帮助探索想法背后机制的工具。”

## 其他通用资料和资源列表

### 其他列表

- [liuchong/awesome-roadmaps: A curated list of roadmaps.](https://github.com/liuchong/awesome-roadmaps)

### 书籍

- 📖 [The Imposter's Handbook](https://bigmachine.io/products/the-imposters-handbook) - \$30。作者说明："没有计算机科学学位？我也没有——这就是我写这本书的原因。"
- 📖 [The Computer Science Book](https://thecomputersciencebook.com/book/)
- 📖 [The Software Engineer's Guidebook](https://www.engguidebook.com/)：Gergely Orosz 编写的软件工程行业指南。内容极其详尽。

### 文章

- [mr-mig/every-programmer-should-know: 每个软件开发人员都应该知道的（主要是）技术内容集合](https://github.com/mr-mig/every-programmer-should-know)
- [软件开发著名定律](https://www.timsommer.be/famous-laws-of-software-development/)
- [亚马逊建造者图书馆](https://aws.amazon.com/builders-library/?cards-body.sort-by=item.additionalFields.customSort&cards-body.sort-order=asc)
  - 这个 [推文](https://twitter.com/g_bonfiglio/status/1673650452846505985) 线程中有一个最佳文章列表
- [kdeldycke/awesome-falsehood](https://github.com/kdeldycke/awesome-falsehood): 程序员认为的谬误
- [hellerve/programming-talks](https://github.com/hellerve/programming-talks)
- [TechYaks](https://techyaks.com/): 演讲列表
- [改变了我对编程看法的演讲](http://www.opowell.com/post/talks-that-changed-the-way-i-think-about-programming/)
- [每个计算机科学专业学生应该知道的内容](http://matt.might.net/articles/what-cs-majors-should-know/)
- [kamranahmedse/developer-roadmap](https://github.com/kamranahmedse/developer-roadmap)
- [mtdvio/every-programmer-should-know](https://github.com/mtdvio/every-programmer-should-know): 每个软件开发人员应该知道的（主要是）技术内容集合
- [Mike Acton 对专业软件工程师的期望](https://adamj.eu/tech/2022/06/17/mike-actons-expectations-of-professional-software-engineers/)
- [他们没有教你的软件工程内容](https://vadimkravcenko.com/shorts/things-they-didnt-teach-you/)
  - 领域知识比你的编码技能更重要
  - 代码是次要的。商业价值是首要的。
  - 你大部分时间都在与不确定性打交道
- [我们高估了我们的短期能力，但低估了我们的长期能力。](https://paavandesign.com/blog/ostaulta/)
  - 专业化是昆虫的专利。
- [想在你的技术职业生涯中获得不公平的优势？消费其他角色的内容](https://matthewgrohman.substack.com/p/want-an-unfair-advantage-in-your)
  - 跨职能理解在现代科技公司中是关键
  - 有助于避免低估其他角色的重要性和难度
  - 有助于你在与这些角色的人互动时更具战略性
- [十年内自学编程](https://norvig.com/21-days.html)
- [你显然必须自己犯的错误](https://medium.com/@mcfunley/mistakes-you-apparently-just-have-to-make-yourself-cc2dd2bfc25c)
- [我认识的最好的程序员](https://endler.dev/2025/best-programmers/)

### 公理

- [信条 - Urbit](https://urbit.org/blog/precepts/)
  - 数据优于代码。
  - 正确性比性能更重要。
  - 确定性优于启发式方法。
  - 一百行的简洁优于二十行的复杂。
  - 如果你的抽象存在泄漏，那不是由于宇宙的某种定律；只是你抽象能力差。通常，你对抽象的定义不够精确。
  - 如果你因为害怕唤醒其中的恶魔而避免修改某段代码，你就是在恐惧中生活。如果你只停留在你编写或熟悉的小部分代码中，你将永远无法写出传奇的代码。所有代码都是由人类编写的，也可以被人类掌握。
  - 如果显然存在正确的方式和错误的方式，就选择正确的方式。编程需要惊人的纪律。
  - 获得正确答案的最佳方式是尝试错误的方式。
  - 实践告诉你事情是好是坏；理论告诉你原因。
  - 没有资格解决一个问题并不是不解决它的理由。
  - 如果你不理解你所使用的系统，你就无法控制它。如果没有人理解这个系统，系统就控制了你。
- [嵌入式经验法则](https://embeddedartistry.com/blog/2018/04/26/embedded-rules-of-thumb/)
- [50个改变我一生的观念](https://www.perell.com/blog/50-ideas-that-changed-my-life)
- [关于10,000小时编程的反思](https://matt-rickard.com/reflections-on-10-000-hours-of-programming/)
- [20年软件工程师生涯中学到的20件事](https://www.simplethread.com/20-things-ive-learned-in-my-20-years-as-a-software-engineer/)

### 课程

- [Google Tech Dev Guide](https://techdevguide.withgoogle.com/)
- [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/), MIT。包含关于 shell、编辑器、数据处理、git、调试和性能分析、元编程、安全和密码学的讲座。
- [Mathematics for the adventurous self-learner](https://www.neilwithdata.com/mathematics-self-learner)，Neil Sainsbury
- [jwasham/coding-interview-university](https://github.com/jwasham/coding-interview-university)：一套完整的计算机科学学习计划，帮助你成为软件工程师。
- [Teach Yourself Computer Science](https://teachyourselfcs.com/)：一套有偏见的最佳计算机科学资源集合。
- [ossu/computer-science](https://github.com/ossu/computer-science)：免费的自学计算机科学课程！

## 话题

### 会计

- [Engineers Do Not Get To Make Startup Mistakes When They Build Ledgers](https://news.alvaroduran.com/p/engineers-do-not-get-to-make-startup)

### 算法与数据结构

- 阅读 [CLRS](https://mitpress.mit.edu/books/introduction-algorithms)。你可以在 [OCW](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-introduction-to-algorithms-sma-5503-fall-2005/) 上观看并下载课程 - 还有更新的课程。
- 或者阅读 [The Algorithm Design Manual](https://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1849967202?ie=UTF8&qid=1297127794&ref_=sr_1_1&sr=8-1)
- 在 [Project Euler](https://projecteuler.net/) 上尝试一些算法
- [CS 61B Spring 2023](https://sp23.datastructur.es/)

其他资源：

- [Algorithms](http://jeffe.cs.illinois.edu/teaching/algorithms/), Jeff Erickson

老实说：算法可能是一个相当枯燥的话题。[这个 quora 问题](https://www.quora.com/Is-there-a-book-that-teaches-algorithms-data-structures-and-other-computer-science-basics-in-a-fun-way) 列出了一些更有趣的替代学习方式，包括：

- [Grokking Algorithms](https://www.amazon.com/dp/1617292230/ref=cm_sw_su_dp)
- [Essential Algorithms](https://www.amazon.com/Essential-Algorithms-Practical-Approach-Computer/dp/1118612108?ie=UTF8&*Version*=1&*entries*=0)
- [Data Structure Visualization](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)
- 🎞 [6 分钟内了解 15 种排序算法](https://www.youtube.com/watch?v=kPRA0W1kECg&ab_channel=TimoBingmann)
- [Hashing](https://samwho.dev/hashing/)
- [Visualizing Algorithms](https://bost.ocks.org/mike/algorithms/)
- [B-trees 和数据库索引](https://planetscale.com/blog/btrees-and-database-indexes)
- [Big O 可视化](https://samwho.dev/big-o/)
- [像宜家说明书一样解释算法](https://idea-instructions.com/)

示例实现：

- [trekhleb/javascript-algorithms](https://github.com/trekhleb/javascript-algorithms): 用 JavaScript 实现的算法和数据结构
- [The Algorithms](https://the-algorithms.com/)

分布式系统中的算法：

- [Raft 共识算法](https://raft.github.io/)

### API 设计与开发

通用 REST 内容：

- [架构风格与基于网络的软件架构设计](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)，Roy Fielding（REST 的发明者）
- [构建 RESTful HTTP+JSON API 的有用资源集合。](https://github.com/yosriady/api-development-tools)
- [REST API 设计的最佳实践](https://stackoverflow.blog/2020/03/02/best-practices-for-rest-api-design/)，Stack Overflow 博客
- 📖 [无干扰的 REST：设计完美 API 的指南](https://www.mulesoft.com/sites/default/files/resource-assets/ebook-UndisturbedREST_v1.pdf)：关于 RESTful API 设计的非常完整的书籍。

示例指南：

- [微软的 REST API 指南](https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md)
- [Zalando RESTful API 和事件方案指南](https://opensource.zalando.com/restful-api-guidelines/)
- [Google 的 API 设计指南](https://cloud.google.com/apis/design/)：设计网络 API 的通用指南。
- [AIP-1：AIP 目的和指南](https://google.aip.dev/1)
  - AIP 代表 API 改进提案，这是一个为 API 开发提供高层、简洁文档的设计文件。

更具体的主题：

- [为什么你应该在 API 中使用链接而不是键来表示关系](https://cloud.google.com/blog/products/application-development/api-design-why-you-should-use-links-not-keys-to-represent-relationships-in-apis)，Martin Nally，Google
  - “在 API 中使用链接而不是外键来表达关系，可以减少客户端需要了解的信息量，并减少客户端和服务器之间的耦合方式。”
- [给我 /events，而不是 webhooks](https://blog.sequin.io/events-not-webhooks/)
  - 事件可以解锁一些急需的 webhook 功能，例如允许你的 webhook 消费者重播或重置其 webhook 订阅的位置。
- [解锁 JSON Patch 的强大功能](https://zuplo.com/blog/2024/10/10/unlocking-the-power-of-json-patch)

### 态度、习惯、心态

- [掌握编程](https://www.prod.facebook.com/notes/kent-beck/mastering-programming/1184427814923414#), Kent Beck.
- [高效程序员的特质](https://www.oreilly.com/ideas/the-traits-of-a-proficient-programmer)
- [编程之道](http://www.mit.edu/~xela/tao.html): 一组关于编程的寓言。
- [拥有主动性是实现目标最有效的方式](http://www.theeffectiveengineer.com/blog/take-ownership-of-your-goals)
- [找到时间成为更好的开发者](https://medium.freecodecamp.org/finding-time-to-become-a-better-developer-eebc154881b2)
- [每天十分钟](https://medium.com/@alexallain/ten-minutes-a-day-e2fa1084f924): Alex Allain 如何通过每天写作十分钟，在不到 200 小时内写完一本书。
- [软件工程师的照顾与喂养（或，为什么工程师会抱怨）](https://humanwhocodes.com/blog/2012/06/12/the-care-and-feeding-of-software-engineers-or-why-engineers-are-grumpy/)
  - 在软件、产品经理和设计师这三元组中，只有工程师被期望关闭他们的创造力，只负责产出。
  - 工程师和产品经理都倾向于错误地认为产品规格或需求等同于宜家家具的说明书。
  - 这是让工程师感到不满的首要原因之一：不断变化的优先级。
  - 尽管许多工程师会抱怨产品经理改变主意，但几乎没有人会在他们的时间估算中考虑这一点。
  - 计算机科学课程并不是为了准备你面对工业界中将要遇到的任务。
  - 当工程师人数多于可用人数时，工程师的时间会从开发转向规划、同步和协调。
  - 让工程师参与创意过程
  - 给工程师提供创意的机会。
  - 鼓励休假。
  - 让他们编写代码
  - 表达感激
- [产品导向的软件工程师](https://blog.pragmaticengineer.com/the-product-minded-engineer/), Gergely Orosz
  - 优秀的产品工程师知道，最迷人的产品需要适当的深度。
  - 产品导向的工程师会迅速绘制出边缘情况，并思考如何减少这些情况的工作量：通常会提出不需要工程工作的解决方案。
  - 参与用户研究和客户支持
  - 提出有充分依据的产品建议
  - 提供产品/工程权衡
- [40 年的 40 个教训](https://medium.com/@schlaf/40-lessons-from-40-years-de39d2c622d6), Steve Schlafman
  - 如果你想在最重要的事情上取得进展，你需要决定你会让谁失望。这是不可避免的。
  - 你能做出的最好的投资是自己的教育。永远不要停止学习。第二好的投资是通过真实而有意义的互动建立你的网络。这是你所知道的和你认识的人。
  - 你永远得不到你没有要求或积极寻找的东西。去争取吧！
  - 它不是关于隧道尽头的光，而是隧道本身。每天都要出现，享受这个过程。
  - 优秀的团队成员总是将组织及其目标置于自己的个人利益之上。
  - 选择你的时机。我们的时间有限，我们的大脑只能处理这么多。专注是关键。明智地选择。
  - 每个人可能都在与某些事情作斗争。要善良。要乐于助人。
- [关于编码、自我和注意力](https://josebrowne.com/on-coding-ego-and-attention/)
  - 初学者的心态接受绝对知识是无限的这一事实，因此记分是浪费时间。
  - 掌握仅仅是动量的积累，而不是知识的积累。
  - 应对自我干扰的经历教会我热爱解决问题的过程。它教会我热爱并尊重学习过程。结果我更加高效。我更少焦虑。我是一个更好的队友。我是一个更好的朋友和更好的思考者。
- [固定 vs. 成长：塑造我们生活的两种基本心态](https://www.brainpickings.org/2014/01/29/carol-dweck-mindset/)
- [优秀的软件工程师是什么样子？](https://fwouts.com/articles/great-software-engineer)
- [良好的睡眠、良好的学习、良好的生活](https://supermemo.guru/wiki/Good_sleep,_good_learning,_good_life)
- 🎞 [史蒂夫·乔布斯：如果你不请求帮助，你就不会走得很远](https://www.youtube.com/watch?v=zkTf0LmDqKI&ab_channel=SiliconValleyHistoricalAssociation)
- [编程名言](https://www.ronaldsvilcins.com/2020/12/10/programming-quotes/)
- [善良](https://boz.com/articles/be-kind)
  - 善良本质上是对你周围人的影响负责。
  - 它要求你注意他们的感受，并考虑你的存在对他们造成的影响。
- [沃伦·巴菲特说，这个简单的习惯将成功人士与其他人区分开来](https://www.inc.com/marcel-schwantes/warren-buffett-says-this-is-1-simple-habit-that-separates-successful-people-from-everyone-else.html)
  - 成功人士和非常成功人士之间的区别在于，非常成功人士几乎对一切都说不。
- [如何变得幸运？](https://jjude.com/luck)
- [程序员应该停止庆祝无能](https://world.hey.com/dhh/programmers-should-stop-celebrating-incompetence-de1a4725), DHH
  - 编程的魔力很大程度上只是你尚未知道的事情。
  - 如果你打算将编程作为你的职业，那么认为你不应该在某些通往精通的道路上是不可接受的。
- [没有速度限制](https://sive.rs/kimo)
- [不要等待动力，行动创造动量](https://salman.io/blog/momentum-motivation/)
  - 从一个微小的任务开始。然后借助它的动量前进。
- [最重要的编码习惯](https://puppycoding.com/2023/07/22/healthy-coding-habits/)
  - 最重要的编码习惯
  - 每天拉伸
  - 定期休息
  - 不要在深夜编码
  - 改善你的编码环境
- [给那些已经读过所有其他建议文章的新软件开发者的建议](https://buttondown.email/hillelwayne/archive/advice-for-new-software-devs-whove-read-all-those/)
- [微服务不是问题。无能的人才是](https://nondv.wtf/blog/posts/microservices-arent-the-problem-incompetent-people-are.html)
- [高自主性](https://www.highagency.com/) (30 分钟阅读)
- [软件工程中的“良好品味”是什么？](https://www.seangoedecke.com/taste/): 它全部关于情境权衡。

> 恶劣的自我感觉被低估了：很多讨论集中在克服恶劣的自我感觉上。我建议接受自我怀疑，每天怀疑自己。在一个快速发展的行业中，你每年的很多知识都会过时，你周围最年轻的人都不断掌握你没有的技能；你通过以新手的决断（甚至恐惧）来保持竞争力。这个跑步机的好处是，每个工程师都在上面：你是一个冒牌者，并不意味着其他人比你更值得，因为他们也是冒牌者。你应该为自己辩护，承担风险，当事情顺利时拍拍自己的背，并且，当你开始建立解决问题的记录时，信任你的技能和适应能力。但请不要误解：你的好坏只取决于你最后解决的问题。

Dan Heller, 在软件领域建立职业生涯

> 我已经学会了从不把写作的井抽干，而是在井底还有东西时就停止，让夜晚的泉水重新填满它。 —— 欧内斯特·海明威

- [Grug 脑的开发者](https://grugbrain.dev): 自我意识程序员的习惯。像《编程之道》一样，但风格不同。

> 良好的判断来自于经验。
> 经验来自于糟糕的判断。

#### 拖延

- [新闻对你有害 – 放弃阅读新闻会让你更快乐](https://www.theguardian.com/media/2013/apr/12/news-is-bad-rolf-dobelli), The Guardian
  - 新闻误导
  - 新闻无关紧要
  - 新闻没有解释力
  - 新闻对你的身体有害
  - 新闻增加认知错误
  - 新闻抑制思考
  - 新闻像毒品一样起作用
  - 新闻浪费时间
  - 新闻使我们被动
  - 新闻扼杀创造力

### 认证/授权

- [微服务世界中的授权](https://www.alexanderlolis.com/authorization-in-a-microservices-world)
- [授权逻辑：规则很难，因为它们会随时间演变](https://www.osohq.com/post/rules-are-hard-logic-for-authorization)
- [哥本哈根书](https://thecopenhagenbook.com/) 提供了在Web应用程序中实现认证的一般指南

### 自动化

- [自动化应该像钢铁侠，而不是奥丁](http://queue.acm.org/detail.cfm?id=2841313)

### 最佳实践

- [软件工程实践](https://simonwillison.net/2022/Oct/1/software-engineering-practices/#tested-dev-environments)

### Beyond software engineering & random

- [Why Software Engineers like Woodworking](https://www.zainrizvi.io/blog/why-software-engineers-like-woodworking/)

### 偏见

偏见不仅仅适用于招聘。例如，基本归因偏见也适用于批评很久以前在完全不同背景下编写的代码。

- [认知偏见速查表](https://buster.medium.com/cognitive-bias-cheat-sheet-55a472476b18). #hiring

### 业务

- [开发者支付基础](https://github.com/juspay/hyperswitch/wiki/Payments-101-for-a-Developer)
- [自制计费系统面临的四大问题](https://www.getlago.com/blog/the-4-biggest-problems-with-homemade-billing-systems)
- [鱿鱼的计费系统构建的14个痛点](https://arnon.dk/the-14-pains-of-billing/)

### Buy vs. Build

- [Choose Boring Technology](https://boringtechnology.club/)
- [Build vs. Buy](https://entropicthoughts.com/build-vs-buy)
  - The reason we want to buy as much as possible is that an organisation has a limited capacity for expertise, so we don’t want to have to become experts on things that don’t make up a competitive advantage.
- [Platform Engineering: Build vs Buy](https://kanenarraway.com/posts/platform-engineering-build-vs-buy/)
  - If someone tells me they can build something cheaper than a vendor, I’m immediately skeptical because I don’t think most people can accurately forecast the actual cost of maintenance in the long term.

### 缓存

- [缓存挑战和策略](https://aws.amazon.com/builders-library/caching-challenges-and-strategies/), Amazon Builders Library

### 职业发展

- [高级开发人员的联合三角形](http://frontside.io/blog/2016/07/07/the-conjoined-triangles-of-senior-level-development.html) 探讨如何定义高级工程师。
- [工程师成长的十个原则](https://medium.com/@daniel.heller/ten-principles-for-growth-69015e08c35b)，Dan Heller。
- [不要称自己为程序员](https://www.kalzumeus.com/2011/10/28/dont-call-yourself-a-programmer/)，Patrick McKenzie。
- [关于成为工程经理](https://nickmchardy.com/2019/02/on-being-an-engineering-manager.html)
- [25岁时我希望得到的职业建议](https://www.linkedin.com/pulse/career-advice-i-wish-had-25-shane-rodgers/?trk=hp-feed-article-title-like)
  - 职业生涯是一场马拉松，而不是短跑
  - 大多数成功来自于重复，而不是新事物
  - 如果工作真的那么好，所有有钱人都会有这些工作
  - 管理是关于人，而不是事物
  - 真诚地倾听他人
  - 认识到员工是有限情感容量的人
  - 不要只和同龄人建立人脉
  - 永远不要为了工作原因牺牲个人道德
  - 认识到失败是学习的一部分
- [我希望年轻时得到的职业建议](https://80000hours.org/2019/04/career-advice-i-wish-id-been-given-when-i-was-young/)
  - 不要过多关注长期计划。
  - 找到优秀的思考者，并冷打电话给你最钦佩的人。
  - 终生重视生产力。
  - 不要过度优化那些不是你首要任务的事情。
  - 多读书，读别人不读的东西。
  - 严肃地思考要优先解决什么问题。
  - 多读历史。
- [为什么优秀的开发人员被提升到不幸福](https://robwalling.com/2007/06/27/why-good-developers-are-promoted-into-unhappiness/)，Rob Walling。或者为什么管理可能不适合你。
- [如何利用你的职业生涯帮助解决世界上最紧迫的问题](https://80000hours.org/key-ideas/)
- [高级工程师的工作是什么？](https://jvns.ca/blog/senior-engineer/) 你需要的不仅仅是个人贡献者。
- [从编码训练营毕业生到构建分布式数据库](https://medium.com/swlh/from-coding-bootcamp-graduate-to-building-distributed-databases-29acbb723d8)
  - 读书（和论文），而不是博客文章
  - 为你的职业轨迹负责
- 🏙 [全面的工程师](https://speakerdeck.com/swanandp/the-well-rounded-engineer) 包含许多优秀的书籍推荐。
  - 范式多语种（学习不同的语言和范式）
  - 数据库多语种
  - 协议多语种（最好是TCP/IP和HTTP）
  - 熟练使用构建工具、打包和分发
  - 调试、可观测性
  - 部署、基础设施和DevOps
  - 软件架构和扩展
  - 能够编写玩具编译器、解释器和解析器
  - 能够编写玩具游戏
  - 能够理解算法分析
- [一些职业建议](https://lethain.com/career-advice/)，Will Larson。
  - 你得到的建议是某人试图综合他们的经验，而不是对世界运作方式的准确陈述。
  - 建立声望的水库。
  - 有些人非常擅长某件事，以至于他们变得在当前角色中不可替代，这导致他们即使在其他更有趣的角色中也是合适人选，却仍然被困在当前角色中。
  - 优秀的关系会跟随你到任何地方。糟糕的关系也是如此。
  - 在职业生涯早期，尽量在不同类型的公司和不同产品领域工作。
- [邪恶的建议：避免“容易”的事情](http://yosefk.com/blog/evil-tip-avoid-easy-things.html)
- [终极代码练习](https://blog.codinghorror.com/the-ultimate-code-kata/)
- [高级软件工程师的特质](https://sergiomartins8.hashnode.dev/why-is-a-senior-engineer-senior): 影响力、认知、可见性、影响力、指导
- [软件工程 - 软件部分](https://addyosmani.com/blog/software-engineering-soft-parts/)
  - 批判性思考并提出有充分理由的论点
  - 掌握基础知识
  - 专注于用户，其他一切都会随之而来
  - 学会如何学习
- [如何拥有你的成长作为软件工程师](https://jes.al/2022/07/how-to-own-your-growth-as-a-software-engineer/)
- [四十年程序员](https://codefol.io/posts/the-forty-year-programmer/)
  - 你变得越好，你就越不像其他人
  - 通过做基础工作来学习深层原理
  - 看其他领域，从其他领域学习
  - 要小心生产力技巧
- [高级工程师生活在未来](https://www.zerobanana.com/essays/living-in-the-future/)
- [你的职业地图会是什么样子？](https://tomcritchlow.com/2023/04/26/career-maps/)
- [如何在亚马逊（或其他任何大公司）取得成功](https://www.reddit.com/r/cscareerquestions/comments/4x0ugj/how_to_be_successful_at_amazon_or_any_other_large/)
- [仅仅优秀是不够的](https://joshs.bearblog.dev/being-good-isnt-enough/)
  - 最大的收益来自于结合不同学科。
- [停止回避政治](https://terriblesoftware.org/2025/10/01/stop-avoiding-politics/) 是对“政治”这个词当前（负面）含义的一个好的反主流观点。
  - 从某种意义上说，"政治"获得这种含义是不幸的，因为亚里士多德正确地认为政治是实践智慧的最高形式，因为它涉及人类作为社会动物的特性。
  - “好的政治就是以良好结果服务为目的，对关系和影响力进行战略性处理。”
  - 例子：在需要之前建立关系，理解激励因素，有效向上管理，创造双赢局面，保持可见性。
  - “不进行好的政治的替代方案不是没有政治。它是坏的政治默认获胜。它是那些错误的人因为大声说话而得逞，而那些正确的人因为沉默而无法发声。”

关于高级工程师：

- [初级开发人员关于成为高级开发人员的错误信念](https://vadimkravcenko.com/shorts/falsehoods-junior-developers-believe-about-becoming-senior/)

#### 选择你的下一个/第一个机会

- [职业决策 - Elad Gil - Elad 博客](https://blog.eladgil.com/p/career-decisions)

#### Getting to Staff Eng

- [I became a FAANG Staff Engineer in 5 years. These are the 14 lessons I learned along the way.](https://medium.com/geekculture/i-became-a-faang-staff-engineer-in-5-years-here-are-the-14-lessons-i-learned-along-the-way-f70ac078875c)
  - 软件工程不仅仅是编码。实际上，编码只是其中一小部分。
  - 将你的工作流程化
  - 对反馈保持开放并倾听。真的，要倾听。
  - 优秀的反馈很难找到；珍惜它。
  - 留意地平线（但不要同时关注两处）。
  - 弄清楚什么重要，并让其他事情随风而去。
  - 比较确实是快乐的窃贼。
  - 导师关系是一件美好的事情。
  - 一般来说，美好的日子并不是凭空发生的。
  - 建议和指导只是建议；它们不是规则。
- [达到Staff-plus工程师角色的指南](https://staffeng.com/guides/), Will Larson
  - [提高可见度](https://staffeng.com/guides/being-visible)
  - [关于Staff-plus工程的额外资源](https://staffeng.com/guides/learning-materials)
- [Staff角色原型](https://staffeng.com/guides/staff-archetypes/), Will Larson

### 字符集

- [每个软件开发人员绝对、肯定必须了解的关于 Unicode 和字符集的最低限度（没有借口！）](http://www.joelonsoftware.com/articles/Unicode.html)
- [2023 年每个软件开发人员必须了解的关于 Unicode 的最低限度（仍然没有借口！）](https://tonsky.me/blog/unicode/)

### 国际象棋

(yes - 国际象棋 gets its own section :)

- [国际象棋编程维基](https://www.chessprogramming.org/Main_Page)
- [压缩国际象棋移动](https://mbuffett.com/posts/compressing-chess-moves/)

### 云服务

- [open-guides/og-aws](https://github.com/open-guides/og-aws): AWS 实用指南

### 代码审查

- [如何进行代码审查](https://google.github.io/eng-practices/review/reviewer/)，Google 工程实践文档。
- [提交后的审查](https://medium.com/@copyconstruct/post-commit-reviews-b4cc2163ac7a)：一个可以提高开发人员速度的有趣想法（尽管有一些注意事项）。
- [如何让你的代码审查者爱上你](https://mtlynch.io/code-review-love/)
  - 先审查自己的代码
  - 编写清晰的变更列表描述
  - 自动化简单的事情
  - 用代码本身回答问题
  - 严格限定变更范围
  - 将功能性和非功能性变更分开
  - 以优雅的方式回应批评
  - 巧妙地征求缺失的信息
  - 将所有平局都归功于审查者
  - 最小化审查轮次之间的延迟
- [像人一样进行代码审查](https://mtlynch.io/human-code-reviews-1/)
- [Ask HN：你们是如何审查代码的？](https://news.ycombinator.com/item?id=11416746)：HackerNews 上关于此话题的精彩讨论，充满有趣的观点。
- [代码审查的马斯洛金字塔](https://www.dein.fr/posts/2015-02-18-maslows-pyramid-of-code-review)
  - 关于同一主题的另一篇文章：[代码审查金字塔](https://www.morling.dev/blog/the-code-review-pyramid/)
- [远程团队的代码审查](https://web.hypothes.is/blog/code-review-in-remote-teams/)：一套非常完整的规则。
- [默认不进行代码审查](https://www.raycast.com/blog/no-code-reviews-by-default/)
  - 责任重于惯例

### 编码与代码质量

- [编写易于删除而非易于扩展的代码](http://programmingisterrible.com/post/139222674273/write-code-that-is-easy-to-delete-not-easy-to)
- [无我编程的十诫](http://blog.codinghorror.com/the-ten-commandments-of-egoless-programming/)
- 📖 [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.goodreads.com/book/show/3735293-clean-code), Robert C. Martin。描述了众多有用的最佳实践。篇幅较长。还有一个[Clean Code 快速参考](../cheatsheets/Clean-Code-V2.4.pdf)。
- [软件工艺是关于什么的](https://blog.cleancoder.com/uncle-bob/2011/01/17/software-craftsmanship-is-about.html)
  - 我们厌倦了编写垃圾代码。
  - 我们不会接受“以后再清理”的愚蠢老谎言。
  - 我们不会相信“快速意味着肮脏”的说法。
  - 我们不会允许任何人强迫我们做出不专业的行为。
- [布尔变量命名技巧](https://dev.to/michi/tips-on-naming-boolean-variables-cleaner-code-35ig)
  - 有一个惯例是用 "is" 或 "has" 前缀布尔变量和函数名。
  - 尽量始终使用 is，即使在复数形式中 (`isEachUserLoggedIn` 比 `areUsersLoggedIn` 或 `isUsersLoggedIn` 更好)
  - 避免自定义前缀 (`isPaidFor` 比 `wasPaidFor` 更好)
  - 避免使用否定 (`isEnabled` 比 `isDisabled` 更好)
- [如何编写难以维护的代码](https://github.com/Droogans/unmaintainable-code/blob/master/README.md)
- [kettanaito/naming-cheatsheet](https://github.com/kettanaito/naming-cheatsheet): 一个全面的、与语言无关的变量命名指南。A/HC/LC 模式的发源地。
- 🧰 [质量工程指南](https://qeunit.com/guides/)
- [使代码难以阅读的因素：复杂性的视觉模式](https://seeinglogic.com/posts/visual-readability-patterns/)
- [zakirullin/cognitive-load: 🧠 认知负荷才是关键](https://github.com/zakirullin/cognitive-load)
- [如何创建软件质量](https://lethain.com/quality/)

### 通信

另见写作部分

- [如何作为开发者有效沟通](https://www.karlsutt.com/articles/communicating-effectively-as-a-developer/)
  - 针对短篇、中篇和长篇写作的大量具体建议和示例
- [编程时你脑海中会浮现什么？](https://dillonshook.com/what-do-you-visualize-while-programming/)

### 编译器

- [The Compiler Writer Resource Page](https://c9x.me/compile/bib/)
- [kanaka/mal](https://github.com/kanaka/mal): mal - Make a Lisp

### 配置

- [JSON 作为配置文件的缺点](https://arp242.net/weblog/JSON_as_configuration_files-_please_dont.html), Martin Tournoij.
  - 无法添加注释
  - 过多的引号和语法噪音
  - 使用 DC（声明式配置）来控制逻辑通常不是一个好主意。
- [你的配置很糟糕？尝试使用真正的编程语言](https://beepb00p.xyz/configs-suck.html)
  - 大多数现代配置格式都很糟糕
  - 使用真正的编程语言
- [代码抱怨：配置复杂度钟](https://mikehadlow.blogspot.com/2012/05/configuration-complexity-clock.html)
  - 我并不是说在某些情况下实现复杂的配置、规则引擎或 DSL 是不合适的，事实上，如果需求合适，我非常乐意构建一个 DSL，但我是在说你应该在开始之前了解其影响并认识到你所处的位置。
  - 最初希望非技术人员可以通过 GUI 来配置应用程序，但事实证明这是一个错误的希望；将业务规则映射到引擎中需要一种只有开发团队中某些成员才具备的专业知识。

### 持续集成 (CI)

- [持续集成](https://martinfowler.com/articles/continuousIntegration.html), MartinFowler.com

### 数据分析与数据科学

- [让虚假数据看起来有意义的方法](https://danbirken.com/statistics/2013/11/19/ways-to-make-fake-data-look-meaningful.html)
  - 不要分享原始数据
  - 不要分享你的方法论
  - 不要包含置信区间
  - 不要质疑你自己的数据
- 📖 [Python 数据科学手册](https://jakevdp.github.io/PythonDataScienceHandbook/), O'Reilly

### 数据库

另请参阅 SQL 部分。

- [CAP 定理的通俗介绍](http://ksat.me/a-plain-english-introduction-to-cap-theorem)
- [PACELC 定理](https://en.wikipedia.org/wiki/PACELC_theorem): "在分布式计算机系统中，如果发生网络分区（P），必须在可用性（A）和一致性（C）之间做出选择（根据 CAP 定理），但否则（E），即使系统在没有分区的情况下正常运行，也必须在延迟（L）和一致性（C）之间做出选择。"
- [零停机时间数据库迁移](https://blog.rainforestqa.com/2014-06-27-zero-downtime-database-migrations/)（代码示例使用的是 Rails，但这种方法适用于任何编程语言）
- [现代存储系统背后的算法](https://queue.acm.org/detail.cfm?id=3220266)，ACM Queue
- [构建一个简单的数据库](https://cstack.github.io/db_tutorial/)
- [数据库系统读物，第五版](http://www.redbook.io/)
- [比较数据库类型：数据库类型如何演变以满足不同需求](https://dataguide.prisma.io/intro/comparing-database-types)
- [关系型数据库是如何工作的](http://coding-geek.com/how-databases-work/)
- [使用索引，Luke](https://use-the-index-luke.com/)
- [课程介绍 —— 为开发人员准备的 MySQL](https://planetscale.com/learn/courses/mysql-for-developers/introduction/course-introduction)，PlanetScale
- [查询引擎是如何工作的](https://howqueryengineswork.com/00-introduction.html)
- [为什么你应该可能使用 SQLite | Epic Web Dev](https://www.epicweb.dev/why-you-should-probably-be-using-sqlite)

数据库扩展：

- [Figma 数据库团队如何活下来讲述扩展的故事](https://www.figma.com/blog/how-figmas-databases-team-lived-to-tell-the-scale/)：关于分片的有趣故事

#### NoSQL

- [NOSQL Patterns](http://horicky.blogspot.nl/2009/11/nosql-patterns.html)
- [NoSQL Databases: a Survey and Decision Guidance](https://medium.baqend.com/nosql-databases-a-survey-and-decision-guidance-ea7823a822d#.9fe79qr90)
- The DynamoDB docs has some great pages:
  - [Read Consistency](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.ReadConsistency.html)
  - [From SQL to NoSQL](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/SQLtoNoSQL.html)
  - [NoSQL Design for DynamoDB](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-general-nosql-design.html)
- [Redis Explained](https://architecturenotes.co/redis/)

#### Postgres

- [Safe Operations For High Volume PostgreSQL](https://www.braintreepayments.com/blog/safe-operations-for-high-volume-postgresql/) (this is for PostgreSQL but works great for other DBs as well).
- [Transaction Isolation in Postgres, explained](https://www.thenile.dev/blog/transaction-isolation-postgres)
- [PostgreSQL exercises](https://pgexercises.com/)
- [Postgres operations cheat sheet](https://wiki.postgresql.org/wiki/Operations_cheat_sheet)
- [Just use Postgres](https://mccue.dev/pages/8-16-24-just-use-postgres)
- [Postgres is Enough](https://gist.github.com/cpursley/c8fb81fe8a7e5df038158bdfe0f06dbb)
- [Postgres: don't Do This](https://wiki.postgresql.org/wiki/Don't_Do_This)
- [PostgreSQL and UUID as primary key](https://maciejwalkowiak.com/blog/postgres-uuid-primary-key/)

### 数据格式

- [程序员对电话号码的错误认识](https://github.com/googlei18n/libphonenumber/blob/master/FALSEHOODS.md)，Google 的 `libphonenumber`。
- [自动补全规则](http://jeremymikkola.com/posts/2019_03_19_rules_for_autocomplete.html)：自动补全字段的粗略规范
- [程序员对地址的错误认识](https://www.mjt.me.uk/posts/falsehoods-programmers-believe-about-addresses/)
- [程序员对姓名的错误认识](https://www.kalzumeus.com/2010/06/17/falsehoods-programmers-believe-about-names/)
- [kdeldycke/awesome-falsehood](https://github.com/kdeldycke/awesome-falsehood)：程序员相信的错误认识
- [理解 UUID、ULID 和字符串表示](https://sudhir.io/uuids-ulids)
- [程序员对错误认识列表的错误认识](https://kevin.deldycke.com/2016/falsehoods-programmers-believe-about-falsehoods-lists)
- [Australia/Lord_Howe 是最奇怪的时区](https://ssoready.com/blog/engineering/truths-programmers-timezones/)
- [一封献给 CSV 格式的爱的信](https://github.com/medialab/xan/blob/master/docs/LOVE_LETTER.md)
- [程序员对航空的错误认识](https://flightaware.engineering/falsehoods-programmers-believe-about-aviation/)
- [模式 - Schema.org](https://schema.org/docs/schemas.html)

### 数据科学/数据工程

- [A dirty dozen: twelve common metric interpretation pitfalls in online controlled experiments](https://blog.acolyer.org/2017/09/25/a-dirty-dozen-twelve-common-metric-interpretation-pitfalls-in-online-controlled-experiments/)
- [datastacktv/data-engineer-roadmap](https://github.com/datastacktv/data-engineer-roadmap): 成为数据工程师的路线图
- [Awesome Data Engineering Learning Path](https://awesomedataengineering.com/)
- [Modern Data Infrastructure 的新兴架构](https://a16z.com/2020/10/15/the-emerging-architectures-for-modern-data-infrastructure/)
- [如何从单体数据湖过渡到分布式数据网格](https://martinfowler.com/articles/data-monolith-to-mesh.html)
  - 基于数据湖架构的数据平台存在常见的失效模式，导致在大规模部署时无法兑现承诺。
  - 我们需要将领域作为首要关注点，应用平台思维构建自助式数据基础设施，并将数据视为产品。
- [MLOps](https://madewithml.com/courses/mlops/)
- [Uber 的大数据平台：100+ PB 数据，分钟级延迟](https://eng.uber.com/uber-big-data-platform/)
- [SQL 应该是数据转换逻辑的默认选择](https://www.robinlinacre.com/recommend_sql/)

### 调试

另请参阅本文档中的事件响应部分

- [橡胶鸭子问题解决](http://blog.codinghorror.com/rubber-duck-problem-solving/)
- [橡胶鸭子调试](http://c2.com/cgi/wiki?RubberDucking)
- [五个为什么](https://en.wikipedia.org/wiki/5_Whys)
- [五个谎言分析](https://serce.me/posts/14-10-2021-the-five-lies-analysis)
  - 当该技术成为模板的一部分时，真正的问题才会显现。
  - 行动项可能与根本原因相距甚远。
  - 相关文章：[Google SRE 的演变](https://www.usenix.org/publications/loginonline/evolution-sre-google)
- [无限的如何](http://www.kitchensoap.com/2014/11/14/the-infinite-hows-or-the-dangers-of-the-five-whys/) 批评了五个为什么的方法，并提倡使用另一组问题，以从事件中获得最大的学习。
  - 参见：[人为错误：模型与管理](https://app.box.com/s/7z35l09amvr1vwxouh2s)
  - “五个为什么的问题在于，它过于专注于对工作如何完成和事件如何发生的一种线性和简单化的解释。”
  - “人为错误成为起点，而不是结论。”（Dekker, 2009）
  - “当我们问‘如何？’时，我们是在寻找一个叙述。”
  - “在决策和行动方面，我们想知道为什么某人会做他们所做的事。”
  - 在每个“为什么”步骤中，只会选择一个答案进行进一步调查。问“如何”会鼓励更广泛的探索。
  - “在事故调查中，就像在大多数其他人类活动中一样，我们容易受到‘你寻找的即是你找到的’（What-You-Look-For-Is-What-You-Find 或 WYLFIWYF）原则的影响。这是一个简单的认识，即我们对将要看到的内容的假设（What-You-Look-For）在很大程度上将决定我们实际找到的内容（What-You-Find）。”（Hollnagel, 2009, p. 85）（参见 [WYLFIWYF 的插图](https://www.youtube.com/watch?v=vJG698U2Mvo)）
  - “选择‘根本原因’的最后一个原因是，它在政治上被接受为已识别的原因。其他事件或解释可能被排除或未被深入研究，因为它们引发了对组织或其承包商尴尬或政治上不可接受的问题。”（Nancy Leveson, Engineering a Safer World, p. 20）
  - [有限理性](https://en.wikipedia.org/wiki/Bounded_rationality)：理性个体将选择一个令人满意的决策，而不是最优的决策
  - 该文章提供了具体的方法和问题，以从人们那里获取故事，从而获得更好的洞察。
    - 你当时期望会发生什么？
    - 如果你当时要向同事描述这个情况，你会说什么？
    - 这种情况是否符合一个标准场景？
    - 你当时试图实现什么？当时是否有多个目标？是否有时间压力或其他限制？
    - [在此处查看模板](http://www.kitchensoap.com/wp-content/uploads/2014/09/Velocity2014-PM-Fac-Handout-Debrief.pdf)
- [60秒内的Linux性能分析](http://techblog.netflix.com/2015/11/linux-performance-analysis-in-60s.html)
- [HubSpot的复盘：从250个为什么中学到的东西](https://product.hubspot.com/blog/bid/64771/post-mortems-at-hubspot-what-i-learned-from-250-whys)
- [调试小册子](https://jvns.ca/debugging-zine.pdf)，Julian Evans
- [如果你理解了一个错误，你就能修复它](https://wizardzines.com/comics/understand-can-fix/)
- [30分钟规则](https://daniel.feldroy.com/posts/thirty-minute-rule)：如果有人在某事上卡住超过30分钟，他们应该寻求帮助
- [如何创建一个最小可复现的示例](https://stackoverflow.com/help/minimal-reproducible-example)，Stack Overflow
- [一些提高调试能力的方法](https://jvns.ca/blog/2022/08/30/a-way-to-categorize-debugging-skills/)，Julia Evans
  - 学习代码库
  - 学习系统（例如，HTTP堆栈，数据库事务）
  - 学习工具（例如，`strace`，`tcpdump`）
  - 学习策略（例如，编写代码以复现，添加日志，休息一下）
  - 获取经验：根据一项研究，“专家只是形成了更多正确的假设，并且在找到故障时更有效率。”
- [什么是“Saff Squeeze”方法来查找错误？](https://stackoverflow.com/questions/23865274/what-exactly-is-the-saff-squeeze-method-of-finding-a-bug)
  - 一种系统的方法，用于从失败的测试中删除测试代码和非测试代码，直到测试和代码足够小，可以理解。
- [tcpdump非常棒](https://jvns.ca/blog/2016/03/16/tcpdump-is-amazing/)，Julia Evans
- [我们谈论“根本原因”时到底在谈什么](https://github.com/readme/guides/root-cause)
- [David A. Wheeler 对 David J. Agans 的《调试》一书的评论](https://dwheeler.com/essays/debugging-agans.html)
- [故障排除：一项永不落后的技能](https://www.autodidacts.io/troubleshooting/)
  - 包括一些有趣的调试故事的链接
- [软件团队对用户反馈的错误信念](https://thoughtbot.com/blog/falsehoods-software-teams-believe-about-user-feedback)

### 设计（视觉、用户体验、用户界面、字体排印）

我强烈建议阅读 [The Non-Designer's Design Book](http://www.amazon.com/gp/product/0133966151/ref=pd_lpo_sbs_dp_ss_1?pf_rd_p=1944687602&pf_rd_s=lpo-top-stripe-1&pf_rd_t=201&pf_rd_i=0321534042&pf_rd_m=ATVPDKIKX0DER&pf_rd_r=1R7MVQP0BCP7GP9VZGYX)。这是一本非常短小的书，将为您提供一些非常实用的设计建议。

- 如果您正在处理数据，Edward Tufte 的 [The Visual Display of Quantitative Information](http://www.amazon.com/Visual-Display-Quantitative-Information/dp/0961392142/ref=sr_1_1?ie=UTF8&qid=1458046603&sr=8-1&keywords=tufte) 被认为是经典之作。
- [Universal Principles of Design](http://www.amazon.com/Universal-Principles-Design-Revised-Updated/dp/1592535879/ref=sr_1_1?ie=UTF8&qid=1458046663&sr=8-1&keywords=universal+principles+of+design) 将为您提供足够的词汇和概念，以将设计挑战转化为文字。
- [HackerNews 的书籍推荐](https://news.ycombinator.com/item?id=12711060)
- 🏙[Design for Non-Designers](https://speakerdeck.com/tracymakes/design-for-non-designers-beyond-tellerand-dusseldorf-2018)

文章：

- [每个设计师都应该知道的10条可用性启发式原则](https://uxdesign.cc/10-usability-heuristics-every-designer-should-know-129b9779ac53)
  - 系统状态的可见性
  - 系统与现实世界的匹配
  - 每个系统都应该有一个明确的紧急出口
  - 不要忘记人们有90%的时间与其他应用程序进行交互
  - 识别优于记忆（识别 = 从记忆中浅层提取，例如一个熟悉的人，记忆 = 更深层的提取）
  - “完美不是在没有更多可以添加的时候实现的，而是在没有更多可以删除的时候实现的。” – Antoine de Saint-Exupery
  - 帮助用户识别、诊断和从错误中恢复
- [如何为您的数据可视化选择更美丽的颜色](https://blog.datawrapper.de/beautifulcolors/)
- [您可以每次安全遵循的视觉设计规则](https://anthonyhobday.com/sideprojects/saferules/)
- [可塑软件：在封闭应用程序的世界中恢复用户的自主权](https://www.inkandswitch.com/essay/malleable-software/)

字体排印：参见“字体排印”部分

资源：

- 🧰 [bradtraversy/design-resources-for-developers](https://github.com/bradtraversy/design-resources-for-developers)：设计和用户界面资源，包括库存照片、网页模板、CSS 框架、用户界面库、工具等。

### 设计（面向对象建模、架构、模式、反模式等）

这里有一些不错的书籍：

- 📖 [设计模式：可复用面向对象软件的基础](http://www.amazon.com/dp/0201633612/)：被称为“四人组”，几乎是任何开发人员必读的书籍。其中很多对于Python来说可能有些过时（因为一切皆为对象，动态类型），但主要思想（组合优于继承）确实是一个很好的哲学。
  - 以及他们的邪恶对手 [Resign Patterns](http://nishitalab.org/user/paulo/files/resign-patterns.txt)
- 📖 [企业应用架构模式](http://www.amazon.com/dp/0321127420/?tag=stackoverfl08-20)：学习如何在实际应用中使用数据库。Mike Bayer的SQLAlchemy深受这本书的影响。
- 📖 [领域驱动设计：软件核心复杂性应对之道](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)，Eric Evans
- 📖 [整洁架构](https://www.goodreads.com/book/show/18043011-clean-architecture)，Robert C. Martin。Uncle Bob提出了一种充分利用单一职责原则的架构。这是开始一个新代码库的好方法。也可以查看 [整洁架构速查表](../cheatsheets/Clean-Architecture-V1.0.pdf) 和 [这篇文章](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)。
- 📖 [游戏编程模式](https://www.amazon.com/dp/0990582906/ref=cm_sw_em_r_mt_dp_U_9xygFb9M86CXY)：Robert Nystrom通过游戏编程的媒介讲解设计、序列、行为模式等。这本书也可以在线免费阅读 [这里](https://gameprogrammingpatterns.com/contents.html)。

在架构方面，Martin Fowler是绝对的权威：查看他的 [软件架构指南](https://martinfowler.com/architecture/)。

文章：

- O'Reilly的 [如何在Python中犯错](https://www.oreilly.com/content/how-to-make-mistakes-in-python/)
- [程序员的教育](https://hackernoon.com/education-of-a-programmer-aaecf2d35312)：一位有35年行业经验的开发者的思考。其中有一个特别好的部分关于设计与复杂性（参见“端到端论点”，“分层与组件化”）。
- [领域驱动设计](https://en.wikipedia.org/wiki/Domain-driven_design)，维基百科。
- [抽象的光谱](https://www.youtube.com/watch?v=mVVNJKv9esE) 🎞，Cheng Lou
- [“Bug-O”符号](https://overreacted.io/the-bug-o-notation/)，Dan Abramov
- [反模式](.././antipatterns)
- [继承 vs. 组合](http://learnpythonthehardway.org/book/ex44.html)：Python中的一个具体例子。[另一个稍长的例子在这里](http://python-textbok.readthedocs.io/en/latest/Object_Oriented_Programming.html)。[最后一个，在Python 3中](http://blog.thedigitalcatonline.com/blog/2014/08/20/python-3-oop-part-3-delegation-composition-and-inheritance/#.V7SZ4tB96Rs)。
- [组合优于继承](http://c2.com/cgi/wiki?CompositionInsteadOfInheritance)
- [复杂性与策略](https://hackernoon.com/complexity-and-strategy-325cd7f59a92)：关于复杂性与灵活性的有趣视角，有非常棒的例子（例如Google Apps Suite vs. Microsoft Office）。
- [开源应用程序的架构](https://aosabook.org/en/index.html)
- [重新审视鲁棒性原则](https://cacm.acm.org/magazines/2011/8/114933-the-robustness-principle-reconsidered/fulltext)
  - Jon Postel：“在你所做的事情上要保守，在你接受他人所做的事情上要开放。”（RFC 793）
  - 鲁棒性原则影响了两个一般性问题领域：有序互操作性和安全性。
- [Unix哲学基础](http://catb.org/esr/writings/taoup/html/ch01s06.html#id2877610)，Eric S Raymond
- [专家软件设计者的八个习惯：图解指南](https://thereader.mitpress.mit.edu/habits-of-expert-software-designers/)
- [没有银弹——软件工程中的本质与偶然](https://worrydream.com/refs/Brooks_1986_-_No_Silver_Bullet.pdf)，Frederick P. Brooks, Jr. (1986)
  - 软件系统有四个属性使得构建软件变得困难：复杂性、一致性、可变性和不可见性
  - 有解决方法：
    - 利用大众市场来避免构建可以购买的东西。（“购买 vs. 构建”）
    - 将快速原型设计作为建立软件需求的计划迭代的一部分。
    - 有机地开发软件，随着系统的运行、使用和测试，不断增加更多的功能
    - 识别并培养新一代的伟大概念设计师。
    - （也包含在《人月神话》中）
- [走出泥潭](https://curtclifton.net/papers/MoseleyMarks06a.pdf)，Ben Moseley, Peter Marks (2006) 引入了本质复杂性和偶然复杂性的区分
  - 复杂性是当今软件中绝大多数问题的根本原因。不可靠性、延迟交付、缺乏安全性——甚至大型系统中的性能问题也可以最终归因于无法管理的复杂性。
  - 引用Dijkstra的话：“测试是完全不够的……（它）可以非常有效地用来显示错误的存在，但永远无法显示错误的不存在。”
  - 函数式编程在很大程度上避免了状态派生复杂性的问题，这得益于不可变性和状态与逻辑的清晰分离。
- [关于本质复杂性的一点笔记](https://olano.dev/blog/a-note-on-essential-complexity/)
  - 软件工程师的目标是减少偶然复杂性并协助处理本质复杂性。
- [软件设计是知识构建](https://olano.dev/blog/software-design-is-knowledge-building/)
  - 编程应被视为程序员形成或实现某种洞察力、理论的活动，与当前较为普遍的观点（即编程应被视为生成程序和某些其他文本的活动）形成对比。
  - 程序的构建等同于程序员团队构建其理论的过程。
- [认知负荷才是关键](https://minds.md/zakirullin/cognitive#long)
  - 一个精心设计的单体应用，如果模块真正隔离，通常比一堆微服务更加灵活。
  - 三十年过去了，基于微内核的GNU Hurd仍在开发中，而单体Linux无处不在。
  - “通过限制选择的数量来减少认知负荷。”（Rob Pike）
  - 这个规则适用于所有类型的数字状态（在数据库或任何地方）——优先使用自描述字符串。
  - 无论你在API中承诺了什么，只要有足够多的用户，所有可观察的行为都会被某人依赖。([Hyrum's Law](https://www.hyrumslaw.com/))
  - DDD是关于问题空间，而不是解决方案空间。
  - 熟悉并不等同于简单。
  - 要学习的心理模型越多，新开发人员交付价值所需的时间就越长。
- [CUPID：快乐编码](https://dannorth.net/blog/cupid-for-joyful-coding/)
  - 可组合：与其他组件良好协作
  - Unix哲学：做好一件事
  - 可预测：做你期望的事情
  - 符合习惯：感觉自然
  - 基于领域：解决方案领域在语言和结构上建模问题领域

> 你可以在设计图上使用橡皮擦，也可以在建筑工地使用大锤。（Frank Lloyd Wright）

资源：

- 🧰 [设计原则](https://principles.design/)

#### 设计：数据库模式

- [A humble guide to database schema design](https://www.mikealche.com/software-development/a-humble-guide-to-database-schema-design)，Mike Alche
  - 使用至少第三范式
  - 用约束建立最后一道防线
  - 永远不要将完整地址存储在一个字段中
  - 永远不要将名字和姓氏存储在同一个字段中
  - 建立表和字段名称的惯例。
- [YAGRI: You are gonna read it](https://www.scottantipa.com/yagri)：存储 `created_at`，`created_by` 等。

#### 设计：模式

- [KeystoneInterface](https://martinfowler.com/bliki/KeystoneInterface.html)，Martin Fowler。
  - 构建所有后端代码，集成，但不构建用户界面
- [101 Design Patterns & Tips for Developers](https://sourcemaking.com/design-patterns-and-tips)
- [Python Design Patterns: For Sleek And Fashionable Code](https://www.toptal.com/python/python-design-patterns): 对常见设计模式（Facade，Adapter，Decorator）的一个相当简单的介绍。Python 中设计模式实现的更完整列表在 [Github](https://github.com/faif/python-patterns)。
- SourceMaking 的 [Design Patterns](https://sourcemaking.com/design_patterns) 看起来也是一个不错的网络资源。
- [Anti-If: The missing patterns](https://code.joejag.com/2016/anti-if-the-missing-patterns.html)

#### 设计：简洁

- [Simple Made Easy](https://www.infoq.com/presentations/Simple-Made-Easy) 🎞, Rich Hickey。这是一场极其鼓舞人心的演讲，重新定义了简洁、易用性和复杂性，并展示了看似简单的解决方案实际上可能会损害你的设计。

### Dev environment & tools

- 🧰 [Awesome Dev Env](https://github.com/jondot/awesome-devenv)


- [Glances: An eye on your system](https://github.com/nicolargo/glances)
- [HTTPie: a CLI, cURL-like tool for humans](https://github.com/jkbrzt/httpie)
- [jq: command-line JSON processor](https://stedolan.github.io/jq/)
- [tmux: terminal multiplexer](http://tmux.github.io/)
- [htop: an interactive process viewer for Linux](http://hisham.hm/htop/)
- [htop explained](https://peteris.rocks/blog/htop/)
- [socat](https://copyconstruct.medium.com/socat-29453e9fc8a6)
- [Visual guide to SSH tunnels](https://robotmoon.com/ssh-tunnels/)
- [casey/just](https://github.com/casey/just/): a command runner written in Rust (claims to be better than Makefile)
- [Gazr](https://gazr.io/): an opinionated way to define your `Makefile`

Article about tools:

- [The return of fancy tools](https://macwright.com/2021/03/16/return-of-fancy-tools.html)
  - Simple tools make you think a little more
  - Drucker: "I’m not writing it down to remember it later, I’m writing it down to remember it now."
  - Frictionless note-taking produces notes, but it doesn't produce memory.

### Docker

另请参阅 [charlax/python-education](https://github.com/charlax/python-education#deployment) 中特定于 Python 的部分。

- [使用 Docker Compose 构建生产就绪的 Web 应用最佳实践](https://nickjanetakis.com/blog/best-practices-around-production-ready-web-apps-with-docker-compose)
  - 使用覆盖文件避免为开发和生产环境分别使用两个 Compose 文件
  - 使用别名和锚点减少服务重复
  - 在 Docker Compose 中定义 `HEALTHCHECK` 而不是在 Dockerfile 中定义
  - 充分利用环境变量
  - 使用多阶段构建优化镜像大小
  - 以非 root 用户身份运行容器
- [Python 开发者 Docker 最佳实践](https://testdriven.io/blog/docker-best-practices/)
  - 使用多阶段构建
  - 仔细注意 Dockerfile 命令的顺序以利用层缓存
  - 更小的 Docker 镜像更模块化和安全（注意 Alpine）
  - 最小化层数（`RUN`, `COPY`, `ADD`）
  - 使用非特权容器
  - 优先使用 `COPY` 而不是 `ADD`
  - 将 Python 包缓存到 Docker 主机
  - 优先使用数组而不是字符串语法
  - 理解 `ENTRYPOINT` 和 `CMD` 的区别
  - 包含 `HEALTHCHECK` 指令
  - 尽可能避免使用 `latest` 标签
  - 不要在镜像中存储秘密
  - 使用 `.dockerignore` 文件（包括 `**/.git` 等）
  - 对 Dockerfile 和镜像进行格式化和扫描（例如使用 `hadolint`）
  - 将日志记录到 stdout 或 stderr
- [Docker 容器安全](https://tbhaxor.com/docker-containers-security/)

### 文档

- [文档驱动开发](https://gist.github.com/zsup/9434452)
- [为你的文档编写自动化测试](https://krausefx.com/blog/writing-automated-tests-for-your-documentation): 我认为这应该是必须的。在文档中测试代码示例可以确保它们永远不会过时。
- 🏙 [文档是王道](https://speakerdeck.com/kennethreitz/documentation-is-king), Kenneth Reitz
- [保持一个变更日志](https://keepachangelog.com/en/1.0.0/)
- [架构决策记录 (ADR)](https://adr.github.io/): 一种记录架构决策的方法。
- [记录架构决策](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions)
- [joelparkerhenderson/architecture-decision-record](https://github.com/joelparkerhenderson/architecture-decision-record): ADR 的示例和模板。
  - 以及一个 CLI 工具: [npryce/adr-tools](https://github.com/npryce/adr-tools)
- [文档系统](https://documentation.divio.com/)
- [清单的清单](https://www1.nyc.gov/assets/doh/downloads/pdf/em/gawande_checklist.pdf)
- [编写代码注释的最佳实践](https://stackoverflow.blog/2021/12/23/best-practices-for-writing-code-comments/)
- [始终要辞职](https://jmmv.dev/2021/04/always-be-quitting.html)
  - 记录你的知识
  - 培训你的继任者
  - 委派
  - 通过让自己变得可替换，你可以自由地从事高影响力项目。
- [先写文档，再构建](https://reproof.app/blog/document-first-then-build)
- [Diátaxis](https://diataxis.fr/): 一种系统化的技术文档写作方法
  - 有四种模式：教程、如何操作指南、技术参考和解释
  - 文档详细介绍了每种模式。
- [ARCHITECTURE.md](https://matklad.github.io/2021/02/06/ARCHITECTURE.md.html)
- [两个具有出色文档的开源项目](https://johnjago.com/great-docs/) (esbuild 和 redis)
- [编写软件教程的规则](https://refactoringenglish.com/chapters/rules-for-software-tutorials/)

> 最淡的墨水比最强的记忆更可靠。
> -- 中国谚语

### Dotfiles

- 🧰 [Awesome dotfiles](https://github.com/webpro/awesome-dotfiles): lots of great dotfiles.
- [My dotfiles](https://github.com/charlax/dotfiles)

Articles

- [Setting Up a Mac Dev Machine From Zero to Hero With Dotfiles](http://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449)

### 编辑器与 IDE

- [Sublime Text 必备插件和资源](https://github.com/dreikanter/sublime-bookmarks)
- Bram Moolenaar（Vim 作者），[高效文本编辑的七个习惯](http://www.moolenaar.net/habits.html) ([演示文稿](http://www.moolenaar.net/habits_2007.pdf))。这是关于 Vim 的，但其中包含了一些关于为何投入时间学习如何使用文本编辑器提高效率的宝贵经验。
- [VScode](https://code.visualstudio.com/) 是目前最流行的文本编辑器之一。
  - [Visual Studio Code 能做到这些吗？](https://www.smashingmagazine.com/2018/01/visual-studio-code/)，Smashing Magazine。
- [有个性的编码](https://realdougwilson.com/writing/coding-with-character)

#### Vim

- 🧰 [vim-awesome](http://vimawesome.com/)
- 🎞 [Vimcasts](http://vimcasts.org/)
- ⭐️ [Is Vim Really Not For You? A Beginner Guide](https://thevaluable.dev/vim-beginner/)
  - The first part of a series of 6 articles with lots of detailed and practical tips for using Vim efficiently.
  - [A Vim Guide for Advanced Users](https://thevaluable.dev/vim-advanced/): more advanced shortcuts and commands
- 📖 [Learning the vi and Vim Editors](https://www.oreilly.com/library/view/learning-the-vi/9780596529833/)
- 📖 [Practical Vim](https://pragprog.com/titles/dnvim2/practical-vim-second-edition/), Drew Neil
- [Learn Vimscript the Hard Way](https://learnvimscriptthehardway.stevelosh.com/)
- [VimGolf](https://www.vimgolf.com/): nice challenges to learn Vim
- [Vim anti-patterns](https://blog.sanctum.geek.nz/vim-anti-patterns/)
- [Learn Vim For the Last Time: A Tutorial and Primer](https://danielmiessler.com/study/vim/)
- [Vim Cheat Sheet & Quick Reference](https://quickref.me/vim)
- [History and effective use of Vim](https://begriffs.com/posts/2019-07-19-history-use-vim.html)
- [Moving Blazingly Fast With The Core Vim Motions](https://www.barbarianmeetscoding.com/boost-your-coding-fu-with-vscode-and-vim/moving-blazingly-fast-with-the-core-vim-motions/)
- [micahkepe/vimtutor-sequel: Vimtutor Sequel - Advanced Vim Tutor Lessons](https://github.com/micahkepe/vimtutor-sequel)
- [Vim Racer - An Online Game for VIM Navigation](https://vim-racer.com/)

Feel free to check my [vim configuration](https://github.com/charlax/dotfiles/tree/master/vim) and my [vim cheatsheet](https://github.com/charlax/dotfiles/tree/master/vim).

Other editors:

- [Use GNU Emacs](https://www2.lib.uchicago.edu/keith/emacs/)

### 邮件

- [从第一性原理解释邮件](https://explained-from-first-principles.com/email/#json-meta-application-protocol)
- 🏙 [事务邮件最佳实践](https://speakerdeck.com/wildbit/transactional-email-best-practices)

### 工程管理

Checkout my [list of management resources](https://github.com/charlax/engineering-management).

### 练习

学习的最佳方式是通过实践来学习。

- [Reinvent the Wheel](https://endler.dev/2025/reinvent-the-wheel/)
- [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x): 一系列精心编写、逐步指导的教程，用于从零开始重新创建我们喜爱的技术
  - Richard Feynman: "我无法创造的东西，我不理解"
- [The elevator programming game](http://play.elevatorsaga.com/)
- [每个程序员都应该尝试的挑战性项目](https://austinhenley.com/blog/challengingprojects.html), Austin Z. Henley
- [每个程序员都应该尝试的挑战性项目](http://web.eecs.utk.edu/~azh/blog/challengingprojects.html): 文本编辑器，太空入侵者，编译器（Tiny Basic），微型操作系统，电子表格，视频游戏机模拟器。
- [每个程序员都应该尝试的更多挑战性项目](https://austinhenley.com/blog/morechallengingprojects.html): 光线追踪器，键值存储网络API，网络浏览器，股票交易机器人。
- [让我们构建一个正则表达式引擎](https://kean.blog/post/lets-build-regex)
- [从零开始编写一个时间序列数据库引擎](https://nakabonne.dev/posts/write-tsdb-from-scratch/)
- [构建7个GUI来学习基本的UI编程技能](https://eugenkiss.github.io/7guis/tasks/)
- [编程游乐场列表](https://jvns.ca/blog/2023/04/17/a-list-of-programming-playgrounds/), Julia Evans
- [编写更多“无用”的软件](https://ntietz.com/blog/write-more-useless-software/)
- [SadServers - Linux & DevOps 故障排除面试](https://sadservers.com/)
- [编写玩具软件是一种乐趣](https://blog.jsbarretto.com/post/software-is-joy)
- [Fly.io 分布式系统挑战“Gossip Glomers”](https://fly.io/dist-sys/)

练习：

- [CodinGame](https://www.codingame.com/start)
- [Codewars](https://www.codewars.com/)
- [Exercism](https://exercism.org/)

### 实验

- [8 个每个工程师都应该知道的烦人 A/B 测试错误](https://posthog.com/blog/ab-testing-mistakes)

### 函数式编程（FP）

- [告别面向对象编程](https://medium.com/@cscalfani/goodbye-object-oriented-programming-a59cda4c0e53#.39ax09e4k)
- [函数式编程与 Haskell](https://www.youtube.com/watch?v=LnX3B9oaKzw) 🎞：学习 FP 的一些好理由！
- [函数式编程基础](https://www.matthewgerstman.com/functional-programming-fundamentals/)：FP 及其优势的简要介绍。
- [面向对象 vs 函数式编程](https://blog.cleancoder.com/uncle-bob/2014/11/24/FPvsOO.html)，Robert C. Martin，《Clean Code Blog》。一位面向对象编程专家对 OOP 与 FP 差异的有趣观点。
  - 面向对象编程不是关于状态的。对象是函数的集合，而不是数据的集合。
  - 函数式程序，像面向对象程序一样，由操作数据的函数组成。
  - 函数式编程对赋值施加了纪律。
  - 面向对象编程对函数指针施加了纪律。
  - 无论你的编程风格如何，软件设计的原则仍然适用。你决定使用一种没有赋值操作符的语言，并不意味着你可以忽略单一职责原则。
- [解析，不要验证](https://lexi-lambda.github.io/blog/2019/11/05/parse-don-t-validate/)
  - 使用一种数据结构，使非法状态无法表示
  - 尽可能地将证明负担向上推，但不要更远
  - 让你的数据类型指导你的代码，而不是让代码控制数据类型
  - 不要害怕多次解析数据
  - 避免使用非规范化数据表示，特别是如果它是可变的
  - 使用抽象数据类型使验证器“看起来像”解析器
- 🏙 [函数式编程](https://speakerdeck.com/igstan/functional-programming)
- [15 分钟内掌握 Monad](https://nikgrozev.com/2013/12/10/monads-in-15-minutes/)
- [hemanth/functional-programming-jargon](https://github.com/hemanth/functional-programming-jargon)：用简单术语解释函数式编程领域的术语
- [学习函数式编程的终极指南](https://forum.exercism.org/t/the-definitive-guide-to-learning-functional-programming/3254)，Exercism

### 游戏开发

- [简介 · 小游戏开发的乐趣](https://abagames.github.io/joys-of-small-game-development-en/)

### 图形

- [Text Rendering Hates You](https://faultlore.com/blah/text-hates-you/)
- [AAA - Analytical Anti-Aliasing](https://blog.frost.kiwi/analytical-anti-aliasing/)

### 硬件

- [NandGame](https://nandgame.com/): 从零开始构建一台计算机。
- [What Every Programmer Should Know About SSDs](http://databasearchitects.blogspot.com/2021/06/what-every-programmer-should-know-about.html)
- [How To Make A CPU - A Simple Picture Based Explanation](https://blog.robertelder.org/how-to-make-a-cpu/)

### HTTP

- [Choosing an HTTP Status Code — Stop Making It Hard](https://www.codetinkerer.com/2015/12/04/choosing-an-http-status-code.html)
- [HTTPWTF](https://httptoolkit.tech/blog/http-wtf/)
- [10 Surprising Things You Didn't Know About HTTP](https://webdevguild.com/blog/10-things-http/)
- [The HTTP crash course nobody asked for](https://fasterthanli.me/articles/the-http-crash-course-nobody-asked-for)

### 幽默

- [The Jeff Dean Facts](https://www.informatika.bg/jeffdean)
  - 编译器不会警告 Jeff Dean。Jeff Dean 警告编译器。
  - 对常数时间不满意，Jeff Dean 创造了世界上第一个 `O(1/N)` 算法。
  - Jeff Dean 挖比特币。在他脑子里。
- [The Daily WTF: 信息技术中的奇特变态](https://thedailywtf.com/)

### 事件响应（值班、告警、停机、灭火、事后分析）

另请参阅我的[管理资源列表，“事件响应”](https://github.com/charlax/engineering-management/)部分。

另请参阅本文档中的调试部分。

- [Heroku 的事件响应](https://blog.heroku.com/archives/2014/5/9/incident-response-at-heroku)
  - 描述了事件指挥官角色，灵感来源于自然灾害事件响应。
  - 在演示中也有：[事件响应模式：我们在 PagerDuty 学到的经验 - Speaker Deck](https://speakerdeck.com/arupchak/incident-response-patterns-what-we-have-learned-at-pagerduty)
- Google SRE 书籍中关于[值班](https://landing.google.com/sre/workbook/chapters/on-call/)的章节
- [当你是 SRE 时如何编写运行手册文档](https://www.transposit.com/blog/2020.01.30-writing-runbook-documentation-when-youre-an-sre/)
  - 流程手册“可以减少压力、平均修复时间（MTTR）和人为错误的风险。”
  - 使用模板是有益的，因为从空白文档开始是非常困难的。
  - 知识诅咒是一种认知偏差，当某人与他人沟通时，会无意识地假设沟通对象所具备的知识水平。
  - 使内容易于快速浏览。
  - 如果脚本超过一行，应将其视为代码，并将其提交到仓库中进行源代码控制和潜在测试。
- [事件回顾和事后分析最佳实践](https://newsletter.pragmaticengineer.com/p/incident-review-best-practices?s=r)，Gergely Orosz
- [计算机安全事件处理指南](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf)，NIST
- [事件管理资源](https://resources.sei.cmu.edu/library/asset-view.cfm?assetID=505044)，卡内基梅隆大学
- [无菌驾驶舱规则](https://en.wikipedia.org/wiki/Sterile_flight_deck_rule)，维基百科
- [Shamir 秘密共享，现在是凌晨 3 点。](https://max.levch.in/post/724289457144070144/shamir-secret-sharing-its-3am-paul-the-head-of)
- [站点可靠性工程与即兴创作的艺术](https://thenewstack.io/site-reliability-engineering-and-the-art-of-improvisation/)包含许多优秀的培训想法
  - 可观测性工具集的演练
  - 决策需求表的构建
  - 团队知识的提取
  - 提出问题，“为什么要有值班？”
  - 转动专家轮盘！
- [严重级别](https://response.pagerduty.com/before/severity_levels/)，PagerDuty

告警：

- [我对告警的哲学](https://linuxczar.net/sysadmin/philosophy-on-alerting/)
  - 告警页面应是紧急、重要、可操作且真实的。
  - 在去除嘈杂告警方面应采取谨慎态度——过度监控比监控不足更难解决。
  - 症状是更全面、更稳健地捕捉更多问题的一种更有效的方式。
  - 在基于症状的页面或仪表板中包含基于原因的信息，但避免直接对原因进行告警。
  - 你越往上层服务栈，单个规则中能捕捉到的独立问题就越多。但不要走得太远，以至于无法充分区分正在发生的事情。
  - 如果你想要一个安静的值班轮班，必须有一个系统来处理那些需要及时响应但并非迫在眉睫的问题。
  - 这篇经典文章现已成为 Google SRE 书籍中的一章：[监控分布式系统](https://sre.google/sre-book/monitoring-distributed-systems/)。
- 🏙 [告警的悖论](https://speakerdeck.com/charity/the-paradox-of-alerts)：为什么删除 90% 的告警页面可以让你的系统变得更好，以及如何制定工程师乐于加入的值班轮班。

#### 事后分析

- 一个很好的[事后分析示例（2017年1月31日）](https://about.gitlab.com/2017/02/01/gitlab-dot-com-database-incident/)，描述了一次由于工程师的操作导致6小时数据不可挽回丢失的停机事件。
- [无责事后分析与公正文化](https://codeascraft.com/2012/05/22/blameless-postmortems/)
- [GitHub上的事后分析列表](https://github.com/danluu/post-mortems)
- Google的SRE书籍，[事后分析章节](https://landing.google.com/sre/workbook/chapters/postmortem-culture/)非常出色，包含了许多示例。
- [人为错误模型与管理](https://app.box.com/s/7z35l09amvr1vwxouh2s)
  - 高可靠性组织——这些组织的事故数量少于其应有水平——认识到人为变异性是一种可以利用以避免错误的力量，但它们努力集中这种变异性，并始终关注失败的可能性

> "让我们为一个未来做计划，在这个未来中，我们所有人都和今天一样愚蠢。"
>
> – Dan Milstein

事后分析示例大纲：

- 执行摘要
  - 影响
  - 根本原因
- 影响
  - 受影响的用户数量
  - 丢失的收入
  - 持续时间
  - 团队影响
- 时间线
  - 检测
  - 解决
- 根本原因分析
  - 例如使用5个为什么方法
- 学到的经验
  - 做得好的地方
  - 做得不好的地方
- 待办事项（包含直接链接到任务跟踪工具）
  - 用于改进预防的任务（包括培训）
  - 用于改进检测的任务（包括监控和告警）
  - 用于改进缓解的任务（包括应急响应）

### 互联网

- [互联网是如何运作的？](https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm)
- [网络是如何运作的](https://github.com/vasanthk/how-web-works)
- [给年轻网络开发者的建议](https://beesbuzz.biz/blog/2934-Advice-to-young-web-developers)

### 面试

注意：这是关于你作为面试者，**不是**作为面试官。要查看我为面试官准备的资源列表，请前往我的 [工程管理仓库](https://github.com/charlax/engineering-management#hiring-interviews)。

- [IT公司系统设计面试](https://github.com/checkcheckzz/system-design-interview)
- [技术面试巨库](https://github.com/jdsutton/Technical-Interview-Megarepo)：软件工程/计算机科学技术面试学习材料
- [如何赢得编码面试](https://medium.com/on-writing-code/how-to-win-the-coding-interview-71ae7102d685)
- [我参加完编码训练营后花了三个月申请工作。这是我学到的东西。](https://medium.freecodecamp.com/5-key-learnings-from-the-post-bootcamp-job-search-9a07468d2331#.uq7vbbjfx)
- [面试问题中的十大算法](http://www.geeksforgeeks.org/top-10-algorithms-in-interview-questions/)
- [交互式Python编码面试挑战](https://github.com/donnemartin/interactive-coding-challenges)
- [技术面试手册](https://www.techinterviewhandbook.org/)
- [成为软件工程师的完整计算机科学学习计划](https://github.com/jwasham/coding-interview-university)
- [获得Google、Microsoft和Stripe工作机会的面试建议](https://www.zainrizvi.io/blog/the-interviewing-advice-no-one-shares/)
- [评估你在编程面试问题中表现的框架](https://docs.google.com/spreadsheets/d/1gy9cmPwNhZvola7kqnfY3DElk7PYrz2ARpaCODTp8Go/htmlview?pru=AAABfLx5bfQ*dDBm6wJC2BsJGIrDvJfFQw)
- [为系统设计和编码面试做准备](https://blog.pragmaticengineer.com/preparing-for-the-systems-design-and-coding-interviews/), Gergely Orosz
- [在30天内完成60多个技术面试后我学到的东西](https://meekg33k.dev/what-i-learned-from-doing-60-technical-interviews-in-30-days)
- [高级工程师的系统设计面试指南](https://interviewing.io/guides/system-design-interview), interviewing.io

你应该提出的问题：

- [向面试官提出的问题](https://rkoutnik.com/articles/Questions-to-ask-your-interviewer.html)
- [面试期间向公司提出的问题](https://github.com/viraptor/reverse-interview)
- [面试面试官：提出问题以揭示公司的真正文化](https://praachi.work/blog/questions-to-ask-in-a-job-interview)
- [Twipped/InterviewThis](https://github.com/Twipped/InterviewThis)：向潜在雇主提出的问题
- [tBaxter/questions-for-employers: 一组有用的向潜在雇主提出的问题的集合。](https://github.com/tBaxter/questions-for-employers)

简历：

- [简历上的红旗](https://danicfilip.com/2020/red-flags-on-your-resume/?ck_subscriber_id=887770473)
- [我们在简历中寻找的内容](https://huyenchip.com/2023/01/24/what-we-look-for-in-a-candidate.html)
  - 我们寻找的是展示出的专业知识，而不是关键词
  - 我们寻找的是能够完成任务的人
  - 我们寻找的是独特的视角
  - 我们关注的是影响，而不是无意义的指标
- [为什么你不应该在LinkedIn上列出证书](https://interviewing.io/blog/why-you-shouldnt-list-certifications-on-linkedIn)

另请参阅本文档中的练习部分。

### Kubernetes

- [OWASP/www-project-kubernetes-top-ten](https://github.com/OWASP/www-project-kubernetes-top-ten)
- [Kubernetes Tutorial for Beginners: Basic Concepts](https://spacelift.io/blog/kubernetes-tutorial)

### 大型语言模型（LLM）

- [What Is ChatGPT Doing… and Why Does It Work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/), Stephen Wolfram
- [Embeddings: What they are and why they matter](https://simonwillison.net/2023/Oct/23/embeddings/)

### 学习与记忆

学习如何学习！

- [How I Rewired My Brain to Become Fluent in Math](https://nautil.us/how-i-rewired-my-brain-to-become-fluent-in-math-235085): 副标题 _理解的构建块是记忆和重复_。
- [One Sure-Fire Way to Improve Your Coding](https://changelog.com/posts/one-sure-fire-way-to-improve-your-coding): 阅读代码！
- [Tips for learning programming](http://blog.hiphipjorge.com/tips-for-learning-programming/)
- [You can increase your intelligence: 5 ways to maximize your cognitive potential](https://blogs.scientificamerican.com/guest-blog/you-can-increase-your-intelligence-5-ways-to-maximize-your-cognitive-potential/): 原谅这个标题有点点击诱饵，但其实是一篇好文章。
- [How to ask good questions](https://jvns.ca/blog/good-questions/), Julia Evans.
- [Stop Learning Frameworks](https://sizovs.net/2018/12/17/stop-learning-frameworks/)
- [Learning How to Learn](https://www.coursera.org/learn/learning-how-to-learn): 强大的心理工具，帮助你掌握困难的科目
- [Why books don’t work](https://andymatuschak.org/books/), Andy Matuschak.
  - "作为一种媒介，书籍在传达知识方面出人意料地差，而读者大多没有意识到这一点。"
  - "在学习科学中，我们称这种模型为“传授主义”。这是知识可以从教师直接传授给学生的概念，就像从一页纸转录到另一页纸一样。如果真能如此就好了！"
  - "通过在逐渐延长的时间间隔内对已学习的材料进行自我测试，你可以廉价且可靠地将大量信息长期记忆下来。"
- [Strategies, Tips, and Tricks for Anki](https://senrigan.io/blog/everything-i-know-strategies-tips-and-tricks-for-spaced-repetition-anki/): 这些建议对任何工具都有效
  - 添加图片。我们的大脑是视觉导向的，这有助于记忆。
  - 不要添加你不理解的东西。
  - 不要添加记忆整个列表的卡片。
  - 写下来。对于错误答案，我会写在纸上。写作是一种冥想。我真的很喜欢这个。
  - 不断问自己为什么？为什么这有效？为什么它这样有效？强迫自己理解一个主题的根源。
  - 康奈尔方法：阅读一个主题时，在页边写下问题来测试自己。
  - 假设你必须教它
  - 使用记忆短语，如PEMDAS用于列表和其他难以记忆的主题。
  - 删除没有意义或你不想再记住的卡片。
- [Effective learning: Twenty rules of formulating knowledge](https://www.supermemo.com/en/archives1990-2015/articles/20rules)
  - 建立在基础之上
  - 坚持最小信息原则：你学习的材料必须以尽可能简单的方式表述
  - 空缺删除是简单且有效的：Kaleida的使命是创建一个...它最终生产了一个，叫做Script X。但花了三年时间
  - 图形删除与空缺删除一样有效
  - 避免集合
  - 避免列举
  - 消除干扰 - 即使是最简单的项目，如果它们与其他项目相似，也可能完全难以处理。使用例子、上下文提示、生动的插图、参考情感和你的个人生活
  - 个性化并提供例子 - 个性化可能是建立在其他记忆之上的最有效方式。你的个人生活是事实和事件的金矿，可以用来参考。只要你为自己建立一个收藏，就充分利用个性化来建立在已建立的记忆之上
  - 提供来源 - 来源有助于你管理学习过程，更新你的知识，判断其可靠性或重要性
  - 优先级 - 有效的学习都是关于优先级的。
- [How to Remember Anything You Really Want to Remember, Backed by Science](https://www.inc.com/jeff-haden/how-to-remember-anything-you-really-want-to-remember-backed-by-science.html)
  - 自我测试
  - 总结并与其他人分享。
  - 将你刚学到的内容与你之前经历的联系起来。
- [How To Remember Anything Forever-ish](https://ncase.me/remember/): 一个关于学习的漫画
- [Get better at programming by learning how things work](https://jvns.ca/blog/learn-how-things-work/)
- [How to teach yourself hard things](https://jvns.ca/blog/2018/09/01/learning-skills-you-can-practice/)
- [Building Your Own Personal Learning Curriculum](https://www.smashingmagazine.com/2021/02/building-personal-learning-curriculum/)
- [Always do Extra](http://www.bennorthrop.com/Essays/2021/always-do-extra.php)
  - 额外是指完成那两屏，然后研究一个用于表单验证的新库，可能会减少样板代码。
  - 额外必须与正常工作平衡。
  - 额外必须与你的正常工作一致。
- [Against 3X Speed](https://perell.com/essay/against-3x-speed/)
  - 讲座在课堂体验中只是其中的一部分时最有效
  - 学习是关于间隔重复，而不是一次性读完书
- [The Problems with Deliberate Practice](https://commoncog.com/blog/the-problems-with-deliberate-practice/)
- [Why Tacit Knowledge is More Important Than Deliberate Practice](https://commoncog.com/tacit-knowledge-is-a-real-thing/)
- [In Praise of Memorization](http://www.pearlleff.com/in-praise-of-memorization)
  - 没有知识你就无法准确推理
  - 记忆可以组织你的知识
  - 它会一直留在你脑海里
- [Celebrate tiny learning milestones](https://jvns.ca/blog/2022/03/13/celebrate-tiny-learning-milestones/), Julia Evans.
  - 保持一个吹嘘文档 ([让你的工作被认可：写一份吹嘘文档](https://jvns.ca/blog/brag-documents/))
  - 你可以通过“意外”学到很多
  - 修复一个错误可以是一个里程碑
- [Why writing by hand is still the best way to retain information](https://stackoverflow.blog/2022/11/23/why-writing-by-hand-is-still-the-best-way-to-retain-information/), StackOverflow
- 🎞 [Making Badass Developers - Kathy Sierra (Serious Pony) keynote](https://www.youtube.com/watch?v=FKTxC9pl-WM&t=2s&ab_channel=O%27Reilly)
- [How to study](https://cse.buffalo.edu/~rapaport/howtostudy.html) （包含大量卡尔文与霍布斯的漫画！）
  - 管理你的时间
  - 在课堂上做笔记并在家里重写它们
  - 先学习难的科目并在安静的地方学习
  - 主动且缓慢地阅读，在上课前后阅读
  - 做作业
  - 为考试学习
  - 参加考试
  - 做研究并写论文
  - 我真的必须做所有这些吗？
  - 是否有其他网站提供学习提示？
- [10 Things Software Developers Should Learn about Learning](https://cacm.acm.org/research/10-things-software-developers-should-learn-about-learning/)
- 🏙 [Things I Learned the Hard Way](https://speakerdeck.com/bcantrill/things-i-learned-the-hard-way), Bryan Cantrill

关于卡片：

- [Augmenting Long-term Memory](http://augmentingcognition.com/ltm.html)
- [How to write good prompts: using spaced repetition to create understanding](https://andymatuschak.org/prompts/) - 还包括许多有洞察力的研究论文。
- [Effective learning: Twenty rules of formulating knowledge](https://www.supermemo.com/en/blog/twenty-rules-of-formulating-knowledge)
- [Rules for Designing Precise Anki Cards](https://controlaltbackspace.org/precise/)
- Fernando Borretti, [Effective Spaced Repetition](https://borretti.me/article/effective-spaced-repetition)
- [Anki-fy Your Life](https://abouttolearn.substack.com/p/anki-fy-your-life) 说明为什么投资你的记忆是有道理的。

关于Zettelkasten和PKM（个人知识管理）：参见 [Personal knowledge management](#personal-knowledge-management-pkm)

理查德·费曼的学习策略：

1. 第一步：不断问“为什么？”
2. 第二步：当你学习某样东西时，要学到能向一个孩子解释的程度。
3. 第三步：不要随意记忆东西，而是寻找让其变得显而易见的解释。

> 大多数人高估了他们在一年内能做的事情，低估了他们在十年内能做的事情。
> – 比尔·盖茨

> 说实话，我认为大多数人可以学到比他们以为的更多。他们没有尝试就低估了自己。
> 一点建议：将知识视为某种语义树很重要——确保你理解基本原理，即树干和大枝，然后再进入细节/叶子，否则他们就没有可以依靠的东西。
> —— 埃隆·马斯克

> “经验是当你需要它时才得到的东西。”
> —— 斯蒂文·赖特

> 告诉我，我会忘记。教我，我会记住。让我参与，我会学习。
> – 本杰明·富兰克林

> 教育是点燃火焰，而不是装满容器。
> – 苏格拉底

> 我们坚持做的事情会变得更容易做；不是因为事情本身的性质发生了变化，而是因为我们的能力增强了。
> – 拉尔夫·瓦尔多·爱默生

> 一个聪明的人可以从一个愚蠢的问题中学到比一个愚蠢的人从一个聪明的答案中学到的更多。
> – 李小龙

> 有人曾很好地描述过讲座：这是一个过程，教师的笔记变成学生的笔记，而没有经过任何一方的头脑。
> —— 玛尔蒂默·阿德勒

> 愚人从经验中学习。我更喜欢从他人的经验中学习。
> —— 俾斯麦

### Licenses (legal)

- [Software Licenses in Plain English](https://tldrlegal.com/)

### Linux (系统管理)

- [欢迎使用 Linux 命令行，你和我！](https://lym.readthedocs.io/en/latest/index.html)
- [Linux 性能](https://www.brendangregg.com/linuxperf.html), Brendan Gregg
- [Linux 磁盘 I/O 图表](https://zenodo.org/records/15234151)

### 低代码/无代码

- [Levels.fyi 如何使用 Google Sheets 作为后端扩展到数百万用户](https://www.levels.fyi/blog/scaling-to-millions-with-google-sheets.html)

### 低级，汇编

- [回到基础](https://www.joelonsoftware.com/2001/12/11/back-to-basics/), Joel Spolsky。解释为什么学习低级编程很重要。
  - 我认为即使在最高架构层面，人们所犯的一些最大错误都来自于对最低级别的一些简单事物理解薄弱或错误。
- [Linux 可执行文件中有什么？](https://fasterthanli.me/series/making-our-own-executable-packer/part-1)
- 📖 [计算机系统要素](https://www.nand2tetris.org/book)：从第一原理构建现代计算机（nand2tetris）。
- [旧模式驱动现代技术](https://softwarebits.substack.com/p/old-pattern-powering-modern-tech?s=r)
- [解密位运算，一个温和的 C 教程](https://www.andreinc.net/2023/02/01/demystifying-bitwise-ops)
- [理解位运算符的力量。不需要数学](https://www.deusinmachina.net/p/understanding-the-power-of-bitwise)
- [内存分配](https://samwho.dev/memory-allocation/)（一篇交互式文章）
- [为什么 0.1 + 0.2 = 0.30000000000000004？](https://jvns.ca/blog/2023/02/08/why-does-0-1-plus-0-2-equal-0-30000000000000004/), Julia Evans（关于浮点数）
- [将 "You" 放入 CPU](https://cpu.land/the-basics)
- [使用 Ubuntu 进行 x86-64 汇编语言编程](http://www.egr.unlv.edu/~ed/assembly64.pdf)
- [XOR](https://www.chiark.greenend.org.uk/~sgtatham/quasiblog/xor/)

### 机器学习/人工智能

- [从零开始构建Transformer](https://e2eml.school/transformers.html)
- [图神经网络简介](https://distill.pub/2021/gnn-intro/)

### 数学

- 🏙 [Hackers 的统计学](https://speakerdeck.com/jakevdp/statistics-for-hackers)

### 营销

- [goabstract/Marketing-for-Engineers](https://github.com/goabstract/Marketing-for-Engineers)

### 网络

- [关于 DNS 的一切你需要知道](https://www.nslookup.io/learning/)
- [计算机网络基础](https://iximiuz.com/en/series/computer-networking-fundamentals/)

### 可观测性（监控、日志、异常处理）

另请参阅：[站点可靠性工程（SRE）](#site-reliability-engineering-sre)

#### 日志记录

- [不要记录日志](https://sobolevn.me/2020/03/do-not-log) 介绍了一些日志记录的反模式。
  - 在监控和错误跟踪中记录日志没有太多意义。使用更好的工具：带有警报、版本控制、事件溯源的错误和业务监控。
  - 日志记录会显著增加架构的复杂性。并且需要更多的测试。使用架构模式，使日志记录成为合同的显式部分。
  - 日志记录是一个独立的基础设施子系统。并且相当复杂。你将不得不维护它，或者将这项工作外包给现有的日志服务。
- [我父母告诉我的关于日志的谎言](https://www.honeycomb.io/blog/lies-my-parents-told-me-about-logs/)
  - 日志是便宜的
  - 我可以自己运行得更好
  - 分层日志是分离信息的好方法
  - 日志基本上与事件相同
  - 标准日志格式就足够好了
- [日志记录 - OWASP 常见错误防范指南系列](https://cheatsheetseries.owasp.org/cheatsheets/Logging_Cheat_Sheet.html)
- [审计日志的耻辱墙](https://audit-logs.tax/)：列出不优先为安全和运维团队提供高质量、广泛可用的审计日志的供应商。
- [结构化日志指南](https://signoz.io/blog/structured-logs/)

#### 错误/异常处理

- 本仓库中的 [错误处理反模式](.././antipatterns/error-handling-antipatterns.md)。
- [编写有用的错误信息](https://developers.google.com/tech-writing/error-messages)，Google 开发者的技术写作课程
  - 解释问题
  - 解释解决方案
  - 清晰表达
- [错误无处不在：我们如何集中和结构化错误处理](https://olivernguyen.io/w/namespace.error/)（针对 Go，但对任何语言都有用）
- 获取灵感：[处理错误 - 图形 API](https://developers.facebook.com/docs/graph-api/guides/error-handling#receiving-errorcodes)

#### 指标

- [Meaningful availability](https://blog.acolyer.org/2020/02/26/meaningful-availability/)
  - 一个好的可用性指标应该是有意义的、成比例的和可操作的。"有意义"意味着它应该捕捉用户所体验到的内容。"成比例"意味着指标的变化应该与用户感知到的可用性变化成比例。"可操作"意味着该指标应该为系统所有者提供关于为何某一时期可用性较低的洞察。这篇论文表明，常用的任何指标都无法满足这些要求…
- 📃 [Meaningful Availability](https://www.usenix.org/conference/nsdi20/presentation/hauer) 论文。
  - 这篇论文提出并评估了一种新的可用性指标：窗口用户运行时间

#### 监控

- Google, [Site Reliability Engineering, Monitoring Distributed Systems](https://landing.google.com/sre/sre-book/chapters/monitoring-distributed-systems/)
  - [Alerting on SLOs](https://sre.google/workbook/alerting-on-slos/)
- PagerDuty, [Monitoring Business Metrics and Refining Outage Response](https://www.pagerduty.com/blog/monitoring-business-metrics/)
- 🧰 [crazy-canux/awesome-monitoring](https://github.com/crazy-canux/awesome-monitoring): monitoring tools for operations.
- [Monitoring in the time of Cloud Native](https://medium.com/@copyconstruct/monitoring-in-the-time-of-cloud-native-c87c7a5bfa3e)
- [How to Monitor the SRE Golden Signals](https://medium.com/faun/how-to-monitor-the-sre-golden-signals-1391cadc7524)
  - From the Google SRE book: Latency, Traffic, Errors, and Saturation
  - USE Method (from Brendan Gregg): Utilization, Saturation, and Errors
  - RED Method (from Tom Wilkie): Rate, Errors, and Duration
- [Simple Anomaly Detection Using Plain SQL](https://hakibenita.com/sql-anomaly-detection)
- [How percentile approximation works (and why it's more useful than averages)](https://www.timescale.com/blog/how-percentile-approximation-works-and-why-its-more-useful-than-averages/)
- [Implementing health checks](https://aws.amazon.com/builders-library/implementing-health-checks/)
- [IETF RFC Health Check Response Format for HTTP APIs](https://datatracker.ietf.org/doc/html/draft-inadarei-api-health-check-06)

### 开源

- [非代码贡献是开源成功的秘诀](https://github.com/readme/featured/open-source-non-code-contributions)

### 操作系统（OS）

- 📖 [The Linux Programming Interface: A Linux and UNIX System Programming Handbook](http://www.amazon.com/The-Linux-Programming-Interface-Handbook/dp/1593272200): 已经在上面提到过。
- 📖 [Modern Operating Systems](https://www.amazon.com/dp/013359162X/), Andrew Tanenbaum, Herbert Bos（未阅读）
- 📖 [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/)（免费书籍，未阅读）
- 📖 [Linux Kernel Development](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468), Robert Love。对在Linux内核中开发的非常完整的介绍。
- [Software Developers Need to Remember](https://jameskle.com/writes/operating-systems)
- 在 [MIT 6.828](https://pdos.csail.mit.edu/6.828/2016/schedule.html) 上玩 xv6
- [macOS Internals](https://gist.github.com/kconner/cff08fe3e0bb857ea33b47d965b3e19f)

### 过度设计

- [10 个现代软件过度设计的错误](https://medium.com/@rdsubhas/10-modern-software-engineering-mistakes-bc67fbef4fc8#.da6dvzyne)
- [过度设计的一个好例子：Juicero 压榨机](https://blog.bolt.io/heres-why-juicero-s-press-is-so-expensive-6add74594e50) (2017 年 4 月)
- [你不是 Google](https://blog.bradfieldcs.com/you-are-not-google-84912cf44afb): 使用 UNPHAT 方法避免盲目崇拜。
  - 在你理解问题之前，不要开始考虑解决方案。你的目标应该是“解决”问题，主要在问题领域内，而不是解决方案领域。
  - 列举多个候选解决方案。不要一开始就只关注你最喜欢的方案！
- [过度思考](https://kerkour.com/overthinking)
  - 第一种毒药：教育。
  - 第二种毒药：营销。
  - 第三种毒药：自我
  - 解决方案：不要试图提前把所有点都连接起来。接受不确定性并开始行动。
- [不要让架构宇航员吓到你](https://www.joelonsoftware.com/2001/04/21/dont-let-architecture-astronauts-scare-you/), Joel
  - 有时聪明的思考者只是不知道何时停止，他们创造出这些荒谬的、包罗万象的、高层次的宇宙图景，虽然看起来很好，但实际上毫无意义。
  - 一个典型的架构宇航员会拿一个事实，比如“Napster 是一个用于下载音乐的点对点服务”，然后忽略除了架构之外的一切，认为它有趣是因为它是点对点的，完全忽略了它之所以有趣是因为你可以直接输入歌曲名称并立即收听。

> “一个复杂系统如果有效，总是被发现是从一个有效简单的系统演化而来的。从头开始设计的复杂系统永远无法正常工作，也无法通过修补使其正常工作。你必须从头开始，从一个有效的简单系统开始。”

— John Gall, 《General systemantics》，一篇关于系统如何运作，尤其是如何失败的论文，1975 年（这句引言有时被称为“Gall 的定律”）

> “软件工程是当编程加入了时间和其他程序员之后发生的事情。”

— Rob Pike, [Google 的 Go 语言：服务于软件工程的语言设计](https://talks.golang.org/2012/splash.article)

> 你无法向前看时连接这些点；你只能在回顾时连接它们。因此，你必须相信这些点在你的未来会以某种方式连接。你必须相信某些东西——你的直觉、命运、生活、业力，无论是什么。这种方法从未让我失望，它在我的生活中产生了巨大的不同。

— Steve Jobs

### 性能

- [Everyone Should Know Numbers](https://everythingisdata.wordpress.com/2009/10/17/numbers-everyone-should-know/)
- [Latency numbers every programmer should know](https://gist.github.com/hellerbarde/2843375)
- [Rob Pike's 5 Rules of Programming](http://users.ece.utexas.edu/~adnan/pike.html)
  - 你无法预知程序的时间消耗点在哪里。
  - 测量
  - 当 n 很小时，复杂的算法效率低，而 n 通常都很小。
  - 复杂的算法比简单的算法更容易出错
  - 数据占主导地位。
- [Performance comparison: counting words in Python, Go, C++, C, AWK, Forth, and Rust](https://benhoyt.com/writings/count-words/): 学习如何衡量性能的绝佳方式。
- [The Mathematical Hacker](https://www.evanmiller.org/mathematical-hacker.html)
- [Four Kinds of Optimisation](https://tratt.net/laurie/blog/2023/four_kinds_of_optimisation.html)

### 个人知识管理（PKM）

- [Zettelkasten 方法](https://zettelkasten.de/posts/overview/)
- [如何作为软件开发人员构建第二个大脑](https://aseemthakar.com/how-to-build-a-second-brain-as-a-software-developer/)
- [关于笔记记录系统的笔记](https://sashachapin.substack.com/p/notes-against-note-taking-systems)
  - 一个有趣的反主流观点！
  - 我在等待任何证据表明我们最具有挑衅性的思想家和作家是那些依赖复杂、系统化笔记记录系统的人。
  - 我看到的证据是那些为了知识管理本身而被教导的人产生了乏味的作品。
- [MaggieAppleton/digital-gardeners](https://github.com/MaggieAppleton/digital-gardeners)
- [笔记应用是想法去死的地方。而这是一件好事。](https://www.reproof.app/blog/notes-apps-help-us-forget)
- [我删除了我的第二个大脑](https://www.joanwestenberg.com/p/i-deleted-my-second-brain)

### 个人效率

查看我关于[管理资源列表，"个人效率"](https://github.com/charlax/engineering-management/#personal-productivity)的这一部分。

### Perspective

- [31岁，我只剩几周可活。这是我想要传递的](https://www.theguardian.com/commentisfree/2020/sep/07/terminal-cancer-live-cancer-life-death)
  - 首先，感恩的重要性。
  - 其次，如果生活得很好，生命就足够长。
  - 第三，让自己脆弱并与其他人的连接很重要。
  - 第四，为他人做些事情。
  - 第五，保护地球。
- [生命并不短暂](https://dkb.show/post/life-is-not-short)
  - “最令人惊讶的是，你不会让任何人偷走你的财产，但你却一直让别人偷走你的时间，而时间的价值是无限的。” — 塞涅卡

### 隐私

- [隐私增强技术：技术人员的入门指南](https://martinfowler.com/articles/intro-pet.html)，Katharine Jarmul，MartinFowler.com

### 问题解决

- [处理难题](https://artofproblemsolving.com/articles/hard-problems)
- [反转，始终反转](https://www.anup.io/2020/07/20/invert-always-invert/)
  - 定义问题 - 你试图实现的是什么？
  - 反转它 - 什么会保证无法实现这一结果？
  - 最后，考虑避免这种失败的解决方案
- 🎞 [吊床驱动开发](https://www.youtube.com/watch?v=f84n5oFoZBc&ab_channel=ClojureTV)，Rick Hickey
  - 有关问题解决的经典演讲。

### 软件工程师的产品管理

参见我的创业资源列表中的[产品管理部分](https://github.com/charlax/entrepreneurship-resources#product-management)。

- 查看 Posthog 出版的这封时事通讯：[Product for Engineers](https://newsletter.posthog.com/)

### 项目管理

参见[我的工程管理资源列表中的项目管理部分](https://github.com/charlax/engineering-management#project-management)。

### 编程语言

我建议学习：

- JavaScript 和另一种解释型语言（Python、Ruby 等）。解释型语言适用于快速的一次性自动化脚本，并且在面试中编写速度最快。JavaScript 无处不在。
- 一种编译型语言（Java、C、C++ 等）。
  - [Y 分钟内学习 C](https://learnxinyminutes.com/docs/c/)
- 一种较新的语言，以了解行业的发展方向（截至撰写时，Go、Swift、Rust、Elixir 等）。
- 一种对函数式编程有原生支持的语言（Haskell、Scala、Clojure 等）。

更多阅读内容：

- [编程语言的简短、不完整、大部分错误的历史](http://james-iry.blogspot.fr/2009/05/brief-incomplete-and-mostly-wrong.html)
- [类型](https://gist.github.com/garybernhardt/122909856b570c5c457a6cd674795a9c)
- [帮助你创建编程语言的资源](https://tomassetti.me/resources-create-programming-languages/)
- [有效程序 - 10 年 Clojure 经历](https://www.youtube.com/watch?v=2V1FtfBDsLU) 🎞, Rich Hickey。Clojure 的作者反思了他的编程经验，并解释了 Clojure 一些关键设计决策背后的理由。
- [即使你不会使用它们，也要学习更多的编程语言](https://thorstenball.com/blog/2019/04/09/learn-more-programming-languages/), Thorsten Ball
  - 这些新的视角、这些想法和模式 —— 它们会留下，即使你最终使用另一种语言。这足以让你继续学习新的语言，因为当你试图解决问题时，视角的改变可能是对你最有益的事情之一。
- [编程语言检查清单](https://famicol.in/language_checklist.html)：对“你想构建自己的语言吗？”的一种有趣看法。
- [静态语言与动态语言：文献综述](http://danluu.com/empirical-pl/)
- [多语言编程与掌握多种语言的好处](https://www.stxnext.com/blog/polyglot-programming/)
- [不是编程语言做了什么，而是它们引导你去做了什么](https://nibblestew.blogspot.com/2020/03/its-not-what-programming-languages-do.html)
- [Ask HN：学习新语言/框架时你编写什么代码？](https://news.ycombinator.com/item?id=32092943)
- [七种编程原始语言](https://madhadron.com/programming/seven_ur_languages.html)：ALGOL、Lisp、ML、Self、Forth、APL、Prolog
- [Lua：那个能够做到的小语言](https://matt.blwt.io/post/lua-the-little-language-that-could/)
- [蒙特利尔效应：为什么编程语言需要一个风格总管](https://earthly.dev/blog/language-style-czar/)
- [TodePond/DreamBerd：一种完美的编程语言](https://github.com/TodePond/DreamBerd)
- [让我大开眼界的编程语言](https://yoric.github.io/post/programming-languages-that-blew-my-mind/)

> 只有两种类型的编程语言：人们抱怨的那些和没人使用的那些。

-- Bjarne Stroustrup（C++ 创造者）

资源列表：

- [编程语言中的伟大作品](https://www.cis.upenn.edu/~bcpierce/courses/670Fall04/GreatWorksInPL.shtml)

#### Python

对于 Python，请查看我的 [专业 Python 教育仓库](https://github.com/charlax/python-education)。

#### JavaScript

在此仓库中：查看 [./training/front-end/](.././training/front-end/)

JavaScript 是一种如此普遍的语言，以至于几乎成为必学内容。

- [mbeaudru/modern-js-cheatsheet](https://github.com/mbeaudru/modern-js-cheatsheet): 用于现代项目中频繁遇到的 JavaScript 知识的速查表。
- [javascript-tutorial](https://github.com/javascript-tutorial): 详尽的 JavaScript 指南，配有简单但详细的解释。提供多种语言版本。
- [30 Days of JavaScript](https://github.com/Asabeneh/30-Days-Of-JavaScript): 30 天的 JavaScript 编程挑战是一个逐步指南，帮助你在 30 天内学习 JavaScript 编程语言。
- [用函数式编程释放 JavaScript 的潜力](https://janhesters.com/blog/unleash-javascripts-potential-with-functional-programming)

#### 垃圾回收

- [A Guide to the Go Garbage Collector](https://go.dev/doc/gc-guide): 一篇关于 Go 垃圾回收器的非常有见地的指南

### 编程范式

- [命令式 vs 声明式编程](https://tylermcginnis.com/imperative-vs-declarative-programming/), Tyler McGinnis.
  - 我在声明式和非声明式之间划出界限的标准是是否可以追踪代码的执行过程。正则表达式是100%声明式的，因为在模式执行时是无法追踪的。
- 🎞 [命令式 vs 声明式编程](https://www.youtube.com/watch?v=E7Fbf7R3x6I&ab_channel=uidotdev)

### 公共演讲（展示）

- [为黑客演讲](https://sfhbook.netlify.app/)

### 阅读

- [高效阅读的完整指南](https://maartenvandoorn.nl/reading-guide/)
- [手写笔记的好处](https://www.bbc.com/worklife/article/20200910-the-benefits-of-note-taking-by-hand)
- [如何更有效和高效地阅读](https://aliabdaal.com/read-more-effectively/)
- [你应该阅读学术计算机科学论文](https://stackoverflow.blog/2022/04/07/you-should-be-reading-academic-computer-science-papers/), Stack Overflow 博客
- [如何记住你读过的内容](https://fs.blog/remember-books/)
  - 做笔记
  - 保持专注
  - 在书上做标记
  - 建立心理联系
  - 放弃一些书
- [撰写摘要比阅读更多书籍更重要](https://www.andreasfragner.com/writing/writing-summaries)
  - 用1-2句话，整本书是关于什么的？
  - 它试图回答的3-4个核心问题是什么？
  - 用一段话总结每个答案。
  - 你个人学到的最重要的东西是什么？
  - 在[Hacker News 线程](https://news.ycombinator.com/item?id=36011599)中有一个有趣的反主流观点：“一旦我放松并决定，‘如果这本书里的内容足够好，我的大脑会替我记住’，我从书本中获得的满足感和实用性都大幅增加。”
- [你读的是什么，即使你并不总是记得](https://blog.jim-nielsen.com/2024/you-are-what-you-read/)
  - “我无法记住我读过的书，就像我无法记住我吃过的饭菜一样；即使如此，它们塑造了我。” Ralph Waldo Emerson
- [我的阅读方式](https://www.robkhenderson.com/p/how-i-read)
  - 我阅读速度较慢。我会做笔记，划线，高亮，在页边写下我的想法，遇到特别有趣的内容或观点时我会暂停。
  - “听书而不是阅读书，就像喝蔬菜而不是吃蔬菜。”
  - “你从电视、电影、播客中不会学到任何持久重要的东西……它们是垃圾食品。成功人士都集中在三种学习方式上：大量的阅读时间，一些练习和项目，以及与比自己稍领先的人的对话。”

### 重构

- [The Rule of Three](https://blog.codinghorror.com/rule-of-three/), Coding Horror
  - 每个程序员都认为自己刚刚想到并输入到编辑器中的想法是最通用、最灵活、最能一劳永逸的解决方案。
  - 构建可重用组件的难度是构建单用途组件的三倍。
  - 可重用组件应在三个不同的应用程序中进行尝试，才能足够通用，被纳入重用库。
- [Refactor vs. Rewrite](https://remesh.blog/refactor-vs-rewrite-7b260e80277a)
- [Tripping over the potholes in too many libraries](https://blog.carlmjohnson.net/post/2020/avoid-dependencies/)
- [Build It Yourself](https://lucumr.pocoo.org/2025/1/24/build-it-yourself/)
  - 现在是2025年，对我来说，让ChatGPT或Cursor快速生成一个无依赖的常见函数实现，比开始研究一个依赖要更快。
- [Refactoring with Codemods to Automate API Changes](https://martinfowler.com/articles/codemods-api-refactoring.html), martinfowler.com

### 正则表达式

- [The Best Regex Trick](http://rexegg.com/regex-best-trick.html)
- [regex101: build, test, and debug regex](https://regex101.com/)

### 发布与部署

- [如何部署软件](https://zachholman.com/posts/deploying-software)，Zach Holman
- [BlueGreenDeployment](http://martinfowler.com/bliki/BlueGreenDeployment.html)，Martin Fowler
- [快速前进且不破坏任何东西](https://zachholman.com/talk/move-fast-break-nothing/)，Zach Holman
- 🏙 [快速前进且不破坏事物](https://docs.google.com/presentation/d/15gNk21rjer3xo-b1ZqyQVGebOp_aPvHU3YH7YnOMxtE/edit#slide=id.g437663ce1_53_591)，Google
- [发布到生产环境](https://blog.pragmaticengineer.com/shipping-to-production/)，The Pragmatic Programmer

#### 版本控制

- [SemVer - 语义化版本控制](https://semver.org/)
- [CalVer - 日历版本控制](https://calver.org/)
- [语义化版本控制无法拯救你](https://hynek.me/articles/semver-will-not-save-you/)
- [版本号：如何使用？](https://bernat.tech/posts/version-numbers/)

#### 检查清单

- [生产就绪检查清单](https://gruntwork.io/devops-checklist/), Gruntwork
- [检查清单：在将微服务部署到生产环境之前必须完成的内容](https://habr.com/en/post/438186/)
- [终端用户关心但程序员不关心的事](https://instadeq.com/blog/posts/things-end-users-care-about-but-programmers-dont/): 包括颜色、格式、主题、集成、用户体验、兼容性、运维。

#### 功能标志

- [Flipping out](http://code.flickr.net/2009/12/02/flipping-out/), Flickr。关于功能标志的最早文章之一。
- [Feature Flags, Toggles, Controls](https://featureflags.io/), Launch Darkly 提供的功能标志文档网站。
- [Feature Toggles (aka Feature Flags)](https://martinfowler.com/articles/feature-toggles.html), Pete Hodgson, martinFowler.com。关于该主题的全面文章。
  - 快速但安全地向用户交付新功能
  - 发布标志允许将不完整和未经测试的代码路径作为潜在代码部署到生产环境，可能永远不会启用。
  - 实验标志用于进行多变量或A/B测试。
  - 运维标志控制我们系统行为的操作方面。
  - 权限标志更改某些用户收到的功能或产品体验。
  - 静态与动态标志
  - 长期标志与短暂标志
  - 精明的团队将他们的功能标志视为库存，这会带来持有成本，并努力将库存保持在尽可能低的水平。
- [Feature Flags Best Practices: Release Management](https://launchdarkly.com/blog/release-management-flags-best-practices/), LaunchDarkly
- [How we ship code faster and safer with feature flags](https://github.blog/2021-04-27-ship-code-faster-safer-feature-flags/), Github.
- [Flipr: Making Changes Quickly and Safely at Scale](https://eng.uber.com/flipr/), Uber
- [Feature flags are ruining your codebase](https://zaidesanton.substack.com/p/feature-flags-are-ruining-your-codebase)

#### 生产环境中的测试

- [为什么 Uber 的微服务架构中使用多租户](https://eng.uber.com/multitenancy-microservice-architecture/)
- [在生产环境中开发](https://tersesystems.com/blog/2020/01/22/developing-in-production/)
  - 复杂系统会产生涌现行为，这些现象只有在达到一定规模时才会出现。
  - 伍德定理：随着系统复杂性的增加，任何单个代理对其系统模型的准确性会迅速下降。
  - 你添加的工具和代码越多，就越难复制包含这些工具和代码的环境。
  - 生产环境测试的核心思想是将部署（工件）与发布（功能）分离。
- [生产环境中的测试：困难的部分](https://medium.com/@copyconstruct/testing-in-production-the-hard-parts-3f06cefaf592), Cindy Sridharan
  - 分布式系统工程的全部重点在于，你假设在某个时间点你将会失败，并以一种方式设计系统，使得每个点的损害最小化，恢复迅速，并且风险与成本之间达到可接受的平衡。
  - 你如何将类似事件的爆炸半径减少一半？
    - 区分部署（0 风险）和发布
    - 构建部署-观察-发布的流水线
    - 将渐进式发布作为常态（金丝雀发布、基于百分比的发布等）
    - 像测试代码一样测试配置更改
    - 默认回滚，避免向前修复（缓慢！）
    - 消除灰度故障 - 在某些情况下，优先崩溃而不是降级
    - 为了降低延迟或正确性，优先使用松耦合服务
    - 使用毒药尝试点（隔离客户端输入的处理）
    - 实现按请求类别的反压
    - 从客户端/终端用户的角度具备适当的可见性（客户端指标）
- [生产环境中的测试：安全的方式](https://medium.com/@copyconstruct/testing-in-production-the-safe-way-18ca102d0ef1)
- [微服务架构中的多租户](https://www.usenix.org/system/files/login/articles/login_winter19_10_gud.pdf)

### 可靠性

**另请参阅 [系统架构](#system-architecture)**

书籍：

- 📖 [Site Reliability Engineering](https://landing.google.com/sre/books/), Google
  - 由 Google SRE 团队成员编写，对整个软件生命周期进行全面分析 - 如何构建、部署、监控和维护大规模系统。
- 📖 [SRE 中的事件指标](https://static.googleusercontent.com/media/sre.google/en//static/pdf/IncidentMeticsInSre.pdf), Štěpán Davidovič, Google
  - TTD（检测时间）、TTM（缓解时间）、TTR（恢复时间）、TBF（故障间隔时间）的权威定义

引语：

> 质量是生命周期开始时的快照，而可靠性是日常操作的连续画面。
> – [NIST](https://www.itl.nist.gov/div898/handbook/apr/section1/apr111.htm)
> 可靠性是每个客户用户都期望的特性。-- 一位 auth0 SRE。

文章：

- 我上面已经提到了书籍《Release It!》。作者还有一个[演示文稿](http://www.slideshare.net/justindorfman/stability-patterns-presentation)。
- [服务恢复：回滚与向前修复](https://www.linkedin.com/pulse/service-recovery-rolling-back-vs-forward-fixing-mohamed-el-geish/)
- [复杂系统如何失效](https://how.complexsystems.fail/)
  - 灾难需要多个故障 – 单点故障是不够的。
  - 复杂系统包含内部潜在的故障混合物。
  - 将事故归因于“根本原因”是根本错误的。
  - 事后评估会受到事后偏见的影响。
  - 安全是系统的一个特性，而不是其组件的特性。
  - 无故障操作需要有故障的经验。
- [难以深入理解的系统](https://blog.nelhage.com/post/systems-that-defy-understanding/)
  - 将精力集中在系统级故障，而不是单个组件故障。
  - 投资于先进的可观测性工具，旨在增加我们可以在不部署自定义代码的情况下提出的问题数量。
- [以可靠方式运营大型分布式系统：我学到的实践](https://blog.pragmaticengineer.com/operating-a-high-scale-distributed-system/), Gergely Orosz.
  - 对实施流程的良好总结。
- [面向生产的开发](https://paulosman.me/2019/12/30/production-oriented-development.html)
  - 生产环境中的代码是唯一重要的代码。
  - 工程师是他们所编写代码的主题专家，应负责在生产环境中运行它。
  - 购买几乎总是优于构建。
  - 使部署变得容易。
  - 信任离刀刃最近的人。
  - 质量门会降低质量。
  - 无聊的技术是伟大的。
  - 非生产环境的回报递减。
  - 事情总会出错。
- 🏙 [高可靠性基础设施迁移](https://speakerdeck.com/jvns/high-reliability-infrastructure-migrations), Julia Evans.
- [附录 F：对航天飞机可靠性的个人观察](https://www.refsmmat.com/files/reflections.pdf), Richard Feynman
- [二十年 Site Reliability Engineering 的经验教训](https://sre.google/resources/practices-and-processes/twenty-years-of-sre-lessons-learned/)
- [服务可靠性数学](https://addyosmani.com/blog/service-reliability/), Addy Osmani

资源：

- 🧰 [dastergon/awesome-sre](https://github.com/dastergon/awesome-sre)
- 🧰 [upgundecha/howtheysre](https://github.com/upgundecha/howtheysre): 技术和科技敏锐组织中 SRE 的公开资源精选集合

#### 集成模式（依赖管理）

- [熔断器](https://martinfowler.com/bliki/CircuitBreaker.html)（在《Release it!》一书中提到）
  - [使 Netflix API 更具弹性](https://netflixtechblog.com/making-the-netflix-api-more-resilient-a8ec62159c2d)，Netflix 博客
  - 🏙 [Netflix 的应用弹性工程与运营 - Speaker Deck](https://speakerdeck.com/benjchristensen/application-resilience-engineering-and-operations-at-netflix)
  - [设计模式：熔断器](https://learn.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker)，Microsoft Azure
- [速率限制算法](https://smudge.ai/blog/ratelimit-algorithms)（及其 [实现](https://github.com/upstash/ratelimit-js/blob/main/src/lua-scripts/single.ts)）
- [交互式指南：掌握速率限制](https://blog.sagyamthapa.com.np/interactive-guide-to-rate-limiting)
- [好的重试，坏的重试：一个事件故事](https://medium.com/yandex/good-retry-bad-retry-an-incident-story-648072d3cee6)：关于重试、熔断器、截止时间等的见解深刻、文笔优秀的故事

#### 韧性

- 🏙 [《行尸走肉：构建弹性应用的生存指南》](https://speakerdeck.com/daschl/the-walking-dead-a-survival-guide-to-resilient-applications)
- 🏙 [现实世界中的防御性编程与弹性系统（TM）](https://speakerdeck.com/tuenti/defensive-programming-and-resilient-systems-in-real-world-tm)
- 🏙 [全栈节：弹性分布式系统的架构模式](https://speakerdeck.com/randommood/full-stack-fest-architectural-patterns-of-resilient-distributed-systems)
- 🏙 [弹性软件设计的七大任务](https://www.slideshare.net/ufried/the-7-quests-of-resilient-software-design)
- 🧰 [弹性工程论文](https://github.com/lorin/resilience-engineering): 弹性工程的资源全面列表
- [MTTR 比 MTBF 更重要（对于大多数类型的 F）](https://www.kitchensoap.com/2010/11/07/mttr-mtbf-for-most-types-of-f/)（也作为[演示文稿](https://www.slideshare.net/jallspaw/dev-and-ops-collaboration-and-awareness-at-etsy-and-flickr)）
- [失败是不可避免的：从一次大规模故障中学习，并在 Datadog 深度构建可靠性](https://www.datadoghq.com/blog/engineering/rethinking-reliability/)

### 搜索

- [每个软件工程师都应该了解的搜索知识](https://scribe.rip/p/what-every-software-engineer-should-know-about-search-27d1df99f80d)

### 安全

- 📖 [渗透测试：黑客入门实践指南](https://nostarch.com/pentesting), Georgia Weidman
- [渗透测试工具速查表](https://highon.coffee/blog/penetration-testing-tools-cheat-sheet/#http--https-webserver-enumeration)
- [macOS 安全与隐私指南](https://github.com/drduh/macOS-Security-and-Privacy-Guide)
- [Web 应用安全指南/检查清单](https://en.wikibooks.org/wiki/Web_Application_Security_Guide/Checklist)
- [你见过一些愚蠢的安全措施吗？](https://www.troyhunt.com/reckon-youve-seen-some-stupid-security-things-here-hold-my-beer/): 所有 _不要_ 做的事情。
- [设计、测试和发布 API 时最重要的安全措施清单](https://github.com/shieldfy/API-Security-Checklist)
- [OWASP 速查表系列](https://cheatsheetseries.owasp.org/): 各种安全主题的速查表系列。
  - [Docker 安全](https://cheatsheetseries.owasp.org/cheatsheets/Docker_Security_Cheat_Sheet.html)
  - [如何提高 Docker 容器的安全性](https://blog.gitguardian.com/how-to-improve-your-docker-containers-security-cheat-sheet/)
- [安全设计](https://henrikwarne.com/2020/03/22/secure-by-design/), Henrik Warne 的书评。
  - 安全代码和良好软件设计之间有大量重叠
  - 每个领域值应由领域原语表示。
  - 在使用外部输入之前，应按照以下顺序进行验证：来源、大小、词法内容、语法、语义。
  - 实体在创建时应保持一致，操作应有限，不应共享可变对象。
  - 每隔几小时执行三项 R：自动轮换密钥，重新铺设服务器和应用程序（在干净的足迹上重新部署），修复漏洞。
  - 不要使用异常进行流程控制。
- [OWASP Web 应用十大安全风险](https://owasp.org/www-project-top-ten/)
  - [如何通过 OWASP 前十项开始 AppSec 项目](https://owasp.org/Top10/A00_2021-How_to_start_an_AppSec_program_with_the_OWASP_Top_10/)
- [ukncsc/zero-trust-architecture: 帮助你设计和部署零信任架构的原则](https://github.com/ukncsc/zero-trust-architecture)
- 🏙 [最小可行安全](https://speakerdeck.com/jacobian/minimum-viable-security-wharton-web-conference-2015)
- [开放软件保障成熟度模型](https://www.opensamm.org/)
- [安全靠隐藏被低估](https://utkusen.com/blog/security-by-obscurity-is-underrated)
- [不想支付赎金团伙？测试你的备份](https://krebsonsecurity.com/2021/07/dont-wanna-pay-ransom-gangs-test-your-backups/), Krebs on Security
- [密码初学者指南](https://medium.com/peerio/how-to-build-a-billion-dollar-password-3d92568d9277#67c2)
- [密码游戏](https://neal.fun/password-game/)
- [五年技术初创公司代码审计的收获](https://kenkantzer.com/learnings-from-5-years-of-tech-startup-code-audits/)
- [API 令牌：乏味的调查](https://fly.io/blog/api-tokens-a-tedious-survey/): 不要使用 JWT。
- [计算机安全中六个最愚蠢的想法](http://ranum.com/security/computer_security/editorials/dumb/index.html)
- [如何更好地拒绝](https://ramimac.me/saying-no)

开发人员培训：

- [Hacksplaining](https://www.hacksplaining.com/)
- [Codebashing](https://free.codebashing.com/)
- [OWASP 安全知识框架](https://owasp.org/www-project-security-knowledge-framework/)
- [PagerDuty 安全培训](https://sudo.pagerduty.com/for_engineers/)
- [Gruyere: Web 应用程序攻击与防御](https://google-gruyere.appspot.com/part1)

资源列表：

- 🧰 [meirwah/awesome-incident-response](https://github.com/meirwah/awesome-incident-response): 事件响应工具
- 🧰 [Starting Up Security](https://scrty.io/)
- 🧰 [decalage2/awesome-security-hardening](https://github.com/decalage2/awesome-security-hardening): 安全加固指南、工具和其他资源

### 研究论文

- [Papers we love](https://github.com/papers-we-love/papers-we-love): 计算机科学社区中值得阅读和讨论的论文。可以作为解决设计问题的灵感来源。
- [The morning paper](https://blog.acolyer.org/): 每天早晨解释一篇计算机科学研究论文。
- [计算机科学历史上最具影响力的7篇论文](https://terriblesoftware.org/2025/01/22/the-7-most-influential-papers-in-computer-science-history/)

### Shell (命令行)

- [The case for bash](https://www.neversaw.us/2021/04/02/the-case-for-bash/)
- 🧰 [alebcay/awesome-shell](https://github.com/alebcay/awesome-shell)
- 🧰 [dylanaraps/pure-bash-bible](https://github.com/dylanaraps/pure-bash-bible): pure bash alternatives to external processes.
- [The Bash Hackers Wiki](https://wiki.bash-hackers.org/) provides a gentler way to learn about bash than its manages.
- [Awk in 20 Minutes](https://ferd.ca/awk-in-20-minutes.html)
- 🏙 [Linux Productivity Tools](https://www.usenix.org/sites/default/files/conference/protected-files/lisa19_maheshwari.pdf)
- [jlevy/the-art-of-command-line](https://github.com/jlevy/the-art-of-command-line): master the command line, in one page **must read**
- [Minimal safe Bash script template](https://betterdev.blog/minimal-safe-bash-script-template/)
- [Command Line Interface Guidelines](https://clig.dev/)
- [The Linux Commands Handbook](https://openbootcamps.com/the-linux-commands-handbook/)
- [How to write idempotent Bash scripts](https://arslan.io/2019/07/03/how-to-write-idempotent-bash-scripts/)
- [Learn bash by playing an adventure](https://gitlab.com/slackermedia/bashcrawl)
- [Effective Shell](https://effective-shell.com/)
- [Computing from the Command Line](https://learnbyexample.github.io/cli-computing/preface.html)
- [What helps people get comfortable on the command line?](https://jvns.ca/blog/2023/08/08/what-helps-people-get-comfortable-on-the-command-line-/)，Julia Evans
- [6 Techniques I Use to Create a Great User Experience for Shell Scripts](https://nochlin.com/blog/6-techniques-i-use-to-create-a-great-user-experience-for-shell-scripts)

### SQL

- [SQL styleguide](http://www.sqlstyle.guide/)
- [Best practices for writing SQL queries](https://www.metabase.com/learn/building-analytics/sql-templates/sql-best-practices)
- [Practical SQL for Data Analysis](https://hakibenita.com/sql-for-data-analysis)
- [Reasons why SELECT * is bad for SQL performance](https://tanelpoder.com/posts/reasons-why-select-star-is-bad-for-sql-performance/)
- [Animate SQL](https://animatesql.com/)
- [Lost at SQL](https://lost-at-sql.therobinlord.com/), an SQL learning game
- [Joins 13 Ways](https://justinjaffray.com/joins-13-ways/?a=b)
- [spandanb/learndb-py](https://github.com/spandanb/learndb-py): learn database internals by implementing it from scratch.
- [gvwilson/querynomicon](https://github.com/gvwilson/querynomicon): an Introduction to SQL for the Cautious and Weary

### 状态

- [同步地图](https://stack.convex.dev/a-map-of-sync)将状态同步分为9个维度。
  - 数据模型：
    - 大小：单个客户端可以访问的数据集有多大？
    - 更新频率：客户端发送更新的频率有多高？
    - 结构：数据是结构丰富还是扁平无结构？
  - 系统需求：
    - 输入延迟：在保持良好用户体验的同时，更新可以延迟多久？
    - 离线：应用程序需要支持多少离线交互？
    - 并发客户端：有多少并发客户端会查看相同的数据？
  - 编程模型：
    - 集中化：编程模型和基础设施有多集中？
    - 灵活性：同步策略，特别是在冲突解决方面，有多灵活？
    - 一致性：应用程序可以对其数据模型断言哪些类型的不变量，这些不变量可以有多强？

### 系统管理

- 🧰 [kahun/awesome-sysadmin](https://github.com/kahun/awesome-sysadmin): 一份精心整理的、令人惊叹的开源系统管理资源列表

### 系统架构

**另请参阅 [可靠性](#system-architecture), [可扩展性](#scalability)**

阅读列表：

- 🧰 [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer): 学习如何设计大规模系统。为系统设计面试做准备。
- 🧰 [A Distributed Systems Reading List](http://dancres.github.io/Pages/)
- 🧰 [Foundational distributed systems papers](http://muratbuffalo.blogspot.com/2021/02/foundational-distributed-systems-papers.html)
- 🧰 [Services Engineering Reading List](https://github.com/mmcgrana/services-engineering)
- 🧰 [System Design Cheatsheet](https://gist.github.com/vasanthk/485d1c25737e8e72759f)
- [karanpratapsingh/system-design](https://github.com/karanpratapsingh/system-design): 学习如何设计大规模系统并为系统设计面试做准备
- [A Distributed Systems Reading List](https://ferd.ca/a-distributed-systems-reading-list.html)

博客：

- [High Scalability](http://highscalability.com/): 有关系统架构的优秀博客，其每周回顾文章充满了大量见解和有趣的科技评论。查看 [所有时间的最爱](http://highscalability.com/all-time-favorites/)。

书籍：

- 📖 [Building Microservices](https://www.amazon.com/Building-Microservices-Designing-Fine-Grained-Systems/dp/1491950358), Sam Newman（对微服务的完整讨论）
- 📖 [Designing Data-Intensive Applications](https://dataintensive.net/)

文章：

- [6 Rules of thumb to build blazing fast web server applications](http://loige.co/6-rules-of-thumb-to-build-blazing-fast-web-applications/)
- [The twelve-factor app](http://12factor.net/)
- [Introduction to architecting systems for scale](http://lethain.com/introduction-to-architecting-systems-for-scale/)
- [The Log: What every software engineer should know about real-time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying): 这是一篇每个人都应该阅读的经典文章。
- [Turning the database outside-out with Apache Samza](https://www.confluent.io/blog/turning-the-database-inside-out-with-apache-samza/)
- [Fallacies of distributed computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing), Wikipedia
- [The biggest thing Amazon got right: the platform](https://gigaom.com/2011/10/12/419-the-biggest-thing-amazon-got-right-the-platform/)
  - 从现在起，所有团队都必须通过服务接口暴露其数据和功能。
  - 监控和QA是同一件事。
- [Building Services at Airbnb, part 3](https://medium.com/airbnb-engineering/building-services-at-airbnb-part-3-ac6d4972fc2d)
  - 韧性是一个要求，而不是一个功能。
- [Building Services at Airbnb, part 4](https://medium.com/airbnb-engineering/building-services-at-airbnb-part-4-23c95e428064)
  - 为服务开发构建基于模式的测试基础设施
- [Patterns of Distributed Systems](https://martinfowler.com/articles/patterns-of-distributed-systems/), MartinFowler.com
- [ConwaysLaw](https://martinfowler.com/bliki/ConwaysLaw.html), MartinFowler.com（关于组织，请查看我的 [engineering-management](https://github.com/charlax/engineering-management/) 列表）。
- [The C4 model for visualising software architecture](https://c4model.com/)
- [If Architects had to work like Programmers](http://www.gksoft.com/a/fun/architects.html)

#### 架构模式

- BFF（前端后端）
  - [前端后端](https://samnewman.io/patterns/architectural/bff/)
- [负载均衡](https://samwho.dev/load-balancing/)：负载均衡算法的可视化探索
- [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)
  - 运营卓越
  - 安全
  - 可靠性
  - 性能效率
  - 成本优化
  - 可持续性

#### 微服务/拆分单体应用

- [Monolith First](https://martinfowler.com/bliki/MonolithFirst.html), Martin Fowler
- [面向服务的架构：随着我们的成长，Uber 工程代码库的扩展](https://eng.uber.com/soa/)
- [在生产环境中不要一开始就使用微服务 – 单体应用是你的朋友](https://arnoldgalovics.com/microservices-in-production/)
- [来自 Google 和 eBay 的关于构建微服务生态系统的深刻经验](http://highscalability.com/blog/2015/12/1/deep-lessons-from-google-and-ebay-on-building-ecosystems-of.html)
- [引入面向领域的微服务架构](https://eng.uber.com/microservice-architecture/), Uber
  - 我们不是围绕单个微服务进行定位，而是围绕相关微服务的集合进行定位。我们称这些集合为领域。
  - 在小型组织中，运营上的好处可能无法抵消架构复杂性的增加。
- [构建微服务架构的最佳实践](https://www.vinaysahni.com/best-practices-for-building-a-microservice-architecture#correlation-ids)
- 🏙 [避免构建分布式单体应用](https://speakerdeck.com/felipead/avoid-building-a-distributed-monolith)
- 🏙 [拆分单体应用](https://speakerdeck.com/slashdotpeter/breaking-down-the-monolith-devone)
- [单体应用是未来](https://changelog.com/posts/monoliths-are-the-future)
  - "我们将把它拆分，并以某种方式找到我们一开始从未拥有的工程纪律。"
- [在向微服务过渡之前准备单体应用的 12 种方法](https://semaphoreci.com/blog/monolith-microservices)
- [被一千个微服务杀死](https://renegadeotter.com/2023/09/10/death-by-a-thousand-microservices.html)
  - [微服务](https://www.youtube.com/watch?v=y8OnoxKotPQ&ab_channel=KRAZAM)
- [我在微服务世界中看到的灾难](https://world.hey.com/joaoqalves/disasters-i-ve-seen-in-a-microservices-world-a9137a51)
- [你想要微服务 – 但你真的需要它们吗？](https://www.docker.com/blog/do-you-really-need-microservices/), Docker

### 可扩展性

**另请参阅：[可靠性](#reliability), [系统架构](#system-architecture)**

- [可扩展的 Web 架构和分布式系统](http://www.aosabook.org/en/distsys.html)
- 📖 [可扩展性规则：扩展网站的 50 条原则](https://smile.amazon.com/Scalability-Rules-Principles-Scaling-Sites/dp/013443160X) ([演示文稿](http://www.slideshare.net/cyrilwang/scalability-rules))
- [扩展到 100k 用户](https://alexpareto.com/scalability/systems/2020/02/03/scaling-100k.html)，Alex Pareto。从 1 到 100k 用户的基本知识。

### 网站可靠性工程（SRE）

**参见：[可靠性](#reliability)**

### 技术债务

- [TechnicalDebt](https://martinfowler.com/bliki/TechnicalDebt.html)，Martin Fowler。
- [Fixing Technical Debt with an Engineering Allocation Framework](https://docs.google.com/presentation/d/16WU1cxG02jnVGQ5byviw3_Q0ILDPZPYtTvU91_210T0/edit#slide=id.p)
  - 修复技术债务不需要停止交付功能
  - 传达商业价值
- [Ur-Technical Debt](https://www.georgefairbanks.com/ieee-software-v32-n4-july-2020-ur-technical-debt)
  - 今天，任何开发者不喜欢的代码都会被标记为技术债务。
  - Ward Cunningham 创造了债务的隐喻，向他的经理解释通过迭代开发可以更快地获得可运行的代码，就像借钱启动项目一样，但必须持续偿还债务，否则利息支付会使项目停滞。
  - Ur-技术债务通常无法通过静态分析检测到。
- [3 Kinds of Good Tech Debt](https://engineering.squarespace.com/blog/2019/three-kinds-of-good-tech-debt)

### 测试

- ⭐️ [微服务架构中的测试策略](http://martinfowler.com/articles/microservice-testing/) (Martin Fowler) 是一个极好的资源，解释了如何正确地测试服务。
- 🧰 [分布式系统测试](https://asatarin.github.io/testing-distributed-systems/)

为什么测试：

- [为什么需要写测试？](https://dave.cheney.net/2019/05/14/why-bother-writing-tests-at-all)，Dave Cheney。一个关于该主题的良好介绍。
  - 即使你不写，别人也会测试你的软件
  - 大多数测试应该由开发团队执行
  - 手动测试不应该成为你测试的主流，因为手动测试是 O(n)
  - 测试是确保你始终可以发布主分支的关键组件
  - 测试可以锁定行为
  - 测试可以给你信心去修改别人的代码

如何测试：

- [一个快速的谜题来测试你的问题解决能力](http://www.nytimes.com/interactive/2015/07/03/upshot/a-quick-puzzle-to-test-your-problem-solving.html?_r=0)... 以及一个了解确认偏误和为什么你主要编写正面测试用例的好方法。
- [测试不是给初学者的](https://www.calhoun.io/testing-is-not-for-beginners/)：为什么学习测试是困难的。这不应该让你气馁！
- [Arrange-act-assert：编写良好测试的模式](https://automationpanda.com/2020/07/07/arrange-act-assert-a-pattern-for-writing-good-tests/)
- [更聪明地测试，而不是更努力](https://lukeplant.me.uk/blog/posts/test-smarter-not-harder/)

测试金字塔：

- [测试金字塔](http://martinfowler.com/bliki/TestPyramid.html)，Martin Fowler
- [消除测试中的不确定性](http://www.martinfowler.com/articles/nonDeterminism.html)，Martin Fowler
- [实用的测试金字塔](https://martinfowler.com/articles/practical-test-pyramid.html)，MartinFowler.com
  - 明确你想要编写的测试类型。在团队中达成命名一致，并就每种测试类型的范围达成共识。
  - 测试套件中的每一个测试都是额外的负担，不会免费获得。
  - 测试代码和生产代码一样重要。
- [软件测试反模式](http://blog.codepipes.com/testing/software-testing-antipatterns.html)，Kostis Kapelonis。
- [编写测试。不要太多。主要是集成测试。](https://blog.kentcdodds.com/write-tests-not-too-many-mostly-integration-5e8c7fff591c) 对于单元测试的反主流观点
- 🎞 [单元测试 2，集成测试：0](https://www.youtube.com/watch?v=Oj8bfBlwHAg&ab_channel=PercyRicardoAnticonaMasabel)
- [2021 年的测试](https://www.tbray.org/ongoing/When/202x/2021/05/15/Testing-in-2021)
- [Google 测试博客：测试规模](https://testing.googleblog.com/2010/12/test-sizes.html)
- [金字塔还是螃蟹？找到适合你的测试策略](https://web.dev/articles/ta-strategies)，web.dev

端到端测试：

- [对更多端到端测试说不](https://testing.googleblog.com/2015/04/just-say-no-to-more-end-to-end-tests.html)，Google 测试博客
- [端到端测试被认为是有害的](https://www.stevesmith.tech/blog/end-to-end-testing-considered-harmful/)

### 工具

- [DevDocs API 文档](https://devdocs.io/)：多个 API 文档的仓库（另请参见 [Dash for macOS](https://kapeli.com/dash)）。
- [DevChecklist](https://devchecklists.com/)：用于共享有助于确保软件质量的检查清单的协作空间
- 🧰 [开发者免费资源](https://free-for.dev/#/)：开发工具和服务免费层级列表
- [Ask HN: 有史以来最佳开发工具提案？](https://news.ycombinator.com/item?id=31782200)
- [详细说明开发者设置、设备、软件和配置的 /uses 页面列表](https://uses.tech/)

> 某些非易腐物品（如技术或想法）的未来预期寿命与其当前年龄成正比
> — Lindy 定律

### 类型系统

- [类型系统中的反例](https://counterexamples.org/intro.html)：一个库，包含类型系统未能捕获的运行时问题
- [使用你的类型系统](https://www.dzombak.com/blog/2025/07/use-your-type-system/)
  - 每个模型都应该有自己的 ID 类型。公共甚至私有函数通常应避免单独使用浮点数或整数。

### 字体排版

- [Butterick’s Practical Typography](https://practicaltypography.com/)
- [Typography for Lawyers](https://typographyforlawyers.com/)
- [Quick guide to web typography for developers · OlegWock](https://sinja.io/blog/web-typography-quick-guide)
- [Features of your font you had no idea about](https://sinja.io/blog/get-maximum-out-of-your-font)

### 版本控制 (Git)

学习 Git 的课程和书籍：

- 📖 [Git 书籍](https://git-scm.com/book/en/v2)
- [从内部了解 Git](https://codewords.recurse.com/issues/two/git-from-the-inside-out)
- [Git 教程和培训](https://www.atlassian.com/git/tutorials)，Atlassian
- [Git 沉浸式学习](https://gitimmersion.com/)
- [视觉 Git 参考](http://marklodato.github.io/visual-git-guide/index-en.html)（稍微高级一些）
- [像 Git 一样思考](http://think-like-a-git.net/)
- [Git 的数据库内部结构 I：打包对象存储](https://github.blog/2022-08-29-gits-database-internals-i-packed-object-store/)：来自 GitHub 的深入解析
- [Oh My Git!](https://ohmygit.org/)：一个学习 Git 的游戏
- [核心 Git 开发者如何配置 Git](https://blog.gitbutler.com/how-git-core-devs-configure-git/)

快捷参考表：

- [Git 快速参考](https://github.com/arslanbilal/git-cheat-sheet)
- [git-tips](https://github.com/git-tips/tips)
- [天啊，Git！？？](https://ohshitgit.com/)

更具体的主题：

- [常规提交](https://www.conventionalcommits.org/en/v1.0.0/)
- [Git 合并与变基：有什么不同？](https://hackernoon.com/git-merge-vs-rebase-whats-the-diff-76413c117333)
- 🏙 [使用 Git 变基进行故事叙述](https://speakerdeck.com/aemeredith/story-telling-with-git-rebase)
- 🏙 [Git 变基与合并](https://speakerdeck.com/mrfoto/git-rebase-vs-merge)
- 🏙 [你应该了解的 10 个 Git 反模式](https://speakerdeck.com/lemiorhan/10-git-anti-patterns-you-should-be-aware-of)
- [学习 Git 分支](https://learngitbranching.js.org/)：一个互动游戏
- [使用 git rerere 仅一次解决冲突](https://medium.com/@porteneuve/fix-conflicts-only-once-with-git-rerere-7d116b2cec67)
- [Monorepo 解释](https://monorepo.tools/)
- [如何编写 Git 提交信息](https://cbea.ms/git-commit/)
- [git-worktree](https://git-scm.com/docs/git-worktree)：管理多个连接到同一仓库的工作树。

### 工作道德、生产力与工作/生活平衡

查看我关于[工程管理资源列表，"个人生产力"](https://github.com/charlax/engineering-management/#personal-productivity)的这一部分。

### Web development

在此仓库中：查看 [training/web-dev/](.././training/web-dev/) 和 [./training/front-end/](.././training/front-end/)

学习指南和资源：

- [grab/front-end-guide](https://github.com/grab/front-end-guide): 现代前端技术栈的学习指南和介绍。
- [Front-End Developer Handbook 2019](https://frontendmasters.com/books/front-end-handbook/2019/), Cody Lindley
- [设计和前端资源目录](http://uigoodies.com/index.html)
- 🧰 [codingknite/frontend-development](https://github.com/codingknite/frontend-development): 前端开发资源列表

主题：

- [每个Web开发人员都应该知道的136个事实](https://www.baldurbjarnason.com/2021/100-things-every-web-developer-should-know/)
- [可维护的CSS](http://maintainablecss.com/)
- [由于React而忘记（或从未知道）的事情](https://joshcollinsworth.com/blog/antiquated-react)
- [检查表 - A11Y项目](https://www.a11yproject.com/checklist/) 用于无障碍
- [DevTools技巧](https://devtoolstips.org/)
- [67个浏览器不想让你知道的奇怪调试技巧](https://alan.norbauer.com/articles/browser-debugging-tricks)
- [客户端架构基础](https://khalilstemmler.com/articles/client-side-architecture/introduction/)
- [Web浏览器工程](https://browser.engineering/index.html): 这本书解释了如何用几千行Python代码构建一个基本但完整的Web浏览器，从网络到JavaScript。
- [不要动画高度！](https://www.granola.ai/blog/dont-animate-height)
- [现代浏览器的工作原理](https://addyo.substack.com/p/how-modern-browsers-work)

URL：

- [关于URI的巨大混淆](https://benbernardblog.com/the-great-confusion-about-uris/)
  - URI是一个标识资源的字符字符串。其语法是 `<scheme>:<authority><path>?<query>#<fragment>`，其中只有 `<scheme>` 和 `<path>` 是强制性的。URL和URN是URI。
  - URL是一个标识位于计算机网络上的资源的字符字符串。其语法取决于其方案。例如 `mailto:billg@microsoft.com`。
  - URN是一个唯一标识资源的字符字符串。其语法是 `urn:<namespace identifier>:<namespace specific string>`。例如 `urn:isbn:9780062301239`
- [优秀URL设计的例子](https://blog.jim-nielsen.com/2023/examples-of-great-urls/)
- [四个酷酷的URL - Alex Pounds的博客](https://alexpounds.com/blog/2018/12/29/four-cool-urls)
- [你的URL就是你的状态](https://alfy.blog/2025/10/31/your-url-is-your-state.html)

### 写作（沟通、博客）

➡️ 参见我的 [工程管理列表](https://github.com/charlax/engineering-management#writing)

- [被低估的软件工程技能：写得好](https://blog.pragmaticengineer.com/on-writing-well/)
  - 来自 HN 讨论："写几页设计文档或亚马逊风格的六页备忘录可能需要几天时间，但当你意识到系统设计存在缺陷或没有解决任何实际用户需求时，可以节省几周甚至更多的时间。"
- [推销自己，推销你的工作](https://www.solipsys.co.uk/new/SellYourselfSellYourWork.html?te20hn)
  - 如果你做了出色的工作，如果你开发了出色的软件，或者修复了飞机上的故障，或者调查了某个问题，但没有告诉任何人，那么你还不如没做。
- [写作指南](https://www.julian.com/guide/write/intro)
  - 思路 — 确定要写什么
  - 初稿 — 生成关于你主题的见解
  - 重写 — 重写以提高清晰度、吸引力和简洁性
  - 风格 — 重写以提高风格和流畅性
  - 练习 — 提高写作能力
- [简洁写作](http://paulgraham.com/simply.html), Paul Graham
- [写作就是思考：学习自信写作](https://blog.stephsmith.io/learning-to-write-with-confidence/)
- [是时候开始写作了](https://alexnixon.github.io/2019/12/10/writing.html) 解释了为什么杰夫·贝索斯在亚马逊禁止使用 PowerPoint。
  - 原因是写一份好的四页备忘录比“写”一份二十页的 PowerPoint 更难，因为一份好的备忘录的叙述结构迫使你进行更深入的思考，更好地理解什么更重要，以及事物之间的关系。
  - PowerPoint 风格的演示文稿以某种方式允许忽略想法，淡化相对重要性的感觉，并忽视想法之间的相互联系。
- [编程与写作](http://antirez.com/news/135), Antirez
- [每行写一个句子](https://sive.rs/1s)
- [Ask HN: 如何提升你的技术写作？](https://news.ycombinator.com/item?id=31859040)。有很多优秀的资源。
- [令人困惑的解释中的模式](https://jvns.ca/blog/confusing-explanations/), Julia Evans
- [开发者的写作技巧](https://css-tricks.com/technical-writing-for-developers/)
- [一些博客的误区](https://jvns.ca/blog/2023/06/05/some-blogging-myths/), Julia Evans
- [乔治·奥威尔的六条写作规则](https://infusion.media/blog/george-orwells-six-rules-for-writing/)
  - 永远不要使用你习惯于在印刷品中看到的隐喻、明喻或其他修辞手法。
  - 永远不要使用长词，如果短词可以做到的话。
  - 如果可以删掉一个词，就永远删掉它。
  - 永远不要使用被动语态，如果可以使用主动语态的话。
  - 永远不要使用外语、科学术语或行话，如果可以想到一个日常英语的等价词。
  - 与其直言不讳地使用粗鄙语言，不如违反这些规则。
- [开发者的博客写作](https://rmoff.net/2023/07/19/blog-writing-for-developers/)
- [架构图中的7个常见错误](https://www.ilograph.com/blog/posts/diagram-mistakes/)
- [如果没人阅读，为什么还要写博客？](https://andysblog.uk/why-blog-if-nobody-reads-it/)
  - 写博客迫使清晰。它让你组织你的想法，明确你的观点。
- [具体性：大规模有效的武器](https://longform.asmartbear.com/specificity/), A Smart Bear.
  - 用具体词汇代替通用词汇，使你的文字清晰、有力、吸引人，甚至有趣。

关于技术写作的指南和课程：

- [文档指南 — Write the Docs](https://www.writethedocs.org/guide/)
  - 原则
  - 风格指南
  - 文档即代码
  - 标记语言
  - 工具
- [技术写作简介](https://developers.google.com/tech-writing/one), Google
  - 语法
  - 主动语态
  - 清晰简短的句子

![像亚马逊人一样写作](.././images/amazon_writing_rules.jpeg)

> 如果你过度思考，就去写。如果你思考不足，就去读。
> – @AlexAndBooks_

## Resources & inspiration for presentations

- <https://twitter.com/devops_borat>
- <https://speakerdeck.com/>
- Dilbert
- Calvin & Hobbes ([search engine](http://michaelyingling.com/random/calvin_and_hobbes/))
- <https://twitter.com/_workchronicles>

## Keeping up-to-date

Website and RSS feeds (I use [Feedly](http://feedly.com/)):

- [Hacker News](https://news.ycombinator.com/) ⭐️
- [VentureBeat](https://venturebeat.com/)
- [High Scalability](http://highscalability.com/): see [above](#system-architecture)

Security:

- [Schneier on Security](https://www.schneier.com/)
- [Krebs on Security](https://krebsonsecurity.com/)
- [The Hacker News](https://thehackernews.com/)

Newsletters:

- [Bytes](https://bytes.dev/) (JavaScript)
- [PyCoders](https://pycoders.com/) (Python)
- [Posthog](https://newsletter.posthog.com/)
- [Tech Talks Weekly](https://techtalksweekly.io/)

Blogs:

- [kilimchoi/engineering-blogs](https://github.com/kilimchoi/engineering-blogs)

## 概念

[Glossary](../glossary.md)

- [BDD](https://en.wikipedia.org/wiki/Behavior-driven_development)
- [CAP theorem](https://en.wikipedia.org/wiki/CAP_theorem)
- [DDD](https://en.wikipedia.org/wiki/Domain-driven_design)
- [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
- [EAV](https://en.wikipedia.org/wiki/Entity%E2%80%93attribute%E2%80%93value_model)
- [GRASP](../<https://en.wikipedia.org/wiki/GRASP_(object-oriented_design)>)
- [KISS](https://en.wikipedia.org/wiki/KISS_principle)
- [Make it run, make it right, make it fast](http://c2.com/cgi/wiki?MakeItWorkMakeItRightMakeItFast)
- [OOP](https://en.wikipedia.org/wiki/Object-oriented_programming)
- [SOLID](../<https://en.wikipedia.org/wiki/SOLID_(object-oriented_design)>)
- [TDD](https://en.wikipedia.org/wiki/Test-driven_development)
- [Two Generals' Problem](https://en.wikipedia.org/wiki/Two_Generals%27_Problem)
- [YAGNI](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it)

## 我的其他列表

- [engineering-management](https://github.com/charlax/engineering-management/)
- [entrepreneurship-resources](https://github.com/charlax/entrepreneurship-resources)
- [professional-programming](https://github.com/charlax/professional-programming)
- [python-education](https://github.com/charlax/python-education)

