# Multi-Agent Ops System

## 🚀 项目简介

基于 AI 多 Agent 协同架构的自动化运营系统。

支持：

- 多 Agent 协同
- 长链推理
- 自动任务拆解
- RAG 知识库
- 自动内容生成
- 数据分析与反馈优化

---

# 🧠 系统架构

```text
用户输入目标
      ↓
Planner Agent
      ↓
Research Agent
      ↓
Content Agent
      ↓
Visual Agent
      ↓
Review Agent
      ↓
Publish Agent
      ↓
Analytics Agent
```

---

# ▶️ 启动项目

```bash
pip install -r requirements.txt
uvicorn api.app:app --reload
```

访问：

http://127.0.0.1:8000

---

# 📷 Dashboard

![Dashboard](./screenshots/dashboard.png)
