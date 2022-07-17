### Tomcat目录结构
* /bin 一些脚本
* /conf 配置文件以及相关的DTD(文件类型描述符，Document Type Descriptor)，最重要的是server.xml
* /log 日志文件
* /webapps Web应用的相关文件

### 标准的目录布局

一个web应用被定义为一个具有标准布局的文件夹和文件的层次结构。
* *.html, *.jsp, etc ：HTML和JSP页面，以及其他必须对客户端浏览器可见的文件（如Js、样式表文件以及图片）。
* /WEB-INF/web.xml : 应用的*配置文件*(*Web Application Deployment Descriptor*)
* /WEB_INF/classes/ : 这个目录包含了web应用中所需要的所有的class文件（以及想关联的资源）。包括没有被打包成jar文件的servlet和非servlet类。
* /WEB-INF/lib/ : 这个目录包含web应用所需要的JAR文件，例如第三方的类库或者JDBC驱动。

### Tomcat 应用部署
为了被执行，一个web应用必须被部署在一个servlet容器中。应用程序可以使用下面的一种方式被部署在Tomcat中：
