+++
date = '2025-11-20T21:45:14+08:00'
draft = false
title = 'Java基础'

+++

### 包的基本语法

```package com.sina.crm```

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

### 常用包

最好导入具体类

```java
java util.*		//系统提供的工具包，工具类（Scanner
java lang.*		//java的基本包，默认引入
java net.*		//网络包，网络开发
java acw.*		//做Java界面开发，GUI
```

<mark>注意事项</mark>

* package作用是声明当前类所在包，要放在类最上面，一个类只有一个package
* import指令放在package下面，在类定义前面，可以有多句且无顺序要求



##  键盘输入

### 步骤

1. 导入类创建
2. Scanner对象
3. 接受输入内容

* ```java
  import java.util.Scanner	//1.
  public class Input{		
      public static void main(String[] args){
          Scanner input = new Scanner（System.in);	//2.
          System.out.println("输入名字：");
          String name = input.next();		//3.
      }
  }
  ```

  

### Scannner相关方法(以input为例)

1. ```input.next();```接收字符串类型
2. ```inout.nextInt();```接收int型数据
3. ```input.nestDouble();```接收double类数据



## 成员方法

### 基本语法

访问修饰符  +  返回值类型 + 方法名（参数）{ 方法体 }

```public void speak(){ }```

### 方法调用

```Person p1 = new Person();```创建

```p1.speak();```调用



## 方法重载

