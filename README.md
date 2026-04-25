# 私人日记网页部署包

这个目录可以直接部署到 GitHub Pages、Vercel、Netlify 或任意静态网页托管服务。

入口文件：
- `index.html`

附带文件：
- `manifest.webmanifest`：手机端安装到主屏需要
- `sw.js`：基础离线缓存
- `icon.png` / `icon-512.png`：应用图标

注意：
- 日记文字保存在当前浏览器的 `localStorage`。
- 附件保存在当前浏览器的 `IndexedDB`。
- 不同设备之间不会自动同步。
- 换手机或换浏览器前，请在程序里导出 JSON 备份，再到新设备导入。
