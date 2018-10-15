# JVM_Study

# Java_Study

## 作者：冰红茶  
## 参考书籍：《深入理解Java虚拟机》 周志明
    
------    
    
Java号称“Write once, run everywhere”，其中其重要作用莫过于他的虚拟机JVM。通过JVM可以了解到Java这种语言更加深层次的特点和运行状态以及内存分配。为后面为Java程序的高并发和性能优化打下坚实的基础^_ ^

## 目录
## [一、Java内存区域与内存溢出异常](#1)
### [1.1 运行时数据区域](#1.1)
## [二、基础语法](#2)
### [2.1 操作符](#2.1)
### [2.2 流程控制](#2.2)

        
------      
        
<h2 id='1'>一、Java内存区域与内存溢出异常</h2>
<h3 id='1.1'>1.1 运行时数据区域</h3>  
        
#### 1) 概述
> - JVM一个突出的特点要数他的自动内存管理机制，不用为每一个new去写配对的delete/free代码
#### 2) 运行时数据区域
> - 程序计数器
>>>>>> ![Java程序执行与运行环境](https://github.com/hblvsjtu/Java_Study/blob/master/picture/%E5%9B%BE1-1%20Java%E7%A8%8B%E5%BA%8F%E6%89%A7%E8%A1%8C%E4%B8%8E%E8%BF%90%E8%A1%8C%E7%8E%AF%E5%A2%83.jpg?raw=true)