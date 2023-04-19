#### 电影知识图谱
这个电影知识图谱项目使用了Spring Boot、Spring Data Neo4j和Neo4j数据库来构建一个Web应用程序，提供了一个交互式的电影信息浏览和搜索体验。该项目使用了Java 11作为编程语言，并使用了前端技术如jQuery、Bootstrap和d3.js来展示电影数据。

通过该应用程序，用户可以搜索电影、导演和演员，并查看它们之间的关系和详细信息。电影、导演和演员以及它们之间的关系都被建模为Neo4j数据库中的节点和边。Spring Data Neo4j提供了一些方便的对象图映射功能，使得将Neo4j集成到基于Spring的应用程序中变得非常容易。

用户可以通过环境变量配置Neo4j数据库的连接信息。默认情况下，数据库连接使用的是Neo4j Sandbox或Neo4j Aura提供的演示数据库。该应用程序的Web框架使用了Spring-Boot启用的Spring-WebMVC，提供了一个方便的RESTful API来查询电影知识图谱数据。
#### 运行环境配置
视频教程：
https://meeting.tencent.com/v2/cloud-record/share?id=b87e9f69-c8da-4642-9ea9-c5f40374daea&from=3

JDK11的安装及配置
jdk11环境配置链接 牢记安装路径，配置环境需要
https://blog.csdn.net/Y16692862627/article/details/129726856

maven安装教程及环境配置
https://blog.csdn.net/Y16692862627/article/details/129727157

idea的配置
https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/v2/cover/boxcn8ER8Z1aY3xLc8Ca0STIq6g/?fallback_source=1&height=1280&mount_node_token=RAYQdQ6AKoOYmuxARa1cbDgknuc&mount_point=docx_image&policy=equal&width=1280

然后将idea的jdk版本切换
https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/v2/cover/boxcnkkwuKNkeR0iY1KT1dsIfCb/?fallback_source=1&height=1280&mount_node_token=F8KedsSeuoiWeixMhHzcvHg0nsb&mount_point=docx_image&policy=equal&width=1280

blob:https://a2eb1ewtyj.feishu.cn/92340a07-38b1-436f-a6cc-3328017697c8
添加完jdk就可运行代码了；

运行代码
下再次仓库代码按如图所示运行
blob:https://a2eb1ewtyj.feishu.cn/3d729ea8-73b3-49fb-9fea-821db56bef61

如果出现这种情况
blob:https://a2eb1ewtyj.feishu.cn/2ade1ba6-8248-4c97-a419-f746a3358382

则点击下图中的load
blob:https://a2eb1ewtyj.feishu.cn/5639a8ef-ec62-4194-b912-ff1a0d0b83b5

然后点击运行

运行成功后浏览器访问http://localhost:8080/即可。

如果想改变端口

blob:https://a2eb1ewtyj.feishu.cn/94aca80e-1026-4498-9707-9b335db1d7c2

blob:https://a2eb1ewtyj.feishu.cn/bbbcdd05-249c-49ad-a3d3-4772092c646f

blob:https://a2eb1ewtyj.feishu.cn/94587a12-1167-4090-9b89-8ef4aff1e166

直接把8080换成其他的即可
