目的：说明如何用Github写文章、并发布到公开可访问地址。

## 使用过程描述
1. 用帐号登录 [github](www.github.com)，帐号联系杨姣

2. 你看到一个仓库叫做 **matrixport-article.github.io**
![](https://raw.github.com/matrixport-article/matrixport-article.github.io/master/_images/1/repo.png)

3. 点击进入，你会看到一个目录，找到名叫 post 的目录，这就是你要创建文章的地方
![](https://raw.github.com/matrixport-article/matrixport-article.github.io/master/_images/1/post.png)

4. 你看到的一个 file 就是一篇文章，点击 create new file 就是创建一篇文章
![](https://raw.github.com/matrixport-article/matrixport-article.github.io/master/_images/1/create.png)

5. 你需要按格式要求写文章标题，格式要求`YYYY-MM-DD-YOUR-TITLE.markdown`。即：如果你希望用户看到的格式标题是 May Report 并且用户看到发布是5月12号，那么你需要写：2020--5-12-May-Report.markdown。标题内容里空格都写作-，一定要按这个格式要求填写在这个地方。

6. 下面的编辑框里是你要发布的内容，请按照 [markdown语法](https://www.jianshu.com/p/191d1e21f7ed)书写。编辑过程中可以随时点击旁边的 Preview 预览用户界面效果。

7. 完成后，点击 commit to master 按钮。
![](https://raw.github.com/matrixport-article/matrixport-article.github.io/master/_images/1/commit.png)

8. 等同步完成，你就可以访问我们提供的地址，来看线上效果了。

### 如何存放图片

* 找到 _images 文档，如下，这就是你存放图片的地方。
![](https://raw.github.com/matrixport-article/matrixport-article.github.io/master/_images/1/image.png)

* 进去image文件夹、你可以为不同文章创建不同的目录，方便后续整理。
![](https://raw.github.com/matrixport-article/matrixport-article.github.io/master/_images/1/folder.png)

* 图片的命名建议能体现出来内容，因为后续我们需要它来文章里添加图片。
![](https://raw.github.com/matrixport-article/matrixport-article.github.io/master/_images/1/name.png)

### 如何插入图片

* 到编辑器页面，按照以下格式插入图片
`![](https://raw.github.com/这里是帐号名/这里是仓库名/master/放图片的一级目录/文件夹目录/图片名称)`

* 例如：存在在 _images 文档下子文件夹杂 1 下面的一个名为 repo.png 的图片，写为：
`![](https://raw.github.com/matrixport-article/matrixport-article.github.io/master/_images/1/repo.png)`


----

## 这是作者写的
![](https://raw.github.com/matrixport-article/matrixport-article.github.io/master/_images/1/edit.png)

## 这是读者看的
![](https://raw.github.com/matrixport-article/matrixport-article.github.io/master/_images/1/preview.png)

## 这是访问地址
commit 后即会生成公开地址，地址格式为 `https://report.matrixport.dev/YYYY/MM/DD/Your-Tile.html`。
这篇文章 post 命名为`2020--5-12-Please-Follow-This-Instruction.markdown`，所以文章生成的 url 是 `https://report.matrixport.dev/2020/05/12/Please-Follow-This-Instruction.html`。
