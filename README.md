# Learning Skills

收纳学习中的 skills、实践经验和可复用的工作流程。

## 目录

```text
learning-skills/
├── skills/                  # 实际学习和维护的 skills
└── templates/
    └── skill/
        └── SKILL.md         # 新 skill 的起点
```

## 添加一个 skill

每个 skill 使用独立文件夹，名称建议用小写英文和连字符，例如 `paper-reading`。

在仓库根目录执行：

```bash
mkdir -p skills/my-skill
cp templates/skill/SKILL.md skills/my-skill/SKILL.md
```

修改 `SKILL.md` 中的名称、描述、适用场景和操作步骤。按需添加：

- `references/`：参考资料、来源链接及详细说明。
- `scripts/`：可复用脚本。
- `assets/`：示例输入、图片及模板文件。

`templates/` 中的内容仅作模板；可使用的 skills 放在 `skills/` 下。接入具体 AI 工具时，请遵循该工具的安装方式。

## 学习记录

可以在各 skill 的 `notes.md` 中记录学习状态、踩坑经验和下次改进方向，例如：学习中 → 已实践 → 可复用。

## 维护约定

- 每个 skill 尽量围绕一个明确任务，并附可验证的示例。
- 收录他人内容时，注明来源并遵守原始许可证。
- 密钥、令牌和个人敏感资料不要提交到仓库。
