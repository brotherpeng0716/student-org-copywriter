# 学生组织文案skill

面向高校学生组织的中文文案撰写 skill，适用于活动宣传、招新、报名提醒、活动通知、讲座邀请、演出与展览推文、活动回顾、邮件和群消息等场景。

## 直接使用

将本仓库根目录放入 Codex skills 目录，并保留 `SKILL.md` 与 `agents/openai.yaml`：

```text
$CODEX_HOME/skills/student-org-copywriter/
```

未设置 `CODEX_HOME` 时，可使用：

```text
~/.codex/skills/student-org-copywriter/
```

本 skill 无需额外依赖。安装后，直接提出活动文案、招新文案、通知、邮件或推文需求即可触发。

## 目录

- `SKILL.md`：核心写作规则与交付流程
- `agents/openai.yaml`：Codex 界面元数据
- `docs/`：研究、设计文档与会议记录
- `src/`：代码与实现
- `progress/`：每周进度记录
- `showcase/`：示例材料与展示资产
