# URL跳转出现在哪里



首先得思考一下，什么功能需要做URL跳转。大部分的URL跳转都出在登录页面，比如游客在论坛里评论，需要登录才能评论，这时候登录区就会有一个他之前浏览页面的参数值`url=http://xxx.luntan.com?id=123`，在商店看到某样商品想加入购物车时也需要登录，其他类似的跳转功能还有短信验证码认证之后跳转、分享或者收藏之后跳转、给第三方授权之后跳转，他们的共同特点都是从一个页面为了某种操作进入另一个页面，操作之后返回原页面继续浏览。大部分URL跳转都发现在登录的地方，常见的参数值有return、redirect、url、jump、goto、target、link等。



---

## 案例

[支付宝某分站任意URL跳转](http://www.anquan.us/static/bugs/wooyun-2014-054459.html)

[利用京东URL跳转漏洞进行的邮件钓鱼事件(ext参数使用base64加密做跳转)](http://www.anquan.us/static/bugs/wooyun-2015-0113117.html)

[人人网URL跳转](http://www.anquan.us/static/bugs/wooyun-2012-06961.html)

[腾讯邮箱附件预览页面URL跳转](http://www.anquan.us/static/bugs/wooyun-2014-069277.html)

[使用主题安装URL跳转](https://hackerone.com/reports/101962)

[登录任何商店的URL跳转](https://hackerone.com/reports/103772)

---

### 参考：

1. [https://www.secpulse.com/archives/67064.html](https://www.secpulse.com/archives/67064.html)
2. [https://mp.weixin.qq.com/s/ZUoOY5NjcEL3bFvRePwFkg](https://mp.weixin.qq.com/s/ZUoOY5NjcEL3bFvRePwFkg)

