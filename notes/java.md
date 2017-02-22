# Java

## Table of Contents
- [概述](#概述)
	- [简介](#简介)
	- [安装](#安装)
		- [Linux](#Linux)
		- [Windows](#Windows)
 [插件开发](#插件开发)

- [其他](#其他)

---------------------------------------------------------------------

## 概述
### Java环境

#### Linux
* Debian/Ubuntu
1. 下载JDK安装包: http://www.oracle.com/technetwork/java/javase/downloads/index.html
2.

```
$ sudo apt-get install atom
```
* Debian
Download atom-amd64.deb from the Atom releases page.
```
# dpkg --install atom-amd64.deb
```

#### Windows
1. 安装JDK，从Oracel官方网站上下载，也可以通过搜索，进入链接。下载完成后安装。
2. 安装JDK，注意更改安装目录
3. 安装完成后开始配置环境变量，右击我的电脑，点击属性
4. 在出现的对话框中选择高级系统设置
5. 在出现的对话框中选择环境变量
6. 新建名为“classpath”的变量名，变量值为“.;%JAVA_HOME%\lib;%JAVA_HOME%\lib\tools.jar “（注意是”“里的内容）直接复制即可
7. 新建名为”JAVA_HOME“的变量名，变量值为之前安装jdk的目录，例如本人的为”E:\Program Files\Java\jdk1.7.0_40“
8. 在已有的系统变量”path“的变量值加上”;%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin“（注意，每个变量值是以”；“隔开，变量值开头的分号就起这个作用）自此配置完成。
9. 下面检验是否配置成功，运行cmd命令，在出现的对话框输入”java“命令。

### Java程序
一个示例的java程序如下
```
/*
 * File name: HelloWorld.java
 */
public class Fruit {
	public static void main(String[] args) {
		Systeam.out.println("Hello World");
	}
}
```
编译过程如下
```
$ javac  HelloWorld.java
```
运行程序
```
$ java HelloWorld
```

### 约定俗成
* Java程序中约定俗称的规则如下,应该遵守

### 关键字
* 我认为关键字是编程语言最基本的构成要素,因此,这里先列出JAVA的关键字


## 2. Java语言基础
### 2.1 数据类型

### 2.2 变量

### 2.3 操作符


### 2.4 控制流程


### 2.5 数据与字符串

## 3. 类和对象
### 2.1 数据类型

## 4. 继承


## 5. 封装



## 6. 多态



## 7. 异常处理

## 8. Java I/O

## 9. 文件处理

## 10.
