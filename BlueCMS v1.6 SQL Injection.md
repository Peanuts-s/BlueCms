# BlueCMS v1.6 SQL Injection

The keywords parameter can be controlled. Since the cms is encoded in GBK2312, wide bytes can be used to close single quotes. We can use delayed injection to judge the execution of SQL statements

![](https://www.hualigs.cn/image/645398220b7c0.jpg)

![](https://www.hualigs.cn/image/645399a706738.jpg)