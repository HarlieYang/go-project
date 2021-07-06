<!--
 * @Author: HarlieYang
 * @Date: 2021-06-16 23:50:59
 * @LastEditTime: 2021-07-07 00:35:29
 * @LastEditors: Please set LastEditors
 * @Description: 笔记
 * @FilePath: /go-main/go.md
-->
# 1. 特点
> 静态编译语言的安全和性能、动态语言开发维护的高效性
1. c语言中继承的多重概念。表达式语言、控制结构、技术数据类型、调用参数传值、指针等。
2. go语言的每一个文件都要归属于一个包
3. 垃圾回收机制，内存自动回收，不需要开发人员管理
4. 天然并发 (重要概念)
    * 从语言层面支持并发
    * goroutine,轻量级线程，可实现大并发处理，高效利用多核
    * 基于CPS并发模块实现
5. 吸收了管道通信机制，形成go特有的管道
6. 函数可以返回多个值
7. 新的创新： 切片、延时执行defer

# 2. 开发环境搭建 mac
- 安装go sdk https://studygolang.com/dl
- 默认安装目录 /usr/local/go/bin    ./go version
- 环境变量

```
vim /etc/profile

export GOROOT="$HOME/go_env/go"
export PATH="$PATH:$GOROOT/bin"
export GOPATH="$HOME/goproject"

source /etc/profile
```

# 3. 
