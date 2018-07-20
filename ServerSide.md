# Server Side Tools and Services

## Project Structure

Server side project structure follows the maven/gradle [standard directory structure](https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html).



## Maven Plugins

Maven/Gradle plugins will be used for code style checking, bug finding, test running etc.

#### Code Style

Sun coding style will be used, there might be exceptions per project i.e. disabling Spring Boot application default constructor error. 

[Maven Checkstyle Plugin](https://maven.apache.org/plugins/maven-checkstyle-plugin/) and project defined checkstyle definitions will be used.

#### Bug Finding

[FindBugs](https://gleclaire.github.io/findbugs-maven-plugin/) maven plugin will be used with default settings. 



## IDE Helpers

#### Editor Config

[Editor config](https://editorconfig.org/) will be used in order to follow same coding standards. 

#### Gitignore

A default .gitignore file will be used, the file might be edited acording to project, an example file can be found [here](https://raw.githubusercontent.com/canmogol/spring-service-discovery-server/master/.gitignore).




