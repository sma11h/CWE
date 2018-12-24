## 语法
统一规定所有文档均以**GFM**`（GitHub Flavored Markdown）`语法编写，后缀为`.md`。如果你不懂GFM语法，没关系，这里有个不错的[项目](https://github.com/guodongxiaren/README)对GFM进行了介绍，里面的讲解和示例可以很好的帮助你完成文档的编写。
## tui.editor
[tui.editor](https://github.com/nhnent/tui.editor)是一个支持GFM的编译器,可以用它快速编辑GFM风格的文档。简单的使用方法：  
**安装**
```
>mkdir tui-editor
>cd tui-editor
>bower install --save tui-editor
```
**部署**
```
>rename bower_components lib
>mkdir dist
>copy lib\tui-editor\dist dist\
>mkdir html
>copy lib\tui-editor\examples\example00-demo.html html\tui-editor.html
```
**使用**  ~~~~
使用FireFox、Chrome等浏览器打开tui-editor.html即可使用。