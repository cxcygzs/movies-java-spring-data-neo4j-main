#### 电影知识图谱
这个电影知识图谱项目使用了Spring Boot、Spring Data Neo4j和Neo4j数据库来构建一个Web应用程序，提供了一个交互式的电影信息浏览和搜索体验。该项目使用了Java 11作为编程语言，并使用了前端技术如jQuery、Bootstrap和d3.js来展示电影数据。

通过该应用程序，用户可以搜索电影、导演和演员，并查看它们之间的关系和详细信息。电影、导演和演员以及它们之间的关系都被建模为Neo4j数据库中的节点和边。Spring Data Neo4j提供了一些方便的对象图映射功能，使得将Neo4j集成到基于Spring的应用程序中变得非常容易。

用户可以通过环境变量配置Neo4j数据库的连接信息。默认情况下，数据库连接使用的是Neo4j Sandbox或Neo4j Aura提供的演示数据库。该应用程序的Web框架使用了Spring-Boot启用的Spring-WebMVC，提供了一个方便的RESTful API来查询电影知识图谱数据。
#### 运行环境配置
https://a2eb1ewtyj.feishu.cn/docx/EwvadG4B0oCfa8xp81ncAgj6nSe
