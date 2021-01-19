# 山科智绘感知兴趣小组任务

## 一、介绍

本仓库主要用于存放山科智绘感知兴趣小组在开展活动过程中安排的任务，以及小组成员提交的任务完成报告。

## 二、必知必会

### 1、编程语言

- C/C++
- Python

### 2、技术文档撰写

- LaTeX
  - Texlive发行版
- Markdown

### 3、版本管理

- Git
  - 代码托管：Github（国外）、Gitee（国内）
  - 推荐客户端：SourceTree

### 4、Visual Studio Code (VSCode)

- 官方网址： <https://code.visualstudio.com>
- C/C++的推荐编辑器
  - C/C++
- Python的推荐编辑器
  - Anaconda发行版
  - Python插件（Microsoft）
- LaTeX的推荐编辑器
  - LaTeX Workshop插件
- Markdown的推荐编辑器
  - Markdown All in One插件
  - Markdown Preview Enhanced插件
  - markdownlint插件
- 建议使用Vi的编辑模式

## 三、如何提交任务完成报告

### 1、fork上游（upstream）仓库

称山科智绘感知兴趣小组下的小组任务仓库（地址：<https://gitee.com/mapping-perception/group-tasks.git>）为上游仓库。该仓库已经内部开源，大家在提交自己的任务完成报告之前，需要首先fork这个上游仓库到自己的帐户下。

- **进入自己的gitee，点击进入山东科技大学-石波**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125019_3f429eff_8147644.png "屏幕截图.png")

- **点击进入内源**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125135_55970218_8147644.png "屏幕截图.png")

- **可看到内源仓库：山科智绘感知兴趣小组/小组任务，点击进入**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125233_ac6cec5a_8147644.png "屏幕截图.png")

- **从上方仓库地址点击进入仓库**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125317_4132985c_8147644.png "屏幕截图.png")

- **找到右上方的forked**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125402_d50cef27_8147644.png "屏幕截图.png")

- **点击forked后可见，选择自己有自己名字的仓库并点击确认**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125433_2ec80ea8_8147644.png "屏幕截图.png")

### 2、SourceTree进行仓库的克隆（clone）及准备工作

- **进入到自己forked的仓库，找到克隆/下载点击选择复制仓库地址**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125810_740ee151_8147644.png "屏幕截图.png")

- **在电脑上创建“work”文件夹（不建议存放在桌面）**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/132532_367513b7_8147644.png "屏幕截图.png")

- **打开sourcetree，选择clone,将复制的仓库地址粘贴在第一空行，第二空行浏览选择自己在桌面新建的空文件夹，然后点击克隆(如果克隆要求输入账号密码，即为gitee的，一旦密码输入错误无法更正，可在电脑自带的凭据管理器中管理Windows凭据即可删除此次错误登入):**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/153256_d05a34d3_8147644.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/132700_087127e1_8147644.png "屏幕截图.png")

- **将仓库克隆好了之后，需要新建一个上游，先将兴趣小组的地址复制下来**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/134138_92f0aeca_8147644.png "屏幕截图.png")

- **然后进入sourcetree上自己新克隆的仓库，找到右上角的设置，点进去之后发现下方有一个*添加*，点击添加，然后远端名称设为*upstream*,再把刚刚复制的仓库地址添加到*URL/路径*上，点击确定(upstream是以后每次提交pull request的仓库地址)**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/134502_44ea437b_8147644.png "屏幕截图.png")

- **点击确定后，点击*高级*，将使用全局用户配置的勾去掉，将*全名*改为个人姓名，*电子邮件地址*改为QQ邮箱,然后点击确定**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/135012_fcb23069_8147644.png "屏幕截图.png")

### 3、任务完成报告的提交/推送

- **每周提交作业前，需先在sourcetree上*从远端拉取*进行拉取upstream，拉取完后先进行推送，以更新个人仓库**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/140055_bf67b830_8147644.png "屏幕截图.png")

- **在个人仓库中新建一个文件夹，格式为”*第几周作业*“，然后将自己要提交的作业放到里面，则可以看到sourcetree的变化，显现出未暂存文件，然后点击+将要提交的作业暂存**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/140439_752d6f0b_8147644.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/140612_b3240c8d_8147644.png "屏幕截图.png")

- **点击上方提交，提交旁要写清楚提交了什么，之后再点击推送，注意是推送到origin**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/141133_f424e1fc_8147644.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/141155_2353523b_8147644.png "屏幕截图.png")

- **打开gitee,可以看到提交记录，然后在个人名下的小组任务仓库中进行pull request(注意，标题以及相关的内容一定要非常详细），填写完内容之后点击创建即可，pull request经审查没问题后即会被合并到上游仓库**

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/141401_1b58dfbd_8147644.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/141334_ba82852f_8147644.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/141531_bd1ebc1f_8147644.png "屏幕截图.png")
