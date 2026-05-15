# 提示词文件夹

这里放的是“逐文件可直接丢给 AI”的提示词。

## 使用方式

1. 打开对应的 `.prompt.md` 文件。
2. 把目标文件当前内容贴到 `【已有内容】` 后面。
3. 发给 AI 生成。
4. 把返回结果写回对应的目标文件。

## 自动批量生成

如果你要让我一次性批量跑，直接用脚本：

```powershell
python .\tools\doubao_batch_generate.py --all
```

运行前先准备其一：

- 设置环境变量 `DOUBAO_API_KEY` 或 `ARK_API_KEY`
- 或者在 `game/prompts/doubao.config.json` 中填写 `api_key` / `api_key_env`

默认模型：

- `doubao-seed-1-8-251228`

默认 Base URL：

- `https://ark.cn-beijing.volces.com/api/v3`

默认接口：

- `/responses`

可选输出长度字段：

- `max_output_tokens`

## 映射关系

- `docs/total_setting.prompt.md` 对应 [`game/docs/Galgame《星尘告白：错位的温柔》人物设定与故事线（含分支）.md`](/H:/Project/webgl/games/517爱情故事/game/docs/Galgame《星尘告白：错位的温柔》人物设定与故事线（含分支）.md)
- `docs/bailiya_emotion.prompt.md` 对应 [`game/docs/星尘错位：贝利亚的失爱之殇.md`](/H:/Project/webgl/games/517爱情故事/game/docs/星尘错位：贝利亚的失爱之殇.md)
- `scene/start.prompt.md` 对应 [`game/scene/start.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/start.txt)
- `scene/01_common_1.prompt.md` 对应 [`game/scene/01_common_1.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/01_common_1.txt)
- `scene/02_common_2.prompt.md` 对应 [`game/scene/02_common_2.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/02_common_2.txt)
- `scene/03_common_3.prompt.md` 对应 [`game/scene/03_common_3.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/03_common_3.txt)
- `scene/04_nailong_escape.prompt.md` 对应 [`game/scene/04_nailong_escape.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/04_nailong_escape.txt)
- `scene/05_nailong_secret.prompt.md` 对应 [`game/scene/05_nailong_secret.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/05_nailong_secret.txt)
- `scene/06_nailong_crisis.prompt.md` 对应 [`game/scene/06_nailong_crisis.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/06_nailong_crisis.txt)
- `scene/07_nailong_return.prompt.md` 对应 [`game/scene/07_nailong_return.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/07_nailong_return.txt)
- `scene/08_nailong_he.prompt.md` 对应 [`game/scene/08_nailong_he.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/08_nailong_he.txt)
- `scene/08_nailong_be.prompt.md` 对应 [`game/scene/08_nailong_be.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/08_nailong_be.txt)
- `scene/04_bailiya_thaw.prompt.md` 对应 [`game/scene/04_bailiya_thaw.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/04_bailiya_thaw.txt)
- `scene/05_bailiya_recoil.prompt.md` 对应 [`game/scene/05_bailiya_recoil.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/05_bailiya_recoil.txt)
- `scene/06_bailiya_revolt.prompt.md` 对应 [`game/scene/06_bailiya_revolt.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/06_bailiya_revolt.txt)
- `scene/07_bailiya_rescue.prompt.md` 对应 [`game/scene/07_bailiya_rescue.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/07_bailiya_rescue.txt)
- `scene/08_bailiya_he.prompt.md` 对应 [`game/scene/08_bailiya_he.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/08_bailiya_he.txt)
- `scene/08_bailiya_be.prompt.md` 对应 [`game/scene/08_bailiya_be.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/08_bailiya_be.txt)
- `scene/04_ne_path.prompt.md` 对应 [`game/scene/04_ne_path.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/04_ne_path.txt)
- `scene/05_ne_path.prompt.md` 对应 [`game/scene/05_ne_path.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/05_ne_path.txt)
- `scene/06_ne_path.prompt.md` 对应 [`game/scene/06_ne_path.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/06_ne_path.txt)
- `scene/07_ne_path.prompt.md` 对应 [`game/scene/07_ne_path.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/07_ne_path.txt)
- `scene/08_ne_end.prompt.md` 对应 [`game/scene/08_ne_end.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/08_ne_end.txt)
- `scene/08_true_end.prompt.md` 对应 [`game/scene/08_true_end.txt`](/H:/Project/webgl/games/517爱情故事/game/scene/08_true_end.txt)
