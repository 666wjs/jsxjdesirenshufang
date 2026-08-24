# 个人网站（模板 v0.4）

## 一、以后怎么在线改内容

1. 打开这个仓库的网页版，进入 `content.js` 文件；
2. 点右上角的铅笔图标（Edit this file）；
3. 只修改文字部分：`about`（个人介绍）、`strengths`（个人优势）、
   `thinking`（思考集）、`library`（图书馆）、`contact`（联系本人）；
4. 点绿色 **Commit changes** 保存；
5. 等约 1 分钟，网站自动更新。

模板、样式、图片位置都不用动，以后改内容永远只碰这一个文件。

## 二、发布到 GitHub Pages（一次性）

1. 在 [github.com](https://github.com) 登录你的账号，点右上角 **+ → New repository**，
   仓库名随意（例如 `personal-site`），选 **Public**，不要勾选任何初始化选项；
2. 在本地这个文件夹里打开终端，执行（把 URL 换成你自己的仓库地址）：

   ```bash
   git remote add origin https://github.com/你的用户名/personal-site.git
   git push -u origin main
   ```

3. 打开仓库 → **Settings → Pages**，Source 选 **Deploy from a branch**，
   分支选 `main`，路径 `/`，点 **Save**；
4. 等 1–2 分钟，网站地址就是：

   `https://你的用户名.github.io/personal-site/`

## 三、访客权限说明

- 访客通过网址打开的是纯静态页面，**只能看，没有任何编辑入口**；
- 只有登录你本人的 GitHub 账号才能改 `content.js`，天然只读；
- 注意：GitHub Pages 免费版要求仓库公开，所以"知道网址的人"都能看到页面内容。
  如果你希望只有指定的人能看（邀请制），需要 GitHub Pro 的私有 Pages，
  或换带访问控制的托管方案，可以再联系我调整。

## 四、本地预览

直接双击 `index.html` 即可在浏览器预览，正文来自 `content.js`。
