# S0｜CG 与 Blender 基础

> 阶段目标：从完全不会 Blender，到能够独立进入 Sculpt 工作流并完成一个简单人头 Blockout。

## 阶段交付

完成一个：

- 无材质
- 无毛孔
- 无头发
- 简单中性灰
- 具备正 / 侧 / 3/4 视角

的人头 Blockout。

---

## 学习顺序

### M0.1｜理解人物生产管线

- [ ] [L0.1.1 高精人物到底在做什么](L0.1.1.md)
- [ ] L0.1.2 Macro / Secondary / Tertiary
- [ ] L0.1.3 静帧、动画、游戏角色的区别

### M0.2｜Blender 生存基础

- [ ] L0.2.1 Viewport 与导航
- [ ] L0.2.2 G / R / S 与 Object / Edit Mode
- [ ] L0.2.3 Mirror 与 Subdivision

### M0.3｜进入 Sculpt

- [ ] L0.3.1 Grab / Clay / Smooth
- [ ] L0.3.2 Voxel Remesh
- [ ] L0.3.3 对称与非对称

---

# S0 Gate

完成 9 节课后，单独进行阶段验收。

必须做到：

```text
打开 Blender
↓
创建 Sphere
↓
进入 Sculpt
↓
使用 Grab / Clay / Smooth 建立头部大形
↓
Voxel Remesh
↓
使用 X Symmetry
↓
保存阶段版本
```

整个流程无需查教程。

## Gate 交付

```text
submissions/S0/GATE/
├── delivery.md
├── front.png
├── side.png
├── three-quarter.png
└── head-blockout.blend   # 可选 Git LFS
```

## Gate 判断

通过标准不是“像真人”，而是：

- 能独立操作 Blender 基本视图
- 知道当前处于 Object / Edit / Sculpt 哪个 Mode
- 能控制大形而不是随机刷表面
- 理解为什么使用 Voxel Remesh
- 理解为什么前期保持对称
- 能保存并回溯版本

通过后进入 S1：头部结构与基础雕刻。