# 自动化测试平台

## 项目简介

该项目旨在搭建自动化pipeline流程串联AI性能、功能、精度测试流程，并上报测试数据至AI数据存储平台。

相关参考：
- [AI数据存储平台中文文档](../AIEvaluationDataPlatform/README.md)
- [AI数据存储平台英文文档](../AIEvaluationDataPlatform/README_EN.md)

该项目使用[Jenkins](https://github.com/jenkinsci/jenkins)搭建，采用jenkins agent模式纳管各类测试Linux服务器、Windows AIPC。

## 架构图

![参考架构图](architecture.png)

## 样式参考

（部分敏感数据已做打码处理）

## Jenkins Pipeline

![Jenkins Pipeline 1](jenkins_pipeline_1.png)

![Jenkins Pipeline 2](jenkins_pipeline_2.png)

## 触发方式

支持以下两种触发方式：
1. Jenkins触发表单手动触发
2. CI自动触发

![Jenkins触发表单](jenkins_trigger_form.png)

## 报告通知

![报告通知1](report_1.png)

![报告通知2](report_2.png)