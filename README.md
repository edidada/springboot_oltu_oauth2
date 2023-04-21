# README

https://www.cnblogs.com/huanglin101/p/8334208.html


/login：登录接口
/Oauth/authorize:获取授权码的接口
/Oauth/getCode:这个其实就是授权码接口，只是例子中后端没有存储登录状态，做了个中转
/Oauth/accesstoken:获取访问令牌


https://www.cnblogs.com/jdluojing/p/4201729.html

认证服务器的返回是通过重定向实现的

为什么oauth2中的授权码模式 在获取token之前非要先到资源服务器获取一个code 然后才使用资源服务器的code去资源服务器去申请token?
看了很多资料说是因为 用户在确认授权之后 资源服务器会跳转到我们指定的一个回调url, 如果直接返回token的话，谁都可以在浏览器中看到这个token 那就没有安全性可言了

OAuth全称Open Authentication
qq登录是不是用Oauth 2

https://blog.csdn.net/Fishermen_sail/article/details/128850396
