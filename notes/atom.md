# Atom

## Table of Contents
- [概述](#概述)
	- [版本历史](#版本历史)
	- [安装](#安装)
		- [Linux](#Linux)
		- [Windows](#Windows)
- [基础管理](#基础管理)
	- [基础设置](#基础设置)
	- [包管理](#包管理)
- [基础使用](#基础使用)
	- [文本操作](#基础使用)
	- [查找和替换](#查找和替换)
- [内置插件](#内置插件)
- [常用插件](#常用插件)

- [场景搭建](#场景搭建)
	- [C/C++开发环境搭建](#C/C++开发环境搭建)
	- [Java开发环境搭建](#Java开发环境搭建)
- [插件开发](#插件开发)

- [其他](#其他)

---------------------------------------------------------------------

## 概述
### 版本历史

### 安装
#### Linux
* Ubuntu
```
$ sudo add-apt-repository ppa:webupd8team/atom
$ sudo apt-get update
$ sudo apt-get install atom
```
* Debian
Download atom-amd64.deb from the Atom releases page.
```
# dpkg --install atom-amd64.deb
```

#### Windows
Download AtomSetup.exe from the Atom releases page.


## 基础管理
### 基础设置


### 包管理
#### 插件信息
* 在终端查看插件情况
```
$ apm ls
```
* 在atom内部查看插件情况
Edit--Settings--Package

#### 插件安装
* 在atom内部进行插件安装
1. Edit--Settings-Install Packages
2. 输入要安装的插件名称(支持模糊查找)
3. 点击Install按钮
4. 可以在Packages里面根据提示进行插件的设置
* 在atom外部进行安装
```
$apm install <package_name> 会安装最新版本
```


## 基础使用
### 文本操作

### 查找和替换
 Shortcut key   | Command  | Description
 -------------- | ---------|------------
cmd-f  |  | 在缓冲区中查找
cmd-shift-f |  | 在整个项目中查找


## 内置插件




## 常见插件
### 汉化插件
**Name：** simplified-chinese-menu

### tags标签
**Name:** atom-ctags

### 符号树
**Name:** symbols-tree-view  

**usage:**  

 Shortcut key   | Command  | Description
 -------------- | ---------|------------
cmd-f  |  | 在工作面板上展开符号树

## 场景搭建
### C/C++开发环境搭建
#### 自动补全
**Install Package:** autocomplete-clang

#### 语法检测
**Install Package:** linter  linter-clang

#### gdb调试
**Install Package:** atom-gdb-debugger


### Java开发环境搭建

## 插件开发

## 其他
