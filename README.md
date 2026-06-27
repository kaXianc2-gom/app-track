# 📋 AppTrack — 报名进度追踪器

[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![Version](https://img.shields.io/badge/version-v1.0.0-green)](https://github.com/kaXianc2-gom/app-track/releases)

> 公考报名必备。追 5-8 个岗位的报名/审核/缴费/准考证/笔试/面试全流程，自动截止提醒，材料清单逐项勾选，数据支持 JSON 备份导出。

## 🎯 解决的痛点

一个考生通常报 5-8 个岗位，每个岗位的报名开始/截止、审核、缴费、准考证打印、笔试、面试日期全在不同网站。靠脑子记？肯定会漏。

AppTrack 把所有岗位的时间线整合在一个页面，打开就自动检查哪些快截止了。

## ✨ 功能

### 📌 岗位管理
- 添加/编辑/删除岗位
- **9 种状态流转**：跟踪中 → 已报名 → 审核中 → 已通过 → 已缴费 → 笔试 → 面试 → 录取 / 未通过
- 从 SheetLens CSV 一键导入

### ⏱ 时间线视图
- 所有岗位的日期事件按时间排序
- 自动标注：X天前 / 今天 / X天后
- 3 天内截止的标红加急

### ⏰ 截止提醒
- 打开页面自动检测 7 天内截止的岗位
- 弹 toast 提醒，不错过关键日期

### 📎 材料清单
- 每个岗位独立的 checklist
- 逐项勾选：身份证复印件、报名表、学历证书…
- 动态增删

### 📤 数据备份
- JSON 格式导出，换电脑不怕丢
- 支持 JSON 导入恢复

### 🔍 筛选视图
- 全部 / 🔄 进行中 / ⏰ 即将截止 / ✅ 已完成

## 🚀 快速开始

1. [下载 index.html](https://github.com/kaXianc2-gom/app-track/releases/latest)
2. 双击打开
3. 点「➕ 添加岗位」手动填写，或从 SheetLens CSV 导入
4. 填写报名/截止/笔试/面试日期
5. 定期打开页面，自动检查截止日期

## 🔧 技术架构

| 项目 | 说明 |
|------|------|
| 存储 | localStorage（浏览器本地） |
| 依赖 | 无（纯 vanilla JS） |
| 隐私 | 数据完全在本地，不上传 |
| 备份 | JSON 导出/导入 |

## ⚠ 重要提示

数据存储在浏览器 localStorage，**清除浏览器数据会导致丢失**。建议定期点「📤 导出备份」保存 JSON 文件。

## 🤖 AI 辅助

本项目使用 Claude（Anthropic Claude Code）辅助开发。

## 📄 许可证

MIT License
