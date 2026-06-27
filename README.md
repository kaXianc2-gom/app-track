# AppTrack — 报名进度追踪

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.2.1-brightgreen)](https://github.com/kaXianc2-gom/app-track/releases)
[![Pages](https://img.shields.io/badge/demo-online-0078D4)](https://kaXianc2-gom.github.io/app-track/)

> 追踪国考/省考报名全流程——时间线、材料清单、截止提醒。数据存浏览器本地。

单文件 HTML，双击即用。添加岗位、记录状态、查看时间线、导出备份。

## 怎么用

1. 下载 index.html，双击打开
2. 添加岗位，填写部门/职位/日期
3. 时间线自动生成，按日期排列
4. 截止前 7 天标红提醒
5. 定期导出备份

也可以从 SheetLens 导出的 CSV 直接导入岗位。

## 功能

**时间线**：报名、截止、笔试、面试按日期排列。过去 30 天事件自动隐藏，3 天内截止标红。

**状态追踪**：9 个状态（跟踪中 → 已报名 → 审核中 → 已通过 → 已缴费 → 笔试 → 面试 → 录取 / 未通过）。统计栏筛选项。

**材料清单**：每个岗位可附加待办清单，逐项勾选。

**备份**：导出 JSON 文件，随时恢复。

## 🌐 在线体验

无需下载，直接使用：**[🔗 在线 Demo](https://kaXianc2-gom.github.io/app-track/)**

## 🔐 隐私声明

- **数据不上传**：所有报名信息、时间线、材料清单均在浏览器 localStorage 中存储
- **无网络请求**：SheetJS 已内联，运行时零外部请求
- **数据完全本地**：数据仅存于你的浏览器中，不会同步或上传到任何服务器

> ⚠️ **免责声明**：本工具仅供报名进度辅助记录。截止日期等关键信息请以官方公告为准，建议定期导出 JSON 备份。

## 技术

纯 HTML + JS，SheetJS 内联（导入 CSV 用），单文件约 920KB。数据全部 localStorage 存储。

## 生态位置

TableNorm → DataVeil → SheetLens → PostCmp → AppTrack

MIT License
