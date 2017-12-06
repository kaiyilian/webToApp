# webToApp
网页跳转app

实现直接从浏览器打开app。

方法：

1.a标签直接通过href跳转。
```
<a class="item" href="weixin://">微信 a 直接href</a>
```

2.通过iframe标签跳转。

3.通过js中window.location重定向方法跳转。

4.通过window.open打开第三方的下载页。如：应用宝等<br>
```
window.open("http://a.app.qq.com/o/simple.jsp?pkgname=com.travel.maintab&g_f=991653");//adf
```
