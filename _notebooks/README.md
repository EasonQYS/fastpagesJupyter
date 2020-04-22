# 自动将 Jupyter 笔记本转换为 Posts（博客）

命名方式形如： `YYYY-MM-DD-*.ipynb`。 例如:

```shell
2020-01-28-My-First-Post.ipynb
2012-09-12-how-to-write-a-blog.ipynb
```
支持中文名。

- 当心错误的命名!  很容易将 `YYYY-MM-DD-`的最后一个破折号落下。 并且，破折号后面的一个字符只能是文字而不能是符号。

如果命名错误， `fastpages` 会尝试以上传时间加原名称来纠正。但我们仍然建议你规范命名。

在Jupyter中，表头是文档中的第一个单元格。并且是markdown格式的单元格。内容如下（可以缺省）：

  ```markdown
  # "标题"
  > "概要"
  
  - toc: true
  - badges: true
  - comments: true
  - categories: [fastpages, jupyter]
  - image: images/some_folder/your_image.png
  - author: A & B
  ```

注意这里的代码是以YAML格式写的，必须保证正确。

看[这里](https://github.com/fastai/fastpages#writing-blog-posts-with-jupyter)了解更多。
