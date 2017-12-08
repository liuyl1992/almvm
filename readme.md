---
layout: homepage
title: Microsoft ALM VM
keywords: ALM VM homepage
tags: [overview]
permalink: default.html
comments: true
summary: 
---
        
 <!--<img src="http://vsalmvm.azurewebsites.net/wp-content/uploads/2015/09/ALM-VM-banner-0915.png" width="760" height="177" />-->

<br>

### 微软 ALM/DevOps 动手实验 是一系列的练习和实验，这其中包括了丰富内容，通过这些文档、实验和练习，可以让我们体验 Microsoft Visual Studio Team Foundation Server/Visual Studio Team Services 在 ALM/DevOps 方面提供的能力，使得我们能更好的利用微软的工具改善我们的交付流程，使我们的企业更具竞争力。 

<br /> 

<div class="row">
    <div class="lab-item col-md-4" align="center">
          <span class="headnews"> <b> <a href="labs/tfs" class="labmain">Visual Studio & Team Foundation Server Labs</a></b></span><br />
             <a href="labs/tfs"><img style="margin: 10px;" src="images/vside.png"/></a><br />
           <!--span class="mainPageText"> Access the Microsoft ALM VM and TFS Hands-on-Labs</span><br /><br /-->
           <a href="labs/tfs" class="c-glyph"><span class="lab-details">开始练习</span></a>
    </div>
    <div class="lab-item col-md-4" align="center">
         <span class="headnews"> <b><a href="labs/vsts" class="labmain"> Visual Studio Team Services Labs</a></b></span><br /><br />
        <a href="labs/vsts"><img style="margin: 10px;" src="images/vstslogo.png"/></a><br />
       <!--span class="mainPageText"> Follow the Visual Studio Team Services Hands-on-Labs</span><br /><br /-->
       <a href="labs/vsts" class="c-glyph"><span class="lab-details">开始练习</span></a>
    </div>
     <div class="lab-item col-md-4" align="center">
         <span class="headnews"> <b><a href="labs/java" class="labmain"> DevOps with Visual Studio Team Services for Java Labs</a></b></span><br />
        <a href="labs/java"><img style="margin: 10px;" src="images/java.png"/></a><br />
       <!--span class="mainPageText"> DevOps with Visual Studio Team Services for Java</span><br /><br /-->
       <a href="labs/java" class="c-glyph"><span class="lab-details">开始练习</span></a>
    </div>
</div>
 
<div class="clear"></div>


## Visual Studio Team Services Demo Generator 概述

### Visual Studio Team Services DemoGenerator 帮助我们在Visual Studio Team Services 帐户上创建项目，该项目内置示例内容包括源代码、工作项、服务端点、构建和发布定义<h4>

此工具用于帮助Visual Studio 市场团队创建基于VSTS的实验、演示、和教育所需的资源

### 准备工作:

- 一个微软live帐号 - 如果还没有，可以现在 <a href="https://signup.live.com">创建</a> 一个

- 一个 Visual Studio Team Services [初始帐号项目](https://app.vsaex.visualstudio.com),如果你已经拥有，进入你的项目，或者打开[这里](https://aexprodsu1scus.vsaex.visualstudio.com/profile/account?mkt=zh-CN)创建一个

- 此帐号下的一个PAT(Personal Access Token)访问令牌. 关于创建PAT的相关信息，可以查看[这里](https://docs.microsoft.com/zh-cn/vsts/accounts/use-personal-access-tokens-to-authenticate)

- 复制你的PAT，保存下来，下面要用到这个令牌

## 开始使用 Vsts Demo Generator 工具

- 1. 打开 <a href="https://vstsdemogenerator.azurewebsites.net/" target="_blank">VSTS Demo Generator </a> 工具主页面

   <img style="max-width: 700px;max-height: 700px;" src="/labs/vsts/VSTSDemoGenerator/images/1.png"/>

- 2. 输入 ***VSTS 帐号*** 和 ***PAT*** ，然后点击 **Verify & Continue** 

   <img style="max-width: 700px;max-height: 700px;"  src="/labs/vsts/VSTSDemoGenerator/images/2.png"/>

- 3. 输入你的示例项目名称，然后选择一个示例项目模板


   <img style="max-width: 700px;max-height: 700px;"  src="/labs/vsts/VSTSDemoGenerator/images/3.png"/>

4. 有些模板需要在你的VSTS项目中安装扩展，系统会先检测是否已经安装这些扩展，绿色的标记表示已经安装，没有安装建议安装扩展，跟据提示会进入VSTS的扩展商店，在商店可以完成扩展的安装

   <img src="/labs/vsts/VSTSDemoGenerator/images/4.png"/> 

- 5. 点击 **Install**  安装扩展到你的VSTS项目中.

   <img style="max-width: 700px;max-height: 700px;" src="/labs/vsts/VSTSDemoGenerator/images/5.png"/>

- 6. 扩展安装完成后, 返回 VSTS Demo Generator tab 页面并刷页面. 点击 **Create Project**. 你可以看到正在创建项目，这其中会有状态反馈.

   <img style="max-width: 700px;max-height: 700px;" src="/labs/vsts/VSTSDemoGenerator/images/6.png"/>

7. 当项目创建成功后，会看到有创建的团队项目的链接

   <img style="max-width: 700px;max-height: 700px;"  src="/labs/vsts/VSTSDemoGenerator/images/7.png"/>

8. 点进链接，导航到项目主页面，检查并确认项目是否正确创建

   <img style="max-width: 700px;max-height: 700px;"  src="/labs/vsts/VSTSDemoGenerator/images/8.png"/>

>**注:** 你需要为创建的端点提供您自己的信息，如url、用户名、密码等。在尝试使用它们之前，需要提供它们，比如在构建版本中、发布定义中


