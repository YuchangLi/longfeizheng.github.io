---
layout: post
title: Oracle-decode������null�Ĵ���
categories: [Oracle]
description: Oracle-decode������null�Ĵ���
keywords: oracle,Oracle,decode
---
�����ѯsql��Ҫ��ôһ���жϣ���һ��SQL����У���ֵΪ�յ�ʱ�򣬷���0�����򷵻�1��Ӧ����һ��ͦ�򵥵����⣬�������뵽����NVL��DECODE�������ϣ�decode(nvl(column_name,0),column_name,1,0)������������ˣ�����˵�������Ҳ�ͽ����ˣ����ǰٶ���һ�·�����decodeֱ�ӾͿ���ʵ��
```sql
SELECT DECODE(sfr.zj_count,NULL,0,sfr.zj_count) FROM SL_FJ_RULE sfr;
```

�ο����ӣ�
- [http://blog.itpub.net/10018/viewspace-886867/](http://blog.itpub.net/10018/viewspace-886867/ "http://blog.itpub.net/10018/viewspace-886867/")