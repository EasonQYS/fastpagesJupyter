# 自动将 markdown 文件转换为 Posts（博客）

命名格式为 `YYYY-MM-DD-*.md`。 例如:

```shell
2020-01-28-My-First-Post.md
2012-09-12-how-to-write-a-blog.md
```
支持中文。

- 当心错误的命名!  很容易将 `YYYY-MM-DD-`的最后一个破折号落下。 并且，破折号后面的一个字符只能是文字而不能是符号。

在Markdown文档中，最上面的几行作为表头。内容如下（可以缺省部分内容）：

  ```yaml
  ---
  title: "标题"
  summary: "概要"
  toc: true
  comments: true
  image: images/some_folder/your_image.png
  categories: [fastpages, jupyter]
  ---
  ```
注意这里的代码是以YAML格式写的，必须保证正确。

# 插入图片

将图片放到/myblog/images/路径下。

Markdown格式如下：
```
 ![](https://easonqys.github.io/myblog/images/name.jpg "title")
```

# 相关资源

- [Jekyll posts](https://jekyllrb.com/docs/posts/)
- [Example markdown post](https://github.com/fastai/fastpages/blob/master/_posts/2020-01-14-test-markdown-post.md)
