<div align="center">

# 🎬 h3-prompt-expert-suite

## 一句话要栋楼，还你 2560×1440 可编辑电影级飞行片
## One line about a building, get an editable 2560×1440 cinematic flythrough

> ⚠️ **这是一套配合使用的技能组合（2 个）** —— 正文互相引用，建议成套取用。

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

面向建筑、地标与城市空间展示的双技能套件。architecture-flythrough 把一句话需求转成真实资料约束的可编辑三维场景、Blender 原生 2560×1440 预演和电影级飞行视频；h3-prompt-expert 把视频创意、素材、关键帧、多模态参考与编辑需求整理成生产可用的 H3 提示词。两个技能配合使用：先用 Blender 锁定准确空间与摄影机母版、确认预演，再由提示词专家产出风格锚点与最终提交提示词，生成 final.mp4。适用于建筑空间展示，不适用于复杂角色表演。

> ⚠️ **这是一套配合使用的技能组合（2 个）** —— 正文互相引用，建议成套取用。

### ✨ 能做什么

- 一句话建筑/城市需求 → 可编辑 project.blend，保留场景、几何、命名、摄影机路径、动画与基础灯光
- Blender 原生渲染 2560×1440、16:9 RGB 预演视频，用户确认后锁定镜头路线
- 生成 3–4 张风格锚点图，配套 visual_bible.json、style_consistency_qa.json 与实际提交的提示词
- 把创意、关键帧、图片/视频/音频参考改写成官方 H3 格式提示词，默认 4–15 秒、24 FPS、原生立体声
- reference_manifest.json 区分事实与推演；shot_manifest.json 记录焦距、速度档位与确认状态
- 两技能串联：Blender RGB 预演 + 已确认风格关键帧 → H3 生成 final.mp4

### 📦 包含的技能（配合使用）

- `architecture-flythrough` —— 见 [`architecture-flythrough/SKILL.md`](architecture-flythrough/SKILL.md)
- `h3-prompt-expert` —— 见 [`h3-prompt-expert/SKILL.md`](h3-prompt-expert/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/h3-prompt-expert-suite.git
cp -r h3-prompt-expert-suite/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

A two-skill suite for architecture, landmark and city-space showcases. architecture-flythrough turns a one-line request into a reference-constrained editable 3D scene, a Blender-native 2560×1440 previs and a cinematic flythrough video; h3-prompt-expert turns video ideas, assets, keyframes, multimodal references and edit requests into production-ready H3 prompts. The two skills work together: Blender locks accurate space and the camera master and confirms the previs, then the prompt expert supplies style anchors and the final submitted prompt for final.mp4. Built for architectural display, not complex character performance.

> ⚠️ **A cooperating suite of 2 skills** — they reference each other; use them as a group.

### ✨ What it does

- One-line building or city brief → editable project.blend with scene, geometry, naming, camera path, animation and base lighting
- Blender-native 2560×1440 16:9 RGB previs video; the camera route is locked after your approval
- 3–4 style anchor keyframes plus visual_bible.json, style_consistency_qa.json and the exact submitted prompt
- Rewrites ideas, keyframes and image/video/audio references into official H3 prompts: 4–15s, 24 FPS, native stereo
- reference_manifest.json separates fact from inference; shot_manifest.json tracks focal length, speed tiers and approval state
- Both skills chained: Blender RGB previs + approved style keyframes → H3 final.mp4

### 📦 Skills included (designed to work together)

- `architecture-flythrough` — [`architecture-flythrough/SKILL.md`](architecture-flythrough/SKILL.md)
- `h3-prompt-expert` — [`h3-prompt-expert/SKILL.md`](h3-prompt-expert/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/h3-prompt-expert-suite.git
cp -r h3-prompt-expert-suite/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
