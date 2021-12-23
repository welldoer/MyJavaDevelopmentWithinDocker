# MyJavaDevelopmentWithinDocker

准备容器环境，参考：
1. [在VS Code中使用带Docker容器的Java开发环境 – Bruno Borge](https://www.jdon.com/52203)

具体步骤：
1. 在 GitHub 中创建新的 repository；
2. 在本机执行 git clone；
3. 打开 Vscode，以 Remote-Containers: Open Folder in Container 方式打开项目；
4. 依据提示，选择 OS，并增加 Maven、Gradle、Node、Git 等必要安装软件，等待容器镜像生成；
5. 执行 java -version、mvn --version、gradle --version、node -v、npm -v、git --version 检查；
6. 提交更新至 repository；