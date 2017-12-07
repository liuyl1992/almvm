---
title: Visual Studio Team Services Demo Generator- Overview 
layout: page
sidebar: vsts
permalink: /labs/vsts/VSTSDemoGenerator/
folder: /labs/vsts/VSTSDemoGenerator/
---

## 概述
Visual Studio Team Services Demo Generator 帮助您在Visual Studio Team Services 帐户上创建项目，该项目内置的示例内容包括源代码、工作项、服务端点、基于您选择的模板构建和发布定义 

此工具用于帮助Visual Studio 市场团队创建基于VSTS的实验、演示、和教育所需的资源

准备工作:

- 一个 Visual Studio Team Services 帐号 - 如果还没有，可以现在 
<a href="http://bit.ly/2dwMwYR">创建</a> 一个
- 此帐号下的一个PAT(Personal Access Token)访问令牌. 关于创建PAT的相关信息，可以查看 <a href="http://bit.ly/2okeOyJ">这里</a>


## 开始使用 Vsts Demo Generator 工具

1. 打开 <a href="https://vstsdemogenerator.azurewebsites.net/" target="_blank">VSTS Demo Generator </a> 工具主页面

   <img src="images/1.png"/>

2. 输入 ***VSTS 帐号*** 和 ***PAT*** ，然后点击 **Verify & Continue** 

   <img src="images/2.png"/>

3. 输入你的示例项目名称，然后选择一个示例项目模板


   <img src="images/3.png"/>

4. 有些模板需要在你的VSTS项目中安装扩展，系统会先检测是否已经安装这些扩展，绿色的标记表示已经安装，没有安装建议安装扩展，跟据提示会进入VSTS的扩展商店，在商店可以完成扩展的安装

   <img src="images/4.png"/> 

5. 点击 **Install**  安装扩展到你的VSTS项目中.

   <img src="images/5.png"/>

6. 扩展安装完成后, 返回 VSTS Demo Generator tab 页面并刷页面. 点击 **Create Project**. 你可以看到正在创建项目，这其中会有状态反馈.

   <img src="images/6.png"/>

7. 当项目创建成功后，会看到有创建的团队项目的链接

   <img src="images/7.png"/>

8. 点进链接，导航到项目主页面，检查并确认项目是否正确创建

   <img src="images/8.png"/>

>**注:** 你需要为创建的端点提供您自己的信息，如url、用户名、密码等。在尝试使用它们之前，需要提供它们，比如在构建版本中、发布定义中





   




