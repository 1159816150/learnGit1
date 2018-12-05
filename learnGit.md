####1.首先是下载和安装好typora和git 我的是在网上直接安装的widows版本

####2.打开Git bash用以下语句初始化自己的用户名和绑定邮箱

```
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
```

####3.在任意一个盘创建一个空目录，我的目录就是在G盘创建了一个learnGit

G:\Git\learnGit

####4.打开git bash 以下代码将用于生成一个ssh密钥，并将之添加到ssh代理中，此时你的电脑会生成一个.ssh的文件

![1543990384682](https://raw.githubusercontent.com/1159816150/learnGit1/master/image/1543990384682.png)

![1543990435221](https://raw.githubusercontent.com/1159816150/learnGit1/master/image/1543990435221.png)

###5.使用ssh密钥密码

可生成你的密钥密码，每次上传文件时都需要输入。

![1543993689034](https://raw.githubusercontent.com/1159816150/learnGit1/master/image/1543993689034.png)

####6.此时已生成密钥，要向GitHub添加新的ssh密钥

![1543990608278](https://raw.githubusercontent.com/1159816150/learnGit1/master/image/1543990608278.png)

####7.接下来是配置ssh秘钥，这个花了我不少时间，我有点乱

先点击GitHub的设置 点击左边的ssh and gpg keys 点击添加ssh密钥 如图所示 

![1543990781024](https://raw.githubusercontent.com/1159816150/learnGit1/master/image/1543990781024.png)

点击进去他需要你输入一个key，一开始我以为是Git输入的密码，后来才知道是要输入.ssh文件里面id_rsa.pub文件的内容，表示你的密钥，输入后绑定即可完成GitHub的ssh密钥设置。

####8.测试是否成功配置密钥



#### ![1543993973851](https://raw.githubusercontent.com/1159816150/learnGit1/master/image/1543993973851.png)

####9.最后是提交文件到GitHub仓库，具体内容可参照链接学习，步骤一样的。

http://www.markdown.cn/#blockquotes

![1543993736749](https://raw.githubusercontent.com/1159816150/learnGit1/master/image/1543993727849.png)