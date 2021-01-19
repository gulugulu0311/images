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

![ ](https://images.gitee.com/uploads/images/2021/0119/125019_3f429eff_8147644.png "屏幕截图.png")

- **点击进入内源**

![ ](https://images.gitee.com/uploads/images/2021/0119/125135_55970218_8147644.png "屏幕截图.png")

- **可看到内源仓库：山科智绘感知兴趣小组/小组任务，点击进入**

![ ](https://images.gitee.com/uploads/images/2021/0119/125233_ac6cec5a_8147644.png "屏幕截图.png")

- **从上方仓库地址点击进入仓库**

![ ](https://images.gitee.com/uploads/images/2021/0119/125317_4132985c_8147644.png "屏幕截图.png")

- **找到右上方的forked**

![ ](https://images.gitee.com/uploads/images/2021/0119/125402_d50cef27_8147644.png "屏幕截图.png")

- **点击forked后可见，选择自己有自己名字的仓库并点击确认**

![ ](https://images.gitee.com/uploads/images/2021/0119/125433_2ec80ea8_8147644.png "屏幕截图.png")

### 2、SourceTree进行仓库的克隆（clone）及准备工作

- **进入到自己forked的仓库，找到克隆/下载点击选择复制仓库地址**

![ ](https://images.gitee.com/uploads/images/2021/0119/125810_740ee151_8147644.png "屏幕截图.png")

- **在电脑上创建“work”文件夹（不建议存放在桌面）**

![ ](https://images.gitee.com/uploads/images/2021/0119/132532_367513b7_8147644.png "屏幕截图.png")

- **打开sourcetree，选择clone,将复制的仓库地址粘贴在第一空行，第二空行浏览选择自己在桌面新建的空文件夹，然后点击克隆(如果克隆要求输入账号密码，即为gitee的，一旦密码输入错误无法更正，可在电脑自带的凭据管理器中管理Windows凭据即可删除此次错误登入):**

![ ](https://images.gitee.com/uploads/images/2021/0119/153256_d05a34d3_8147644.png "屏幕截图.png")

![ ](https://images.gitee.com/uploads/images/2021/0119/132700_087127e1_8147644.png "屏幕截图.png")

- **将仓库克隆好了之后，需要新建一个上游，先将兴趣小组的地址复制下来**

![ ](https://images.gitee.com/uploads/images/2021/0119/134138_92f0aeca_8147644.png "屏幕截图.png")

- **然后进入sourcetree上自己新克隆的仓库，找到右上角的设置，点进去之后发现下方有一个*添加*，点击添加，然后远端名称设为*upstream*,再把刚刚复制的仓库地址添加到*URL/路径*上，点击确定(upstream是以后每次提交pull request的仓库地址)**

![ ](https://images.gitee.com/uploads/images/2021/0119/190644_233e878c_8147644.png "屏幕截图.png")

![ ](https://images.gitee.com/uploads/images/2021/0119/190901_bcf1c7ba_8147644.png "屏幕截图.png")

![ ](https://images.gitee.com/uploads/images/2021/0119/134502_44ea437b_8147644.png "屏幕截图.png")

- **点击确定后，点击*高级*，将使用全局用户配置的勾去掉，将*全名*改为个人姓名，*电子邮件地址*改为QQ邮箱,然后点击确定**

![ ](https://images.gitee.com/uploads/images/2021/0119/135012_fcb23069_8147644.png "屏幕截图.png")

### 3、任务完成报告的提交/推送

- **每周提交作业前，需先在sourcetree上*从远端拉取*进行拉取upstream以此将个人仓库和上游仓库进行同步，拉取完后进行推送，拉取时，若远端改为upstream后下面要拉取的远端分支没有显现如图1，则点击刷新即可，结果如图2，然后点击拉取即可**

![ ](https://images.gitee.com/uploads/images/2021/0119/192427_23a84c28_8147644.png "屏幕截图.png")

![ ](https://images.gitee.com/uploads/images/2021/0119/192555_830e90ad_8147644.png "屏幕截图.png")

# 1. ![ ](https://images.gitee.com/uploads/images/2021/0119/192859_f595455e_8147644.png "屏幕截图.png")

# 2. ![ ](https://images.gitee.com/uploads/images/2021/0119/193128_862e14a4_8147644.png "屏幕截图.png")

- **拉取完后，可以看到推送上有多出的内容，点击推送，将从上游仓库拉取的更新内容推送到origin，实现上游仓库和个人仓库的同步**

![ ](https://images.gitee.com/uploads/images/2021/0119/193339_85626b0d_8147644.png "屏幕截图.png")

![ ](https://images.gitee.com/uploads/images/2021/0119/193739_bcf87fc0_8147644.png "屏幕截图.png")

- **在个人仓库中新建一个文件夹，格式为”*第几周作业*“，然后将自己要提交的作业放到里面，则可以看到sourcetree的变化，显现出未暂存文件，然后点击+将要提交的作业暂存**

![ ](https://images.gitee.com/uploads/images/2021/0119/140439_752d6f0b_8147644.png "屏幕截图.png")

![ ](https://images.gitee.com/uploads/images/2021/0119/140612_b3240c8d_8147644.png "屏幕截图.png")

- **点击上方提交，提交旁要写清楚提交了什么，之后再点击推送，注意是推送到origin**

![ ](https://images.gitee.com/uploads/images/2021/0119/141133_f424e1fc_8147644.png "屏幕截图.png")

![ ](https://images.gitee.com/uploads/images/2021/0119/141155_2353523b_8147644.png "屏幕截图.png")

- **打开gitee,可以看到提交记录，然后在个人名下的小组任务仓库中进行pull request(注意，标题以及相关的内容一定要非常详细），填写完内容之后点击创建即可，pull request经审查没问题后即会被合并到上游仓库**

![ ](https://images.gitee.com/uploads/images/2021/0119/141401_1b58dfbd_8147644.png "屏幕截图.png")

![ ](https://images.gitee.com/uploads/images/2021/0119/141334_ba82852f_8147644.png "屏幕截图.png")

![ ](https://images.gitee.com/uploads/images/2021/0119/141531_bd1ebc1f_8147644.png "屏幕截图.png")

### 4、关于作业提交后如何进行修改

- **方法一：在个人电脑上的仓库中修改好之后再用sourcetree提交：**

  - 在自己电脑上的仓库中打开并修改好了文件之后，会看到sourcetree出现如下改变，未暂存文件显示出修改过的文件，前方带有黄标

  - 按原来提交作业的步骤进行即可，记得在提交修改的时候在旁边的内容栏处写明提交了什么。提交推送完之后，gitee上的文件即修改成功，无需重新pull request

![ ](https://images.gitee.com/uploads/images/2021/0119/182811_cf4f9a88_8147644.png "屏幕截图.png")
  
- **方法二：直接在gitee上修改（当要修改的地方多的时候不建议此方法，因为无法一边修改一边检测）：**

  - 从gitee上打开自己的仓库找到要修改的文件

  - 点开文件，右方有一个编辑，点击编辑后即可对文件直接修改

  - 修改好后，最下方会有一个提交，提交即可，无需重新pull request

![ ](https://images.gitee.com/uploads/images/2021/0119/183401_79782ad3_8147644.png "屏幕截图.png")

![ ](https://images.gitee.com/uploads/images/2021/0119/183614_aa0f267c_8147644.png "屏幕截图.png")

![ ](https://images.gitee.com/uploads/images/2021/0119/183716_185b9f18_8147644.png "屏幕截图.png")