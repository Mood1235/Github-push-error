创建仓库

```
点击头像处“+”
New repository
填写仓库名称“Repository name”
```

在需要推送到仓库的目录下打开git bash，依次输入以下命令

```
git init	#初始化目录
git add .	#
git commit -m "备注"
git remote add origin https://github.com/仓库地址.git
git branch -M main
git push -u origin main		#推送
```

10054报错，SSL访问不到

```
 输入以下命令
 git config lfs.推送的库的名称/lfs.locksverify fals
 
 推送的库的名称：必须是完整的，从https开始到git结束
```



