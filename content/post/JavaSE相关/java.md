+++
date = '2025-11-20T21:45:14+08:00'
draft = false
title = '包'

+++

### 命名规则

> 由数字，字母，下划线，小圆点组成（数字不能开头，不能是关键字 保留字）
>
> e.g ：aa1.bb2.cc_

### 规范命名

> 格式：com.公司名.项目名.业务模块
>
> e.g ：com.sina.crm.user
>
> ​          com.sina.crm.order
>
> ​	  com.sina.crm.utils

### 包的基本语法

```package com.sina.crm```

### 常用包

```javascript
java util.*		//系统提供的工具包，工具类（Scanner
java lang.*    	//java的基本包，默认引入
java net.*		//网络包，网络开发
java acw.*		//做Java界面开发，GUI
```

<mark>注意事项</mark>

* package作用是声明当前类所在包，要放在类最上面，一个类只有一个package
* import指令放在package下面，在类定义前面，可以有多句且无顺序要求



