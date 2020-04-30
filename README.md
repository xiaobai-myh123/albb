### 第一天

技术要求：

```
java 1.8
编译器 ：eclipse
模板语法 ：Thymeleaf+spring+mybatis+springmvc
环境搭建：使用sprintboot搭建环境   版本 2.2.0
```



数据库设计

**购物车的表**

|  CarId   | int  |  购物车id  | 主键不能为空 |
| :------: | :--: | :--------: | ------------ |
|  UserId  | int  |   用户id   | 不能为空     |
| shoppcar | int  | 商品信息id | 不能为空     |

**商品的表**

| GoodsId   | int     | 商品id       | 主键不能为空 |
| --------- | ------- | ------------ | ------------ |
| GoodsName | varchar | 商品名称     | 不能为空     |
| Img       | varchar | 商品图片地址 | 不能为空     |
| Price     | double  | 商品单价     | 不能为空     |
| Kind      | int     | 商品种类     | 不能为空     |
| Address   | varchar | 发货地址     | 不能为空     |
| size      | varchar | 商品尺码     |              |

**用户表**

| UserId   | int     | 用户id | 主键不能为空 |
| -------- | ------- | ------ | ------------ |
| UserName | varchar | 用户名 | 不能为空     |
| PassWord | varchar | 密码   | 不能为空     |
| Phone    | int     | 手机号 | 不能为空     |



要求：4.30

1. 解决页面问题

2. 数据库的设计

3. 搭建能够运行的环境

   

### 第二天

任务： 

1. 为数据库添加数据
2. 展示首页数据



