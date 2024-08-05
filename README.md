# Spring Boot & Vue3 Examples

欢迎来到 **Spring Boot & Vue3 Examples** 仓库！这个仓库包含了专栏文章中的所有测试代码，包括后端的 Spring Boot 和前端的 Vue3 代码。本仓库的目的是为开发者提供符合企业真实开发场景的最佳实践，帮助你在实际项目中快速上手并解决常见问题。

## 目录结构

```bash
spring-boot-vue-examples/
├── backend/
├── frontend/
├── docs/
├── .gitignore
└── README.md
```

## 目的

本仓库的主要目的是通过一个实际的企业级开发案例，讲解和演示 Spring Boot 和 Vue3 的高级功能，帮助开发者掌握实际项目开发中的最佳实践。通过完整的前后端代码示例，开发者可以学习到如何：

- 使用 Spring Boot 实现复杂业务逻辑
- 集成 MySQL 和 Redis 数据库
- 实现用户认证和授权，包括 JWT 和单点登录（SSO）
- 使用 Vue3 搭建前端页面并与后端进行交互
- 使用单元测试确保代码质量

希望本仓库能够帮助你更好地理解和应用这些技术，提高你的开发技能。

## 如何使用

### 后端

1. 克隆仓库到本地：

   ```sh
   git clone https://github.com/idevebi/spring-boot-vue-examples.git
   ```

2. 导入 `backend` 目录中的项目到你的 IDE（如 IntelliJ IDEA）。
3. 修改 `src/main/resources/application.properties` 文件中的数据库配置。
4. 运行 `QuickstartApplication.java` 启动 Spring Boot 应用。
5. 访问 `http://localhost:8080` 进行 API 测试。

### 前端

1. 进入 `frontend/user-login` 目录：

   ```sh
   cd frontend/user-login
   ```

2. 安装依赖：

   ```sh
   yarn install
   ```

3. 启动前端应用：

   ```sh
   yarn serve
   ```

4. 访问 `http://localhost:8080` 查看登录页面并进行测试。

## 贡献

欢迎大家为本项目贡献代码！如果你有任何建议或问题，请提 [Issue](https://github.com/idevebi/spring-boot-vue-examples/issues) 或提交 [Pull Request](https://github.com/idevebi/spring-boot-vue-examples/pulls)。

## 许可证

本项目采用 MIT 许可证，详情请参阅 [LICENSE](LICENSE) 文件。

---

希望这些示例代码能帮助你在实际项目中更好地应用 Spring Boot 和 Vue3。如果你觉得本项目对你有帮助，请给我们一个 Star ⭐️！
