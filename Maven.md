**Maven 的本质是一个项目管理工具，将项目开发和管理过程抽象成一个项目对象模型(POM, Project Object Model)。**
### Maven 的作用：
* 项目构建
* 依赖管理：管理依赖的资源，避免资源间的版本冲突
* 统一开发结构
  
### Maven 文件结构:：
* /bin ：运行文件
* /boot ：类加载器
* /conf ：配置管理
* /lib ：运行所依赖的jar包

### Maven基础概念
* **仓库** : 用于存储资源，包含各种jar包。（中央仓库，私服，本地仓库）
* **坐标** : Maven中用于描述资源位置。由groupId,artifactld,version组成。packaging定义了项目的打包方式。
* **仓库配置** 