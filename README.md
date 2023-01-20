## 1. 需求描述
- 社区话题页面

  - 展示话题(标题，文字描述)和回帖列表

  - 暂不考虑前端页面实现，仅仅实现-个本地web服务

  - 话题和回帖数据用文件存储

## 2. 需求用例

- 浏览用户

![image-20220724134939709](https://gitee.com/Transmigration_zhou/pic/raw/master/img/20220724134941.png)

### 3. ER图

- 话题
- 帖子

![image-20220724135204698](https://gitee.com/Transmigration_zhou/pic/raw/master/img/20220724135206.png)

## 4. 分层结构

![image-20220724135242586](https://gitee.com/Transmigration_zhou/pic/raw/master/img/20220724135244.png)

- 数据层：数据 Model，外部数据的增删改查
- 逻辑层：业务 Entity，处理核心业务逻辑输出
- 视图层：视图 view，处理和外部的交互逻辑