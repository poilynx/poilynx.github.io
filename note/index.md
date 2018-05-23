---
layout: page
title: 笔记
---

---
### Mysql 向表中添加级联删除和级联更新
首先查看外键名
```sql
mysql> show create table table1;
```
删除外键
```sql
mysql> alter table table1 drop foreign key KEYNAME;
```
添加外键
```sql
mysql> alter table table1 add constraint `fk_table1_table2` foreign key (table2_id) references table2 (_id) on delete cascade;
-- 添加级联删除
mysql> alter table table1 add constraint `fk_table1_table2` foreign key (table2_id) references table2 (_id) on update cascade;
-- 添加级联更新
```
*2018年 05月 22日 星期二 16:03:09 CST*

---
### Git 本地合并分支
```shell
$ git remote -v		# 查看远程分支名称，通常是origin
$ git fetch origin master:temp	#获取最新的origin分支到本地temp分支
$ git diff temp		#查看temp分支与master分支不同
$ git merge temp	#自动合并分支，如果合并失败，需要手动编辑文件进行合并
$ git branch -d temp	#删除temp分支
```
*2018年 05月 22日 星期二 16:46:43 CST*
