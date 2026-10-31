# ENTP Focus

这是一个个人单文件注意力管理网页应用，灵感来自 ENTP自强手册 项目（https://github.com/TANGuoGUO/entp-manual）的想法，实现为原创代码。所有数据仅加密存储在本地浏览器中（密码锁，AES-GCM）。在 iPhone 上安装：用 Safari 打开，点按分享，选择「添加到主屏幕」。

加密备份使用固定文件名 `entp-focus-backup.encrypted.json`，再次导出时覆盖同名文件。应用内会在数据有改动后提醒备份，并在解锁时若距上次成功备份已超过一周则提醒。在 iPhone 上点「立即备份到文件」，通过系统分享存到「文件」。
