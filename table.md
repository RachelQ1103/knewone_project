### knewone table
---
#### 商品表 product
| 字段  | 英文 |
| :------| ---- |
| id    | id |
| 创建时间 |create_time |
| 分享者id    | user_id |
| 名称    | name |
| 价格    | price |
| 图片 |  pirture_urls |
| 动态    | tends|
| 讨论    | commemts |
| 评测    | evaluations |
| 喜欢/点赞    | likes |
| 拥有    | owns |
| 品牌id    | brand_id |


---
#### 商品评论表 product_commemt
| 字段    | 英文 |
| :------| ---- |
| id    | id |
| 创建时间    | create_time |
| 评论者id    | user_id |
| 评论的商品id    | product_id |
| 喜欢/点赞    | like |
| 评论内容    | content |
| 图片    | pirture_urls |
| 回复    | replys |

---
####  评论回复表 commemt_reply
| 字段    | 英文 |
| :------| ---- |
| id    | id |
| 创建时间    | create_time |
| 回复者id    | user_id |
| 评论id    | commemt_id |
| 回复内容    | content |

---
#### 动态表 tends
| 字段    | 英文 |
| :------| ---- |
| id    | id |
| 创建时间    | create_time |
| 用户id    | user_id |
| 动作1    | action1 |
| 动作2    | action1 |

---
#### 评测表 evaluation
| 字段    | 英文 |
| :------| ---- |
| id    | id |
| 创建时间    | create_time |
| 用户id    | user_id |
| 评测的商品id    | product_id |
| 评分    | reta |
| 回复内容    | content |
| 图片    | pirture_urls |
| 喜欢/点赞    | like |
| 回复    | replys |


---
####  评测回复表 evaluation_reply
| 字段    | 英文 |
| :------| ---- |
| id    | id |
| 创建时间    | create_time |
| 回复者id    | user_id |
| 评测id    | commemt_id |
| 回复内容    | content |

---
####  喜欢表 like
| 字段    | 英文 |
| :------| ---- |
| id    | id |
| 创建时间    | create_time |
| 用户id    | user_id |
| 商品id    | product_id |
| 动作(想要/拥有)    | action |  
| 标签    | label |


---
####  拥有表 own
| 字段    | 英文 |
| :------| ---- |
| id    | id |
| 创建时间    | create_time |
| 用户id    | user_id |
| 商品id    | product_id |
| 标签    | label |

---
####  列表 表 list
| 字段    | 英文 |
| :------| ---- |
| id    | id |
| 创建时间    | create_time |
| 用户id    | user_id |
| 名称    | name |
| 描述    | description |
| 商品集合    | products |


> 未完成...

---
#### 列表评论表 list_commemt
| 字段    | 英文 |
| :------| ---- |
| id    | id |
| 创建时间    | create_time |
| 评论者id    | user_id |
| 评论的列表id    | list_id |
| 评论内容    | content |
