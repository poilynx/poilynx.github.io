---
layout: page
title: 笔记
---

---
### 2018年 05月 22日 星期二 16:03:09 CST
Mysql 向表中添加级联删除和级联更新
```sql
mysql> alter table t_orderitem add constraint `FK...` foreign key (oid) references t_orders (oid) on delete cascade;
-- 添加级联删除
mysql> alter table t_orderitem add constraint `FK...` foreign key (oid) references t_orders (oid) on update cascade;
-- 添加级联更新
```
