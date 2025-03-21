# 提交

## 初始化git仓库信息 拉取文档

```git
git clone <仓库路径> [本地目录]

git clone https://github.com/169LI/book-code.git [直接在选好的目录下进行克隆命令，不需建本地目录] 
```

## 进行个人代码目录增加后

```git
git add .
git commit -m "输入提交章节信息"
git pull # 拉取处理冲突，不修改他人代码，只在自己的目录上修改一般不会引起冲突
git push # 推送
```
