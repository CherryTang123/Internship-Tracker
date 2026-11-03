# Internship-Tracker
> Lightweight internship application tracker | AI-assisted development practice

## 📖 项目介绍
一款面向求职者的轻量化实习投递台账工具，解决多赛道求职时投递记录分散、笔试/面试/offer截止节点容易遗漏的痛点。
市面上同类工具往往功能臃肿、收费，或是字段无法自定义，因此从自身真实求职需求出发搭建本项目。

本项目采用**人机协同开发工作流**：
1. 整理原始需求，使用 Gemini 3 Flash 优化 PRD，敲定 MVP 范围、数据字典与状态流转规则；
2. 基于定稿PRD，使用 Trae 生成基础代码脚手架，人工完成逻辑校验、bug修复、交互调整；
3. 自测稳定后托管至 GitHub，持续迭代维护。

> 重要声明：AI仅作为提效辅助工具，需求取舍、业务逻辑、边界校验、代码验收全部由开发者主导，并非AI一键生成成品。

## ✨ 核心功能
- 投递卡片管理：新增 / 编辑 / 删除岗位，记录公司、岗位名称、投递渠道、JD链接、备注
- 标准化状态流转：待投递 / 已投递 / 笔试 / 一面 / 二面 / 终面 / offer / 拒绝 / 搁置
- 时间节点记录：投递时间、笔试时间、面试时间、offer截止时间
- 搜索与筛选：支持按公司、赛道、投递状态快速过滤投递条目
- 本地持久化存储：数据保存在浏览器本地，无需后端、无需登录、开箱即用

## 🧰 技术栈
- HTML + Vanilla JavaScript
- Tailwind CSS
- 纯前端单页应用，无重型依赖，部署成本极低

## 🚀 快速启动
```bash
# 克隆仓库到本地
git clone https://github.com/你的用户名/Internship-Tracker.git

# 进入项目目录
cd Internship-Tracker
