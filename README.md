# ForestBlog - 深圳大学软件工程课程大作业

一个基于 SSM（Spring + SpringMVC + MyBatis）的个人博客系统。  
包含文章管理、用户系统、评论功能、后台管理等模块。
----              
## 📌 项目特性
- 📝 文章发布、编辑、删除  
- 👤 用户注册 / 登录  
- 💬 评论功能  
- 🛠 后台管理  
- 🔍 基于 SSM 架构  
- 🎨 前端基于 前端（View 层 / 表现层）：
1.JSP
用作页面展示，结合 JSTL/EL 输出数据。
2.HTML + CSS + JavaScript
负责页面结构、样式、交互。
3.JSP + SpringMVC
通过 Controller 返回 JSP，实现前后端页面渲染。

-🎨后端（业务层 & 持久层）:
1. Spring — 业务逻辑层（Service）
实现业务流程，如：用户注册、登录、发布文章、评论、分类管理等。
使用 @Service、@Component、@Autowired 实现 IoC/DI。
2. SpringMVC — 控制层（Controller）
接收前端请求（/login, /article/add 等）。
调用 Service 处理业务。
返回 JSP 视图或 JSON。
3. MyBatis — 持久层（DAO）
用 XML 或注解编写 SQL。
实现 CRUD：文章、用户、评论、分类等表。
映射数据库字段和 Java 对象。
4. MySQL — 数据库
存储所有数据（用户、文章、评论、分类、权限、统计等）。
使用连接池（如 Druid / c3p0）。
5. Maven — 构建与依赖管理
管理 Spring、SpringMVC、MyBatis 所有依赖。
提供项目打包、构建、执行方式。re
🖥️ 开发环境（Development Environment）
JDK 22
IntelliJ IDEA
Apache Tomcat 9
MySQL  8.0
Maven 3.6+

## 📁 项目结构（来自 IDEA 工程）
