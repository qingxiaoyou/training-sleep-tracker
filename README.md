# 训练睡眠记录 PWA

这是一个可以部署到 GitHub Pages 的离线 PWA。

## GitHub Pages 发布步骤

1. 打开 GitHub，登录账号。
2. 新建仓库，推荐名字：`training-sleep-tracker`。
3. Visibility 选 `Public`。
4. 创建后点 `Add file` -> `Upload files`。
5. 上传本文件夹里的全部文件：
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `.nojekyll`
   - `README.md`
6. 点 `Commit changes`。
7. 进入仓库 `Settings` -> `Pages`。
8. Source 选择 `Deploy from a branch`。
9. Branch 选择 `main`，Folder 选择 `/root`。
10. 保存后等 1-3 分钟。

发布成功后，地址一般是：

`https://你的用户名.github.io/training-sleep-tracker/`

## iPhone 使用

1. 用 iPhone Safari 打开上面的 GitHub Pages 地址。
2. 等页面加载完成。
3. 点分享按钮。
4. 选择“添加到主屏幕”。
5. 以后从桌面图标打开。

第一次打开后会缓存页面，之后断网也能使用。
