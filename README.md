# webToApp
网页跳转app

实现直接从浏览器打开app。

方法：

1.a标签直接通过href跳转。
```
<a class="item" href="weixin://">
  a标签 href跳转
</a>
```

2.通过iframe标签跳转。

3.通过js中window.location重定向方法跳转。

4.通过window.open打开第三方的下载页。如：应用宝等<br>
```
//跳转到应用宝之后，会自动检测，本地有没有该app
//如果有，则直接打开app
//如果没有，则停留在下载页面
window.open("http://a.app.qq.com/o/simple.jsp?pkgname=com.travel.maintab&g_f=991653");
```
