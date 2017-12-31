# vue-youzan
使用vue重构有赞商城

## 多页面应用调整

1、目录解构调整
- 将之前src下单页面的文件目录(除了components)都迁移到pages/Index下作首页
- 将之前的单页面应用入口文件mian.js改为index.js
- 可以在pages下增加多个文件：对应多个页面,例如这里我添加的cart

２、webpack配置调整
- 参考blog链接: https://github.com/tonyfree/blog/issues/1
