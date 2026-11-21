# 单页 HTML 分享

把要分享的 HTML 放在 `share/<随机 ID>/<文件名>.html`，通过 GitHub Pages 发布。例如，`share/a8f29c4e/room.html` 的访问地址是 `https://js-shows.com/share/a8f29c4e/room.html`。

- 每次发布使用一个新的随机 ID。文件名使用小写英文、数字和连字符。
- 保留 HTML 原有的交互和布局。需要随页面发布的相对路径资源放在同一个目录。
- 分享文件默认不加入主页作品列表。页面及其资源会随仓库公开，持有链接的人可以转发。
- 撤下时提交删除对应的分享目录。GitHub Pages 重新部署后旧网址会失效，文件可能仍可从 Git 历史获取。
