# Malang - 专业AI图像提示词生成器

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/OYYH-Apple/malang?style=flat-square)](https://github.com/OYYH-Apple/malang/stargazers)
[![License](https://img.shields.io/github/license/OYYH-Apple/malang?style=flat-square)](LICENSE)

</div>

Malang 是一个专业的AI图像提示词生成器，能够将自然语言描述转化为高质量、结构化的提示词文档。支持多种主流AI图像生成工具。

## 功能特性

### 核心功能

- **多工具支持**：Midjourney、DALL-E、Stable Diffusion、即梦、Seedance 等
- **结构化输出**：主体描述、风格指导、构图参数、光线设置、颜色方案、氛围渲染
- **中英双语**：自动生成中英文双版本提示词
- **技术参数**：推荐分辨率、采样器、步数、CFG Scale 等

### 特色功能

- **宫格分镜生成**：基于图片自动生成九宫格/十六宫格等电影级分镜脚本
- **视频提示词**：同步生成适用于AI视频工具的提示词
- **一致性控制**：保持人物、服装、光线、色调全程一致
- **文档保存**：自动生成可下载的 Markdown 文档

## 适用场景

| 场景 | 说明 |
|------|------|
| AI图像生成 | 艺术创作、商业设计、概念设计 |
| 分镜脚本 | 电影分镜、产品展示、故事叙述 |
| 提示词优化 | 权重调整、负面约束、技术参数 |

## 支持的宫格规格

- **3x3 九宫格**：9个镜头，适合完整分镜展示
- **4x4 十六宫格**：16个镜头，更详细的分镜
- **2x3 六宫格**：6个镜头，简洁版分镜
- **自定义规格**：根据需求灵活调整

## 快速开始

### 安装

```bash
# 克隆仓库
git clone https://github.com/OYYH-Apple/malang.git

# 进入目录
cd malang
```

### 使用方法

在 opencode 中触发 Malang 技能：

```
"帮我生成提示词"
"画一张图"
"设计一个画面"
"创作艺术作品"
"生成AI图像"
"做分镜"
"生成九宫格"
"帮我写分镜脚本"
```

## 项目结构

```
malang/
├── SKILL.md              # 技能主文件
├── LICENSE               # 许可证
├── agents/               # Agent 相关资源
├── assets/               # 静态资源
├── evals/                # 评估测试
├── references/           # 参考文档
└── scripts/              # 辅助脚本
```

## 风格库

内置多种艺术风格供参考：

| 类型 | 风格 |
|------|------|
| 艺术风格 | 写实、插画、动漫、油画、水彩、像素艺术、低多边形 |
| 摄影风格 | 人像、风景、微距、街头、商业 |
| 设计风格 | 扁平化、拟物化、玻璃态、孟菲斯、包豪斯 |
| 概念风格 | 赛博朋克、蒸汽朋克、极简主义 |

## 技术参数建议

| 参数 | 推荐值 |
|------|--------|
| 分辨率 | 1024x1024 或 16:9 横版 |
| 采样器 | DPM++ 2M Karras |
| 步数 | 25-30 步 |
| CFG Scale | 7-9 |

## 贡献

欢迎提交 Issue 和 Pull Request！

## 许可证

本项目采用 [LICENSE](LICENSE) 许可证。

---

<div align="center">

Made with ❤️ for AI Image Generation

</div>
