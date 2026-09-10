# concept-learning —— 个人概念学习资料生成 Skill

> 作者：覃宏丽（Qinhongli123）· 版本 1.0.0 · Python 课程作业

## 这个 Skill 是干什么的？

输入一个不熟悉的领域概念，自动生成一份结构化、离线可看的 HTML 学习资料，包含六个固定模块：

**概念定义（大白话+规范） → 核心机制 → 应用案例 → 概念辨析 → 自测问题（附折叠答案） → 参考来源**

## 文件清单

| 文件 | 说明 |
| --- | --- |
| `SKILL.md` | Skill 的元信息与完整说明：适用场景、输入、生成步骤、输出结构、资料来源、自检要求 |
| `concept-relationship.html` | 首页：三个概念的关系图 + 我的个人类比理解（建议从这里开始看） |
| `training-materials/agent.html` | 概念一：Agent（智能体） |
| `training-materials/llm-context.html` | 概念二：大模型的上下文 |
| `training-materials/skill.html` | 概念三：Skill（AI 技能包） |

## 使用方法

1. **浏览学习资料**：从本目录下载任意 HTML 文件，用浏览器打开即可（无外部依赖，离线可看）；
2. **推荐阅读顺序**：`concept-relationship.html`（先建立全局）→ `agent.html` → `llm-context.html` → `skill.html`；
3. **自测**：每个概念页底部有自测问题，点击可展开参考答案；
4. **复用本 Skill**：以后学习新概念时，按 `SKILL.md` 中"生成步骤"的六步流程（概念界定 → 机制拆解 → 案例生成 → 概念辨析 → 自测出题 → 来源标注）照做即可，产出结构保持统一。

## 调用示例（自然语言）

> 请用 concept-learning Skill 帮我生成"计算广告"的学习资料，我是广告学大二学生，入门深度，输出 HTML。

## 复刻/扩展说明

- 想给资料增加模块（如"术语表"），修改 `SKILL.md` 中的"输出结构"与"自检要求"两节即可；
- 想生成新概念资料，在 `training-materials/` 下新建对应 HTML，并保持六模块结构与统一导航。
