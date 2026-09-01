# Blind2Blender

> 从 Blender 0 基础，到独立完成高精度写实人物静帧。

这是一个**中文、项目制、可交付、可验收**的 Blender 高精人物建模课程仓库。

本仓库不以“看完教程”为完成标准，而以：

```text
知识 → 实践 → 交付物 → 判断标准 → Pass / Fail
```

为每一节课的基本闭环。

## 课程目标

完成课程后，应能够独立完成一名高精度写实人物，包括：

- 人头与人体大形雕刻
- 真人肖像 Likeness
- 人体解剖与结构判断
- Retopology
- UV
- Multires / Baking
- 写实皮肤与眼睛
- Hair Curves 毛发
- 基础服装
- Cycles 肖像灯光与渲染

最终毕业作品：**1 个完整高精写实人物项目 + 完整制作 Breakdown**。

---

## 课程结构

课程使用三级层次：

```text
大阶段 Stage
└── 中阶段 Module
    └── 小课程 Lesson
```

共规划：

- 8 个 Stage
- 24 个 Module
- 72 个 Lesson
- 每节正文约 5 分钟阅读
- 实践时间不计入 5 分钟

### 大阶段

| Stage | 内容 | 核心交付 |
|---|---|---|
| S0 | CG 与 Blender 基础 | 第一个人头 Blockout |
| S1 | 头部结构与基础雕刻 | 男 / 女 / 老年人头 |
| S2 | 真人肖像与 Likeness | 真人灰模肖像 |
| S3 | 人体与全身人物 | 全身 Anatomy Gray Sculpt |
| S4 | Production Mesh | Retopo + UV + Bake |
| S5 | 写实皮肤与面部系统 | Skin / Eye LookDev |
| S6 | Hair / Clothing / Rendering | 完整角色 LookDev |
| S7 | 毕业项目 | 4K 最终作品 + Breakdown |

完整课程目录见：[`docs/CURRICULUM.md`](docs/CURRICULUM.md)

---

## 学习方式

每个 Lesson 都必须完成以下闭环：

```text
1. 阅读课程正文（约 5 分钟）
2. 完成实践任务
3. 保存 Blender 工程 / 截图
4. 填写交付记录
5. 对照判断标准自检
6. 提交 Review
7. Pass 后进入下一课
```

详细规则见：[`docs/LEARNING_RULES.md`](docs/LEARNING_RULES.md)

---

## 仓库目录

```text
blind2blender/
├── README.md
├── docs/
│   ├── CURRICULUM.md        # 完整课程地图
│   ├── LEARNING_RULES.md    # 学习与交付规则
│   └── EVALUATION.md        # 统一验收体系
├── courses/
│   └── S0-foundation/
│       └── README.md        # 当前阶段课程入口
├── templates/
│   └── lesson-delivery.md   # 每课交付模板
└── submissions/             # 学员交付物
```

> `.blend`、高分辨率贴图等大文件建议使用 Git LFS；仓库中的 Markdown 交付记录至少保留关键截图和判断结论。

---

## 当前学习状态

**当前 Stage：S0 — CG 与 Blender 基础**

开始入口：[`courses/S0-foundation/README.md`](courses/S0-foundation/README.md)

第一课：**L0.1.1 高精人物到底在做什么**

---

## 核心原则

### 1. 不以“看完”为完成

课程完成条件永远是可检查的 Artifact。

### 2. 大形优先于细节

```text
Primary Form
    ↓
Secondary Form
    ↓
Tertiary Detail
```

脸型错误时禁止用毛孔、皮肤和漂亮灯光掩盖问题。

### 3. Gate 制度

每个 Stage 都有阶段 Gate。

Gate 未通过时，原则上不进入下一阶段。

### 4. 作品阶段与训练阶段分离

训练时允许从球开始雕刻以学习结构；正式作品允许使用高质量 Base Mesh 提高生产效率。

---

## 交付命名约定

推荐：

```text
submissions/
└── S0/
    └── L0.3.3/
        ├── delivery.md
        ├── front.png
        ├── side.png
        └── three-quarter.png
```

Blender 工程：

```text
L0.3.3-head-blockout-v01.blend
L0.3.3-head-blockout-v02.blend
```

不要覆盖关键阶段版本。

---

## 课程语言

**课程正文、交付记录、Review 默认全部使用中文。**

Blender UI 可以使用中文或英文；课程会同时给出关键功能的中英文名称，优先帮助建立行业常用英文术语。