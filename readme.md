# Azure Function with Python - README

## 项目简介

本项目展示了如何使用Python编写Azure Function，并通过HTTP触发器处理请求。具体功能包括接收HTTP请求，提取查询参数，并返回相应的响应。

## 先决条件

- 安装 Node.js
- 安装 Azure Functions Core Tools
- 安装 Visual Studio Code 及其 Azure Functions 扩展

## 安装步骤

### 1. 安装Node.js

从 Node.js官网 下载并安装最新的LTS版本。安装过程中，请确保选择了“Add to PATH”选项。

### 2. 安装Azure Functions Core Tools

打开命令行终端，输入以下命令安装Azure Functions Core Tools：

```bash
npm install -g azure-functions-core-tools@4 --unsafe-perm true
