---
## 🌱 一、第一次把本地项目连到 GitHub

如果 GitHub 上已经创建了仓库：

```bash
git init
git remote add origin 仓库地址
```

查看是否连接成功：

```bash
git remote -v
```
---

## 🧠 二、日常开发的标准流程（你以后会反复用）

### 1️⃣ 修改代码

写代码、保存文件。

---

### 2️⃣ 查看状态

```bash
git status
```

看哪些文件被修改。

---

### 3️⃣ 暂存修改（进入 staging area）

```bash
git add .
```

（VS Code 里点 + 也是这个操作）

---

### 4️⃣ 生成快照（本地提交）

```bash
git commit -m "写清楚这次改了什么"
```

这一步只在本地。

---

### 5️⃣ 上传到 GitHub

```bash
git push origin main
```

或者第一次：

```bash
git push -u origin main
```

---

## 🌍 三、远程有更新怎么办？

```bash
git pull origin main
```

= 拉远程代码下来并合并。

---

## 📥 四、如果你换电脑

下载远程仓库：

```bash
git clone 仓库地址
```

clone = 下载整个项目历史。

---

## 🧭 五、你现在需要记住的核心概念

工作区 → 你正在编辑的文件
staging area → git add 后的缓存区
commit → 本地历史快照
push → 上传到远程
pull → 拉远程更新
origin → 远程仓库名字
main → 当前分支

---

## 🔁 六、最常用的五条命令（够用版）

```bash
git status
git add .
git commit -m "xxx"
git push
git pull
```

你真的记住这 5 条就能写项目了。

---

## 🎯 七、判断口诀

改完代码 → add
准备保存版本 → commit
准备同步 GitHub → push
别人改了代码 → pull
新电脑开始 → clone

---
