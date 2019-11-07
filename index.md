...:::  [讲师介绍](coaches.md)\|[培训要求](rules.md)\|[练习需求](https://cac-tech-coach.github.io/NewsClientSpecs)\|[练习API](https://cac-tech-coach.github.io/NewsClientAPI/)\|[度量数据](http://139.198.4.126:8081/#/)\|[积分榜](https://coda.io/d/CAC-OPPO_dWBwjkLuEXF/_subOs)\|[计分规则](scoring.md)\|[CI大屏](https://run.buildmonitor.io/?import=%5B%7B%22Connector%22%3A%22BuildMonitorTravis3%22%2C%22Name%22%3A%22CAC%40OPPO%22%2C%22ServerUrl%22%3A%22https%3A%2F%2Fapi.travis-ci.org%2F%22%2C%22Username%22%3A%22qinyu%22%2C%22Token%22%3A%22mPcuXvs0-wx4Z8XCmI2K1A%22%2C%22ImportantRefs%22%3A%22(master%7Cdevelop%7Crelease%2F(.*))%22%2C%22OnlyActive%22%3Atrue%2C%22Interval%22%3A%221000%22%2C%22ConfigUrl%22%3A%22https%3A%2F%2Fbuildmonitor.gitlab.io%2FTravisConnector%2Fconfig.json%22%7D%5D)\|[参考资料](references.md)  :::...

# 单元测试技巧&规范

[https://github.com/qinyu/junit-docs/](https://github.com/qinyu/junit-docs/)

# 目标

建立对敏捷的基本认知。通过 8 小时左右的示例项目实操演练，掌握持续交付与质量内建所包括的关键技术实践，学会如何引导团队在 Android 新应用、新代码中逐步实现持续交付和质量内建。

# 小组划分

参训学员组成**6个学习小组**，以小组为单位，在三天的培训时间里，根据讲师所讲收的内容和布置的任务，采用正确的技术实践完成示例项目的持续演练。在培训的最后一天下午，以小组为单位展示三天所学内容在示例项目中的运用，进行PK。最终根据小组互动表现、度量数据、以及打擂展示的[**综合得分**](scoring.md)确定[**最终排名**](https://coda.io/d/CAC-OPPO_dWBwjkLuEXF/_subOs)。

| 小组 | 仓库 | 构建 | 测试覆盖率 | 应用下载地址 |
| --- | --- | --- | --- | --- | --- |
| [Oreo](https://github.com/orgs/CAC-0pp0/teams/oreo/members)        | [![Github Repo](https://img.shields.io/github/commit-activity/w/CAC-0pp0/CACOreo.svg)](https://github.com/CAC-0pp0/CACOreo)               | [![Build Status](https://travis-ci.org/CAC-0pp0/CACOreo.svg?branch=master)](https://travis-ci.org/CAC-0pp0/CACOreo)               | [![codecov](https://codecov.io/gh/CAC-0pp0/CACOreo/branch/master/graph/badge.svg)](https://codecov.io/gh/CAC-0pp0/CACOreo)               |         [https://www.pgyer.com/GD4q](https://www.pgyer.com/GD4q) |
| [Nougat](https://github.com/orgs/CAC-0pp0/teams/nougat/members)      | [![Github Repo](https://img.shields.io/github/commit-activity/w/CAC-0pp0/CACNougat.svg)](https://github.com/CAC-0pp0/CACNougat)           | [![Build Status](https://travis-ci.org/CAC-0pp0/CACNougat.svg?branch=master)](https://travis-ci.org/CAC-0pp0/CACNougat)           | [![codecov](https://codecov.io/gh/CAC-0pp0/CACNougat/branch/master/graph/badge.svg)](https://codecov.io/gh/CAC-0pp0/CACNougat)           | [https://www.pgyer.com/9ykK](https://www.pgyer.com/9ykK) |
|   [Marshmallow](https://github.com/orgs/CAC-0pp0/teams/marshmallow/members)  | [![Github Repo](https://img.shields.io/github/commit-activity/w/CAC-0pp0/CACMarshmallow.svg)](https://github.com/CAC-0pp0/CACMarshmallow) | [![Build Status](https://travis-ci.org/CAC-0pp0/CACMarshmallow.svg?branch=master)](https://travis-ci.org/CAC-0pp0/CACMarshmallow) | [![codecov](https://codecov.io/gh/CAC-0pp0/CACMarshmallow/branch/master/graph/badge.svg)](https://codecov.io/gh/CAC-0pp0/CACMarshmallow)| [https://www.pgyer.com/qbSY](https://www.pgyer.com/qbSY) |
| [Lollipop](https://github.com/orgs/CAC-0pp0/teams/lollipop/members)    | [![Github Repo](https://img.shields.io/github/commit-activity/w/CAC-0pp0/CACLollipop.svg)](https://github.com/CAC-0pp0/CACLollipop)       | [![Build Status](https://travis-ci.org/CAC-0pp0/CACLollipop.svg?branch=master)](https://travis-ci.org/CAC-0pp0/CACLollipop)       | [![codecov](https://codecov.io/gh/CAC-0pp0/CACLollipop/branch/master/graph/badge.svg)](https://codecov.io/gh/CAC-0pp0/CACLollipop)        | [https://www.pgyer.com/955w](https://www.pgyer.com/955w) |
| [KitKat](https://github.com/orgs/CAC-0pp0/teams/kitkat/members)  | [![Github Repo](https://img.shields.io/github/commit-activity/w/CAC-0pp0/CACKitKat.svg)](https://github.com/CAC-0pp0/CACKitKat)           | [![Build Status](https://travis-ci.org/CAC-0pp0/CACKitKat.svg?branch=master)](https://travis-ci.org/CAC-0pp0/CACKitKat)           | [![codecov](https://codecov.io/gh/CAC-0pp0/CACKitKat/branch/master/graph/badge.svg)](https://codecov.io/gh/CAC-0pp0/CACKitKat)                 | [https://www.pgyer.com/UFQH](https://www.pgyer.com/UFQH) |
| [Jelly Bean](https://github.com/orgs/CAC-0pp0/teams/jelly-bean/members)   | [![Github Repo](https://img.shields.io/github/commit-activity/w/CAC-0pp0/CACJellyBean.svg)](https://github.com/CAC-0pp0/CACJellyBean)     | [![Build Status](https://travis-ci.org/CAC-0pp0/CACJellyBean.svg?branch=master)](https://travis-ci.org/CAC-0pp0/CACJellyBean)     | [![codecov](https://codecov.io/gh/CAC-0pp0/CACJellyBean/branch/master/graph/badge.svg)](https://codecov.io/gh/CAC-0pp0/CACJellyBean)      | [https://www.pgyer.com/2SL2](https://www.pgyer.com/2SL2) |

# 充分准备

## 账号

本次培训所有演示和小组练习代码全部使用 [github](https://github.com) 托管，也使用了 [travis-ci](https://travis-ci.org/)（用于构建） 和 [codecov](https://codecov.io/gh)（用于覆盖率统计） 服务。各小组的 repo（git 代码仓库）和 team 都已经准备好。学员需要提供 github 账号，由教练邀请加入各小组。

1. 提供 github 账号（账号名或邮箱地址，可以在[这里](https://github.com/join?source=header-home)注册）
2. 关联 github 账号和 travis-ci（在[这里](https://travis-ci.org/)点击右上角"Sign in with Github"按钮，按照提示操作）
3. 关联 github 账号和 codecov（在[这里](https://codecov.io/gh)点击中央" Login with Github"按钮，按照提示操作））

## 开发环境

本次培训有8小时左右的 Android 编码演练，学员需要提前准备好Android开发环境。要求如下：

1. 安装 JDK 8
2. 安装最新 Android SDK（API Level 29）
3. 安装最新 Android Studio（3.5）
4. 安装 Git 客户端
5. 安装 Gradle 或使用 Gradle Wrapper

学员们在培训前可以从所属小组的仓库（见上表）拉取模板工程代码，提前编译缓存好相关依赖，提高练习时的编译效率。

## 熟悉练习项目

本次练习要完成的是一个 Android 新闻客户端。

1. 熟悉新闻客户端的**[用户故事](https://cac-tech-coach.github.io/NewsClientSpecs)**。
2. 熟悉新闻客户端要使用的**[服务 API](https://cac-tech-coach.github.io/NewsClientAPI/)**。

## 知识准备（建议）

1. 学习 Android Components，了解最新的 Android 分层架构风格，请参考：
   - [https://codelabs.developers.google.com/codelabs/android-room-with-a-view](https://codelabs.developers.google.com/codelabs/android-room-with-a-view)  
   - [https://codelabs.developers.google.com/codelabs/android-room-with-a-view-kotlin/](https://codelabs.developers.google.com/codelabs/android-room-with-a-view-kotlin/)
2. 学习 Android 测试知识，了解可以使用的 Android 测试库，请参考：
   - [https://codelabs.developers.google.com/codelabs/android-testing](https://codelabs.developers.google.com/codelabs/android-testing)
3. 学习 Kotlin（本次培训演示将全部使用 Koltin，[**使用 Kotlin 完成练习也能获得额外加分**](scoring.md)），请参考：
   - [https://kotlinlang.org/docs/reference/](https://kotlinlang.org/docs/reference/)
   - [https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012](https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012)




