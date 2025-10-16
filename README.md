# 206207.xyz
墨铺网https://206207.xyz 代码存储库。
整理一些小代码，比如为了让公众号文章推广过程中，有一个较好的流量主收益，强制要求别人用微信来扫码，而不是随便一个APP扫码就能浏览的H5代码实现方案。其实也就是在网页代码中加入了微信浏览器环境检测，能够让一些计算机初级使用者按规定扫码使用。
下面是被拦截的示意图。
<img width="811" height="533" alt="image" src="https://github.com/user-attachments/assets/d0be18d0-1574-4ec8-8341-bff7c32d26d8" />
然后也有当使用微信手机版或电脑版扫码时，正确打开的示意图。
<img width="812" height="527" alt="image" src="https://github.com/user-attachments/assets/e8204a9f-9c46-4ef4-93ca-ad2e26c5eebc" />
想让访客少点一下，那就用自动跳转代码，这当然是可以实现的。不过因为是全自动的，也就无法去截图了。
这是两个不同的方案，都是做成静态html网页，放在服务器内让网址生效，在草料等二维码生成网站，制作出二维码后就能使用了。
<img width="912" height="408" alt="image" src="https://github.com/user-attachments/assets/c54d6332-c0d0-4ee8-9b41-19148b4ebe50" />

当然也有其问题，如果是微信小绿标的网站，这样进入时不会有任何提示，而普通的网址则会有一个提示，需要点击确认后才会打开。


