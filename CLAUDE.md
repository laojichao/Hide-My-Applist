# Hide-My-Applist - 应用列表隐藏模块

## 项目概述
Hide-My-Applist 是一个 Xposed 模块，用于隐藏设备上的应用列表，防止应用检测到 Root 相关应用。

## 技术栈
- **开发语言**: Java/Kotlin
- **Hook 框架**: Xposed API
- **UI 框架**: Material Design

## 环境要求
- Android 8.0+
- 已安装 Xposed 框架 (LSPosed 等)

## 功能特性
- 隐藏指定应用
- 拒绝应用列表请求
- 提供隐藏效果测试方法

## 构建命令
```bash
./gradlew assembleRelease
```

## 许可证
GPL-3.0

## 作者
Dr-TSNG
