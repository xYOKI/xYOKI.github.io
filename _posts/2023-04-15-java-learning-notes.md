---
layout: post
title:  "Java学习笔记"
date:   2023-04-15 17:45:48 +0800
---
### 一、JDK、JRE、JVM

#### 1. JDK（Java开发工具包：Java Development Kit）

##### Java软件开发工具包；可开发Java软件；可运行Java程序。

两个主要组件：

- **-javac**：编译器compiler：将源程序文件（.java）转成字节码文件（.class）
- **-java**：运行编译后的java程序（.class）
  

#### 2. JRE（Java运行环境：Java Runtime Environment）

##### 只运行Java程序；包括JVM（Java虚拟机）、Java核心类库、支持文件。

#### 3. JVM（Java虚拟机：Java Virtual Machine）

##### 实现Java平台无关性；一次编译，到处运行。

#### 4. 三者关系：

**JDK=JRE+开发工具集**（例如 -javac 编译工具）

**JRE=JVM+JavaSE标准类库**（用于开发桌面程序）

---
### 二、Java三大平台（Java SE、Java EE、Java ME）
- **Java SE**：用于开发桌面程序；为Java EE提供基础；本身基于JDK、JRE；例如QQ、office。
  
- **Java EE**： 用于开发网页的Web程序；包括Java SE、JSP、Servlet等Web开发所需要的技术；例如电商网站、门户网站。

- **Java ME**：用于开发移动设备；同类安卓、IOS。

---
## Windows系统下进行JDK环境搭建

### 一、JDK版本号：jdk-8u241 / jdk-8u301

点击命令行图标可以修改属性，字体格式等等。
用命令行cmd查看jdk版本号的命令：java -version

### 二、编写代码的规则 

1. 小/中/大括号都是**成对存在**的，写完一个立马写另外一个
2. 主方法：空格移到public的i处，一般空**4格**或者空**8格**
3. 全部使用**英文输入法**
4. println中的 l 是小写的 L，不是大写的 i
5. 每次编程修改完成后，都要重新编译再运行
6. Java代码基础结构：
```bash
public class Hellolmooc{
    public static void main(String[l args){
        System.out.println("Hello,mooc!");
    }
}
```
若要运行该程序，可以选择使用**javac**或者**命令行**的命令：去执行；

需要配置好环境变量（2种方式），然后**重新启动cmd**，输入命令运行

### 三、常见问题及解决办法：

#### 1、编码格式问题（乱码）

>解决方法: 
http://www.360doc.com/content/22/1112/23/18334519_1055677330.shtml



