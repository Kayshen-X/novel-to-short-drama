# 小说改编短剧

`novel-to-short-drama` 是一个 Codex Skill。它帮你从小说里选出一个能独立成戏的片段，再按需要完成改编剧本、人物设定、场景道具、逐镜分镜和有声短剧。

A Codex skill for turning a scene from a novel into a storyboard or a finished short drama.

## 安装

把仓库克隆到 Codex 的 Skills 目录。

```sh
git clone https://github.com/Kayshen-X/novel-to-short-drama.git ~/.codex/skills/novel-to-short-drama
```

如果配置了单独的 `CODEX_HOME`，把目标目录改为该目录下的 `skills/novel-to-short-drama`。已经克隆过时，可以在现有仓库运行 `git pull` 更新。

## 使用

附上小说片段或者整本小说，并说明想拍的类型、画风、时长和需要的交付物。

> 用 $novel-to-short-drama 读我提供的小说。挑一段约 40 秒能讲清楚的悬疑戏，做成二维动画。先写出人物目标和最后一个画面，再给我角色设定、道具、场景、每镜首帧和动作。片中对白保留生成工具的原声。

也可以从已选好的小节开始。

> 用 $novel-to-short-drama 把附件的第三节改成 60 秒短剧分镜。帮我把旁白换成可拍的动作，标出每镜开始和结束时人物的视线与道具位置。

## 内容

- [SKILL.md](SKILL.md) 从选段、确定结尾到生成和导出的流程。
- [制作模板](references/production-templates.md) 可复用的片段卡、人物和场景卡、分镜卡。
- [H3 制作与核验](references/h3-production.md) 适合使用 MiniMax H3 和 ComfyUI 时的逐镜生成、原声处理与任务记录。

需要生成成片时，沿用你指定的生成工具和可用环境。阶段交付和模型选择可以直接写在请求里。

## 许可证

[MIT](LICENSE)
