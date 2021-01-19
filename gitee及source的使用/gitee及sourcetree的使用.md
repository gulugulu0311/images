# 1.关于forked仓库的操作

## 步骤

**1.进入自己的gitee，点击进入山东科技大学-石波：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125019_3f429eff_8147644.png "屏幕截图.png")

**2.点击进入内源：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125135_55970218_8147644.png "屏幕截图.png")

**3.可看到内源仓库：山科智绘感知兴趣小组/小组任务，点击进入：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125233_ac6cec5a_8147644.png "屏幕截图.png")

**4.从上方仓库地址点击进入仓库：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125317_4132985c_8147644.png "屏幕截图.png")

**5.找到右上方的forked：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125402_d50cef27_8147644.png "屏幕截图.png")

**6.点击forked后可见，选择自己有自己名字的仓库并点击确认：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125433_2ec80ea8_8147644.png "屏幕截图.png")

# 2.关于在sourcetree上clone仓库的操作

## 步骤

**1.进入到自己forked的仓库，找到克隆/下载点击选择复制仓库地址：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/125810_740ee151_8147644.png "屏幕截图.png")

**2.先在桌面上新建一个空文件夹:**
![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/132532_367513b7_8147644.png "屏幕截图.png")

**3.打开sourcetree，选择clone,将复制的仓库地址粘贴在第一空行，第二空行浏览选择自己在桌面新建的空文件夹，然后点击克隆<font color=red>(如果克隆要求输入账号密码，即为gitee的，一旦密码输入错误无法更正，可在电脑自带的凭据管理器中管理Windows凭据即可删除此次错误登入)</font>:**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/132700_087127e1_8147644.png "屏幕截图.png")

# 3.sourcetree和gitee的使用和管理

## 内容

**1.将仓库克隆好了之后，需要新建一个上游，先将兴趣小组的地址复制下来：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/134138_92f0aeca_8147644.png "屏幕截图.png")

**2.然后进入sourcetree上自己新克隆的仓库，找到右上角的设置，点进去之后发现下方有一个*添加*，点击添加，然后远端名称设为*upstream*,再把刚刚复制的仓库地址添加到*URL/路径*上，点击确定<font color=red>(upstream是以后每次提交pull request的仓库地址)</font>：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/134502_44ea437b_8147644.png "屏幕截图.png")

**3.点击确定后，点击*高级*，将使用全局用户配置的勾去掉，将*全名*改为个人姓名，*电子邮件地址*改为QQ邮箱,然后点击确定：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/135012_fcb23069_8147644.png "屏幕截图.png")

#### *<font color=red>(以上步骤是仅在新克隆仓库时才需操作，并非每次交作业都需要)</font>*

**4.每周提交作业前，需先在sourcetree上*从远端拉取*进行拉取upstream，拉取完后先进行推送，以更新个人仓库：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/140055_bf67b830_8147644.png "屏幕截图.png")

**5.在个人仓库中新建一个文件夹，格式为”*第几周作业*“，然后将自己要提交的作业放到里面，则可以看到sourcetree的变化，显现出未暂存文件，然后点击+将要提交的作业暂存：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/140439_752d6f0b_8147644.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/140612_b3240c8d_8147644.png "屏幕截图.png")

**6.点击上方提交，提交旁要写清楚提交了什么，之后再点击推送，注意是推送到origin：**![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/141133_f424e1fc_8147644.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/141155_2353523b_8147644.png "屏幕截图.png")

**7.打开gitee,可以看到提交记录，然后在个人名下的小组任务仓库中进行pull request<font color=red>(注意，标题以及相关的内容一定要非常详细）</font>,填写完内容之后点击创建即可,pull request经审查没问题后即会被合并到上游仓库**
![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/141401_1b58dfbd_8147644.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/141334_ba82852f_8147644.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0119/141531_bd1ebc1f_8147644.png "屏幕截图.png")


## <font color=red>要求：每次以markdown的形式提交自己的任务完成情况（技术报告）</font>