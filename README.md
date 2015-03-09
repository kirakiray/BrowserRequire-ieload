# BrowserRequire-ieload
Make ie9- support BrowserRequire.

让ie5.5—ie9（默认ie10+才能支持）支持BrowserRequire。

###优势

* 兼容低版本ie的代码与主体分离，有效降低BrowserRequire文件大小；
* 删减掉浏览器断定逻辑，使得BrowserRequire更加快速；
* 按需添加插件（比如开发移动端web，就不需要兼容低版本ie）。

###目录介绍

dist——ieload压缩文件

src——ieload插件源代码

###使用插件

####1.添加插件
```html
<script src="js/br.js"></script>
<!--框架主文件-->
<script src="js/br-ieload.js"></script>
<!--ieload插件-->
```

或采用异步方式添加，详情请查看[插件使用文档](https://github.com/kirakiray/BrowserRequire/wiki/插件使用和介绍)
