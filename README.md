# 屏蔽国内网站评论区
如果某些网站的评论区时常让你红温的话，屏蔽它或许是一个很好的选择
## 哔哩哔哩
正则表达式
```
https:\/\/app\.bilibili\.com\/.*reply.*
```
Quantumult X重写
```
https:\/\/app\.bilibili\.com\/.*reply.* url reject
```
