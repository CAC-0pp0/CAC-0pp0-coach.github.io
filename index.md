...:::  [培训要求](rules.md)\|[练习需求](https://cac-tech-coach.github.io/NewsClientSpecs)\|[练习API](https://cac-tech-coach.github.io/NewsClientAPI/)\|[计分规则](scoring.md)\|[积分榜]()\|[CI看板]()\|[SONAR数据]()\|[参考资料](references.md)\|[讲师介绍](coaches.md)  :::...

# 目标

建立对敏捷的基本认知。通过 8 小时左右的示例项目实操演练，掌握持续交付与质量内建所包括的关键技术实践，学会如何引导团队在 Android 新应用、新代码中逐步实现持续交付和质量内建。

# 小组竞赛

参训学员以小组为单位，在三天的培训时间里，根据讲师所讲收的内容和布置的任务，采用正确的技术实践完成示例项目的持续演练。在培训的最后一天下午，以小组为单位展示三天所学内容在示例项目中的运用，进行PK。最终根据小组互动表现、度量数据、以及打擂展示的[**综合得分**](scoring.md)确定[**最终排名**]()。

# 准备工作

## 账号

本次培训所有演示和小组练习代码全部使用 **[Azure DevOps](https://dev.azure.com/)** 托管和构建，也使用 **[sonarcloud](https://sonarcloud.io/)**（用于静态代码扫描和测试数据统计） 服务。**学员需要提供 Azure DevOps 账号，由教练邀请加入各小组。**

1. **❗❗注册 Azure DevOps 账号（邮箱地址，可以在[这里](https://dev.azure.com/)注册）**  
   **❗❗在分配仓库后，请[配置好 ssh key](https://dev.azure.com/cac-technical/_usersSettings/keys)。这样在练习时避免使用 http 协议 clone 仓库时可能会遇到的你题**
1. （可选）注册 sonarcloud 账号（在[这里](https://sonarcloud.io)点击"Azure DevOps"按钮，按照提示操作）

## 开发环境

本次培训有8小时左右的 Android 编码演练，学员需要提前准备好Android开发环境。要求如下：

1. **❗❗请自带笔记本电脑**
1. 安装 JDK 8
2. 安装最新 Android SDK（API Level 29+）
3. 安装最新 Android Studio（3.6+）
4. 安装 Git 客户端
5. 安装 Gradle 或使用 Gradle Wrapper

学员们在培训前可以从 Azure DevOps 上（地址培训前提供）拉取模板工程代码，提前编译缓存好相关依赖，提高练习时的编译效率。

## 知识准备

1. **❗❗学习 Kotlin（本次培训演示将全部使用 Koltin），请参考**：
   - [https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012](https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012)
   - [https://kotlinlang.org/docs/reference/](https://kotlinlang.org/docs/reference/)
2. **❗❗学习 Android Components，了解最新的 Android 分层架构风格（ViewModel 和 LiveData）**，请参考：
   - [https://codelabs.developers.google.com/codelabs/android-room-with-a-view](https://codelabs.developers.google.com/codelabs/android-room-with-a-view)  
   - [https://codelabs.developers.google.com/codelabs/android-room-with-a-view-kotlin/](https://codelabs.developers.google.com/codelabs/android-room-with-a-view-kotlin/)
3. 学习 Android 测试知识，了解可以使用的 Android 测试库，请参考：
   - [https://codelabs.developers.google.com/codelabs/android-testing](https://codelabs.developers.google.com/codelabs/android-testing)

## 熟悉练习项目

本次练习要完成的是一个 Android 新闻客户端。

1. 熟悉新闻客户端的 **[用户故事](https://cac-tech-coach.github.io/NewsClientSpecs)**。
2. 熟悉新闻客户端要使用的 **[服务 API](https://cac-tech-coach.github.io/NewsClientAPI/)**。
