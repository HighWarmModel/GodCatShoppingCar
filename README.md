### GodCatShoppingCar
使用 vue-cli 仿天猫购物车菜单侧滑`star` `star` `star` 重要的事情说三遍 链接：[http://47.98.107.252:8082/#/ShoppingCar](http://47.98.107.252:8082/#/ShoppingCar)
(欢迎提供bug和优化方案私信邮箱给我1170533231@qq.com  或者加我qq:1170533231 一起讨论 共同进步) 后续我继续优化和添加功能 还没有写完....
### 修复QQ浏览器跳转一次之后返回因为原生侧滑导致js touchmove 失效
### 修复删除之后多产生了长度为1的数组[""]
### 增强功能 侧滑时禁用原生滚动  滚动时禁用侧滑
### 修复 删除之后第一次侧滑失效 touchStartX值为0（因为监听导致赋值为0）
### 修复 删除之后第一次点击跳转失效 
### 修复 点击路由跳转touch事件穿透（导致点到另一个页面的链接跳转） 