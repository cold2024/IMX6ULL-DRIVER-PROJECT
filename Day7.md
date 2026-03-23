# Day7：UBOOT源码结构，交叉编译环境（2025.3.23）

## 今日目标

理解uboot源码结构与交叉编译环境

利用gcc编译工具编译hello.c



## 遇到的问题 & 解决

- uboot的功能实际是一个裸机程序，核心功能：启动内核
- uboot源码架构:arch,board,driver,dts,lib,common等
- gcc的编译过程：预处理-->编译-->汇编-->链接
- 

## 今日Git提交记录

- commit 信息：

## 明日计划

- 写第一个LED字符设备驱动