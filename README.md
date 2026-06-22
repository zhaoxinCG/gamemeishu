---
AIGC:
    Label: "1"
    ContentProducer: 001191110102MACQD9K64018705
    ProduceID: 80711082585128_0-data_volume/7653134343195640099-files/所有对话/主对话/deploy/README.md
    ReservedCode1: ""
    ContentPropagator: 001191110102MACQD9K64028705
    PropagateID: 80711082585128#1782113751608
    ReservedCode2: ""
---
# 美术流水线：从原画到上线

> 一款模拟游戏公司美术岗完整协作流程的文字冒险游戏

## 🎮 在线游玩

**👉 https://zhaoxinCG.github.io/meishu-liuxianshui/**

（首次访问可能需要等待 GitHub Pages 部署 1-2 分钟）

## 🎬 游戏介绍

以第一人称视角体验游戏美术新人的入职历程：
- 📐 项目立项：确定美术风格方向
- 🎨 原画设计：把概念落到具体画面
- 📦 外包管理：审核外部团队的PBR资产
- 🏗️ 地编协作：把资产放进关卡场景
- ⚙️ 技术美术：性能优化与渲染管线
- 💻 程序对接：让美术效果在引擎里跑起来
- 🧪 测试上线：打磨每一个细节

## ✨ 游戏特色

- 🎬 18秒开场动画交代背景
- 📋 完整的游戏规则说明
- 💼 每个NPC标注真实职位（项目总监/原画师/外包/地编/TA/程序）
- 🎵 Web Audio API 程序化生成 BGM（无外部音频文件）
- 🖱️ 选项点击音效 + 打字机音效
- 🏆 5个成就解锁（项目立项/茶水间/PBR专家/关卡大师/独当一面）
- 📚 12个教学场景，涵盖外包 PBR、关卡优化、TA 等真实知识点
- 📱 完整移动端适配

## 🚀 本地运行

```bash
# 方式 1：双击 index.html

# 方式 2：起一个本地服务器（推荐）
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

## 📁 文件结构

```
.
├── index.html       # 游戏主文件（自包含，约24MB）
├── README.md        # 本文件
└── .nojekyll        # 跳过 Jekyll 处理
```

## 🛠️ 技术栈

- 纯 HTML + CSS + JavaScript（无外部依赖）
- Web Audio API 程序化生成 BGM 和音效
- 角色立绘与背景图 base64 内嵌

## 📜 许可

游戏内容仅供学习交流使用。

---

> 本内容由 Coze AI 生成，请遵循相关法律法规及《人工智能生成合成内容标识办法》使用与传播。
