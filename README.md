# HTML 格式转换器

在线地址：<https://jessper2024.github.io/htmlconvert/>

这个静态网页把 SingleFile 保存的 HTML/HTM 文档清理成可导入 Sigil 的单章 XHTML。

## 使用方式

1. 选择或拖入一个或多个 SingleFile HTML 文件。
2. 点击“批量转换”。
3. 下载生成的 `原文件名-Sigil.xhtml`，再在 Sigil 中选择“添加现有文件”。

页面顶部可以选择处理类型：微信公众号文章或 Notion 文档。Notion 模式会从“作者”和“发布时间”属性命名，并只保留页面正文内容区，避免把属性面板、Relations 等编辑控件混进正文。

工具只生成 XHTML，不生成或下载 EPUB。转换完全在每位使用者的浏览器中完成，原始文件不会上传到服务器。

外链图片仍受原网站链接有效期影响；内嵌图片会随 XHTML 保留。
