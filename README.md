🌲 ForestBlog

深圳大学软件工程课程大作业 — 基于 SSM 的个人博客系统

ForestBlog 是一个使用 SSM（Spring + SpringMVC + MyBatis） 搭建的个人博客平台，支持文章管理、用户系统、评论、后台管理等核心功能。

🚀 功能特性（Features）

📝 文章管理：发布 / 编辑 / 删除 / 浏览

👤 用户系统：注册 / 登录 / 权限控制

💬 评论功能：文章评论与展示

🛠 后台管理：文章、用户、分类等管理

📦 清晰的分层结构：基于 SSM 的 MVC 分层设计

🎨 JSP 视图渲染 + HTML/CSS/JS 前端展示

🧱 技术架构（Architecture）
🎨 前端（View 层）

JSP：负责页面展示与数据渲染

HTML / CSS / JavaScript：页面结构、样式与交互

JSTL / EL：辅助从后台向页面输出数据

⚙️ 后端（业务层 & 持久层）
1. Spring — 业务逻辑层（Service）

实现文章、登录、评论等核心业务

使用 @Service、@Autowired 进行 IoC / DI

2. SpringMVC — 控制层（Controller）

接收前端请求（如 /login、/article/add）

调用 Service 完成业务逻辑

返回 JSP 或 JSON

3. MyBatis — 持久层（DAO）

XML/注解编写 SQL

实现文章 / 用户 / 评论 / 分类等 CRUD

Java 对象与数据库表字段映射

4. MySQL — 数据存储

存储用户、文章、评论、分类等业务数据

可结合 Druid/c3p0 作为连接池

5. Maven — 构建与依赖管理

管理 Spring、SpringMVC、MyBatis 等依赖

标准 SSM 项目构建工具

🖥️ 开发环境（Development Environment）

JDK 22

IntelliJ IDEA

Apache Tomcat 9

MySQL 8.0

Maven 3.6+
