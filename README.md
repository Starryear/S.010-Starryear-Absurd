<div align="center">

# ◻️ Starryear-Clean-Absurd-Stage

**把真实照片展开成四次递进的不可能动作，让荒诞悬停在大片安静留白里。**

![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=for-the-badge&logo=openai&logoColor=white)
[![Usage](https://img.shields.io/badge/Usage-Personal%20%26%20Non--commercial-lightgrey?style=for-the-badge)](./LICENSE.md)
![Language](https://img.shields.io/badge/🌐_中文-English-blue?style=for-the-badge)

</div>

---

## ⚠️ 声明

> **仅限个人学习、非营利研究与非商业创作。** 任何商业使用均须事先取得 Starryear年 的书面许可。分享作品时，欢迎标注来源并 **@Starryear年**。

## 📖 关于本项目

本 Skill 将一张照片编排为真正的 2×2 四拼：左上保留真实证据，另外三格删除环境噪声，用原图中的主体和物件递进建立尺度滑移、承载反转与因果闭环。它追求的是“四格同一句怪话 + 每格一大片安静”，而不是堆叠奇幻元素。

- ✅ 保留原照片像素作为证据
- ✅ 三个生成格各用 45–70% 感知留白凸显一个荒诞关系
- ✅ 通过重量、接触、遮挡和阴影让不可能事件可信
- ❌ 不做拥挤四格、复杂城市、无来源符号或血腥身体恐怖

> 📝 The Skill includes the complete prompt in both **Chinese** and **English**.

## 🖼️ 示例作品

示例作品已收录于 [`assets/examples/`](assets/examples/)；这些图片用于展示不同照片在本 Skill 下形成的干净留白、尺度滑移与荒诞关系。

## 📋 目录

- [使用方法](#-使用方法)
- [可自由调整的部分](#-可自由调整的部分)
- [核心原则](#-核心原则)
- [内容结构](#-内容结构)
- [许可证](#-许可证)

## 🚀 使用方法

### 方式一：作为 Codex Skill 使用

1. 将 `008-starryear-clean-absurd-stage` 放入 `~/.codex/skills/`。
2. 开启新对话并上传一张你有权使用的照片。
3. 输入：`使用 $008-starryear-clean-absurd-stage，把这张照片做成干净留白的荒诞超现实四拼。`
4. 得到一张现实证据、尺度滑移、承载反转、因果闭环的 2:3 竖版四格 PNG。

### 方式二：直接使用完整提示词

| 语言 | 文件 |
| :---: | :--- |
| 🇨🇳 中文 | [references/008-starryear-clean-absurd-stage-prompt.zh-CN.md](references/008-starryear-clean-absurd-stage-prompt.zh-CN.md) |
| 🇬🇧 English | [references/008-starryear-clean-absurd-stage-prompt.en.md](references/008-starryear-clean-absurd-stage-prompt.en.md) |

## 🎛️ 可自由调整的部分

| 参数 | 说明 |
| :--- | :--- |
| **荒诞机制** | 尺度倒置、承载反转、主体自我观看、物件成为舞台；每次只选一种 |
| **留白比例** | 每个生成格感知留白 45–70%，默认约 58% |
| **舞台底色** | 从原图提取一种低饱和深色或浅色，保持大面积纯净 |
| **物质感** | 哑光舞台摄影、纸塑偶戏、织物或原图材质延伸；只用一种主材质 |

## 💡 核心原则

1. **一图一怪句** — 用原图名词和一个不可能动词构成唯一视觉命题。
2. **删除比增加重要** — 每个非必要人物、道具、纹理和背景都应移除。
3. **留白也是主体** — 三个生成格的留白都必须完整连续，不能被雾、颗粒、装饰或远景填满。
4. **递进而非重复** — 三格共享同一句荒诞命题，但尺度、承载与因果各向前推进一步。
5. **关系必须落地** — 巨人与微缩主体之间要有清楚的接触、重量和视线关系。

## 📁 内容结构

```text
008-starryear-clean-absurd-stage/
├── README.md
├── LICENSE.md
├── SKILL.md
├── agents/openai.yaml
├── references/
│   ├── 008-starryear-clean-absurd-stage-prompt.zh-CN.md
│   └── 008-starryear-clean-absurd-stage-prompt.en.md
└── assets/examples/
```

> `assets/examples/` 中仅收录 Starryear年提供或明确认可的示例作品。

## 📄 许可证

本项目采用 [LICENSE.md](./LICENSE.md) 中规定的使用条款。

<div align="center">

**如果这个项目对你有帮助，欢迎 Star ⭐ 支持！**

</div>
