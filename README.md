智慧新零售管理系统 - SpringBoot

该项目是一个基于 SpringBoot技术栈构建的智慧新零售管理系统。以下是项目的详细信息和使用指南。


前端项目 [Github](https://github.com/AlexCat315/soms-vue)仓库


项目技术栈

    后端：SpringBoot
    Java 版本：JDK 17（推荐使用 JDK 21）
    数据库：MySQL 5+ (推荐8+)

项目使用
1. 克隆项目


``` bash
git clone https://github.com/AlexCat315/soms-ssm.git
```



2. 修改数据库配置文件

编辑 src/main/resources/application.yaml 文件，修改为你本地的数据库配置：


``` properties
jdbc.driver=com.mysql.cj.jdbc.Driver
jdbc.url=jdbc:mysql://localhost:3306/数据库名?useUnicode=true&characterEncoding=utf8
jdbc.username=root # 修改为你的用户名
jdbc.password=123456 # 修改为你的密码
```



部署和运行

    导入项目：将项目导入到 IntelliJ IDEA。
    配置 Maven：确保 Maven 配置正确，并下载所有依赖。
    配置数据库：确保 MySQL 数据库运行，并创建项目所需的数据库。
    修改配置：按照上述步骤修改 db.properties 文件中的数据库配置。
    启动服务器：在 IDEA 中配置并启动 Tomcat 服务器。
    访问项目：在浏览器中访问 http://localhost:12345 以查看项目运行情况。

注意事项

    确保 MySQL 数据库的用户名和密码正确。
    确保数据库名称和表结构与项目要求一致。
    若遇到依赖问题，检查 Maven 配置并重新导入依赖。

贡献指南

欢迎任何形式的贡献，包括但不限于：

    提交代码
    报告 Bug
    提出新功能建议

联系方式

若有任何问题或建议，请通过 GitHub Issues 进行反馈。
