# 自动将 微软（MicroSoft） Word (*.docx) 文档转换为 Blog Posts（博客）

_提示: 你可以将 Google Docs 通过文件菜单先转换成 Word Docs再上传。具体操作为：在菜单选择 Download > Microsoft Word (.docx)_

文档仅支持后缀名为.docx的格式文档，图片可能无法显示（作者表示可以自动显示）。

## 用法

1. 建立一个Word文档(必须是.docx) ，写好博客内容。

2. 以 `YYYY-MM-DD-*.docx` 格式命名。上传至仓库的 `/_word` 文件夹。 例如 `2020-01-28-My-First-Post.docx`。

    - 当心错误的命名!  很容易将 `YYYY-MM-DD-`的最后一个破折号落下。 并且，破折号后面的一个字符只能是文字而不能是符号。下面是正确的例子：

        ```shell
        2020-01-28-My-First-Post.docx
        2012-09-12-how-to-write-a-blog.docx
        ```
        支持中文。

    - 如果命名错误, `fastpages` 会根据上传时间加原文件名尝试修正。但我们仍然建议您规范命名。

## 参考资料
[following the instructions in this blog post](https://www.fast.ai/2020/01/18/gitblog/).
