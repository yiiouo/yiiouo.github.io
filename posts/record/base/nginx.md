---
title: vim
date: 2021-02-24 15:00:00
tags: [“nginx"]
categories: ["记录"]
---

# 记录

## 例子

### 配置请求转发

最常见的配置，在一台服务器部署了前后端，前端用的是静态文件，后端运行的端口是 8888。当我前端请求当前域的接口时，通过 nginx 进行转发到对应的地址



### HTTPS

### 对某个地址统一添加头部

### 缓存

### 逻辑判断重定向



## 配置





## 记录

### location 的选择

请求进来， server 匹配 location 时，如果选择带有规则解析句，接着是最长的 prefix 配置，一直递减，直到命中