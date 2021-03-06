# Projects 和 tasks

Gradle 里的任何东西都是基于这两个基础概念: *projects(项目)* 和 *tasks(任务)*.

每一个 Gradle 构建都是由一个或多个projects 构成的. 一个 project 到底代表什么依赖于你想用 Gradle 做什么. 举个例子, 一个 project 也许代表一个 JAR 或者一个网页应用. 它也可能代表一个发布的 ZIP 压缩包, 这个 ZIP 可能是由许多其他项目的 JARs 构成的. 一个 project 不必要代表要被构建的某个东西. 它可以代表一件要做的事, 比如布署你的应用. 不要担心现在这些说明看上去有一点模糊. Gradle 的合约构建的支持加入了一个更加具体的关于 project 的定义.

每一个 project 是由一个或多个 tasks 构成的. 一个 task 代表一些更加细化的构建. 可能是编译一些 classes, 创建一个 JAR,生成 javadoc, 或者生成莫个目录的压缩文件.

目前, 我们将关注定义构建里的一些简单的 tasks . 以后的章节会关注与多项目构建以及如果通过projects 和 tasks 工作.
