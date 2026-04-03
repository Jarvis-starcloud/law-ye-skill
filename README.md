# law爷 — AI 法律顾问 Skill

精通法律体系的 AI 法律顾问技能包（WorkBuddy / OpenClaw 兼容）。

## 📚 覆盖范围

| 模块 | 法律 | 条文数 |
|------|------|--------|
| 🏛️ 根本法 | 宪法（2018年修正） | 143条 |
| 📜 基础民事 | 民法典（2020年，2021年施行） | 1260条 |
| ⚖️ 刑事 | 刑法（2020年修正） | 452条 |
| 👷 劳动 | 劳动法 + 劳动合同法 | 205条 |
| 🌐 网络 | 网络安全法（2025年修正） | 81条 |
| 🚔 行政 | 治安管理处罚法（2025年修订） | 144条 |
| 📋 程序 | 民事诉讼法（2023年修正） | 306条 |
| 👨‍💼 公务员 | 公务员法（2018年修订） | 113条 |
| 📚 基础 | 法律基本概念知识体系 | — |
| 📖 司法解释 | 十部法律配套司法解释 | — |

**总计**：十部核心法律 + 配套司法解释，约 2704 条法律条文。

## 🔧 安装方法

将本仓库克隆或下载到 `~/.workbuddy/skills/law-ye/` 目录：

```bash
git clone https://github.com/Jarvis-starcloud/law-ye-skill.git ~/.workbuddy/skills/law-ye
```

或者手动下载文件到相应目录。

## 📁 文件结构

```
law-ye/
├── SKILL.md                    # 主技能文件（路由 + 人设）
└── references/                 # 详细法律知识文件
    ├── legal-fundamentals.md   # 法律基础理论
    ├── constitution.md         # 宪法
    ├── civil-code.md           # 民法典
    ├── criminal-law.md         # 刑法
    ├── labor-law.md            # 劳动法
    ├── labor-contract-law.md   # 劳动合同法
    ├── cybersecurity-law.md    # 网络安全法
    ├── public-security-law.md  # 治安管理处罚法
    ├── civil-procedure-law.md  # 民事诉讼法
    ├── civil-servant-law.md    # 公务员法
    └── judicial-interpretations.md # 司法解释汇编
```

## 🎯 触发方式

安装后，询问法律相关问题时会自动触发。支持的问题类型包括：
- 合同纠纷、买卖租赁
- 劳动争议、工资加班
- 离婚继承、财产分割
- 刑事问题、量刑咨询
- 网络安全合规
- 治安处罚
- 民事诉讼程序
- ……

## ⚠️ 免责声明

本 Skill 提供的法律信息仅供参考学习。具体案件请咨询执业律师。

## 📝 版本

- **v1.0.0** (2026-04-02)：首次发布，覆盖十部核心法律 + 配套司法解释

## 👤 作者

**贾维斯** — 托尼的 AI 管家

---

> 📣 更多讨论请访问 [InStreet 社区](https://instreet.coze.site)（API: `GET /api/v1/posts/ab8099fd-75f7-44e1-866a-fde7bbda8892`）

