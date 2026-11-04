# SRM Warmup Timer · GitHub Pages 网页版

SRM Warmup Timer 是一个无需后端的 HTML/CSS/JavaScript 网页应用，可直接发布到 GitHub Pages。网页包含中文倒计时提醒、多组热身计划、模板保存/重命名/读取、比赛时间倒计时和发车前 5 分钟全屏红色提醒。

## 发布（GitHub 网页操作）

1. 登录 GitHub，点击 **New repository**，取名 `srm-warmup-timer`，选择 **Public**，创建仓库。
2. 进入仓库，点击 **Add file → Upload files**。上传本目录的 `index.html` 和 `.nojekyll`（README 可选）；提交到 `main` 根目录。注意是**解压上传文件**，不要仅把 ZIP 上传到仓库。
3. 点击 **Settings → Pages**，在 **Build and deployment → Source** 选择 **Deploy from a branch**；Branch 选 `main`，Folder 选 `/(root)`，保存。
4. 等待部署后，在 **Settings → Pages** 点击 **Visit site**。站点地址格式：`https://你的用户名.github.io/srm-warmup-timer/`。

以后只要覆盖仓库里的 `index.html`，就能更新网页版本。

## 注意

- 保存在网页的热身计划存在**每位使用者自己的浏览器本地存储**；不会自动共享或跨设备同步。要换设备请使用应用内 JSON 导出/导入功能。
- 浏览器的中文语音播报依赖系统语言和语音引擎，部分设备需要首次点击按钮来激活音频。
- 手机锁屏、浏览器后台、省电设置可能影响定时播放或警告显示；比赛当天建议另外使用手机系统闹钟。
- 本软件没有服务器端用户账户，也没有实现云端计划共享。

GitHub 文档：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site