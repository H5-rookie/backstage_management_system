# backstage_management_system

# 名称：后台管理平台

用途：商品，商家和用户的数据的平台

# 技术选型

Vue + Vue router + ElementUI + axios/fetch +echarts

# 1.  创建项目

```bash
vue create mysys
```



![1608191100000](项目步骤.assets/1608191100000.png)

![1608191146967](项目步骤.assets/1608191146967.png)

![1608191163155](项目步骤.assets/1608191163155.png)

​	![1608191193105](项目步骤.assets/1608191193105.png)

![1608191232441](项目步骤.assets/1608191232441.png)



进行到项目目录中，然后运行

```bash
npm run serve
```

在根目录下面，新建一个 vue.config.js 文件，填入以下内容

```bash
module.exports = {
    lintOnSave:false
}
```

运行 以下命令

```bash
git add * // 把文件提交暂存区
git commit -m "提交vue.config.js"
```





# [创建 github仓库](https://github.com/)

![1608191414880](项目步骤.assets/1608191414880.png)

![1608191508729](项目步骤.assets/1608191508729.png)

# 把本地代码提交远程仓库

把线上的 https 地址复制一下

![1608191935598](项目步骤.assets/1608191935598.png)

https://github.com/thomaslwq/myadmin.git

添加远程地址到本地

```bash
git remote add origin https://github.com/thomaslwq/myadmin.git
```

运行 

```bash
git remote -v 
```





![1608192074630](项目步骤.assets/1608192074630.png)

推送本地代码到远程分支

```bash
git push -u origin master
```

![1608192443199](项目步骤.assets/1608192443199.png)





# git 命令

提交代码

```bash
git status
git add * // git add README.md  git add .
git commit -m "提交API文档"
git status  // 看一下本地有没有修改
// 拉取远程分支代码
git pull origin master // 如果有冲突的情况 手动合并冲突
git push origin master
```

