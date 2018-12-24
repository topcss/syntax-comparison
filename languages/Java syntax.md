# Java 语法

## Java 基础语法

### [HelloWorld](#HelloWorld)

``` java
public class HelloWorld {
    /* 第一个Java程序
     * 它将打印字符串 Hello World
     */
    public static void main(String []args) {
        System.out.println("Hello World"); // 打印 Hello World
    }
}
```

### [语法](#语法)

区分大小写

### 定义变量

``` java
int x;

String s;

String s1, s2;

Object o;

Object obj = new Object();

public String name;
```

### 输出内容

``` java
Response.Write("foo");
```

### 注释

``` java
// This is a comment

/* This is a 
multi-line 
comment */
```

### 读取数据集合数组

``` java
String s = request. getParameter("Name");

String value;

Cookie ck = null;

Cookie args[] = Request.getCookies();

for(int i = 0; i<args.length; i++){

    ck = args[i];

    if(ck.getName().equals("key "))

        value = ck.getValue();

}
```

### 字符串操作

``` java
String s1;
String s2 = "hello";
s2 += " world";
s1 = s2 + " !!!";
```

### If 结构

``` java
if (Request.QueryString != null)
{
...
}
```

### 字符串操作

``` java
String s1;
String s2 = "hello";
s2 += " world";
s1 = s2 + " !!!";
```

### For 循环

``` java
for (int i=0; i<3; i++)
    a[i] = "test";
```

### While 循环

``` java
int i = 0;

while (i<3)
{
    System.out.println(i);
    i += 1;
}
```

### 类定义和继承

``` java
import java.lang.*;

package MySpace;

public class Foo extends Bar {

    private int x; //私有变量

    public Foo() {x = 4; } //构造函数

    public void Add(int x) { this.x += x; } //过程

    public int getNum() { return x; } //函数

}
```

### 事件处理

``` java
jButton1.addMouseListener(new java.awt.event.MouseAdapter() {

    public void mouseClicked(java.awt.event.MouseEvent evt) {
        Button1_Click(evt);
    }

});

private void Button1_Click(java.awt.event.MouseEvent evt) {

}
```

## Java 面向对象

