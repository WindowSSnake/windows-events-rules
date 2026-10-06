# Changelog



本文件记录事件规则库的所有重要变更。



格式参考 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.1.0/)，

版本号遵循[语义化版本](https://semver.org/lang/zh-CN/)。



## \[1.0.0] - 2026-10-06



### 新增

* 首个稳定版本，共 142 条 Windows 事件规则
* 覆盖类别：

&#x20; - 安全审计（登录、账户、组、策略、Kerberos、日志清除等）

&#x20; - 存储/磁盘（disk、Ntfs、storahci、Storage-Storport 等）

&#x20; - 硬件错误（WHEA-Logger 系列）

&#x20; - 内核/电源（Kernel-Power、Kernel-Boot 等）

&#x20; - 服务/更新（Service Control Manager、WindowsUpdateClient 等）

&#x20; - 应用程序（Application Error、Application Hang、.NET Runtime 等）

* level 采用 Windows 原生级别（Critical/Error/Warning/Information/Verbose）
* severity 采用业务严重度（Critical/High/Medium/Low）



### 说明

* 部分事件描述由 AI 辅助起草，经多模型交叉验证、人工核校后定稿
* 事件 ID、来源为事实性信息，不做任何判断担保

