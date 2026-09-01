# 学习与交付规则

## 1. 每课闭环

每节 Lesson 必须完成：

```text
阅读课程正文
  ↓
实践
  ↓
保存阶段版本
  ↓
截图 / 导出交付物
  ↓
填写 delivery.md
  ↓
自评
  ↓
Review
  ↓
Pass / Revise
```

阅读完成不等于课程完成。

---

## 2. 交付目录

推荐结构：

```text
submissions/
└── S0/
    └── L0.3.3/
        ├── delivery.md
        ├── front.png
        ├── side.png
        ├── three-quarter.png
        └── silhouette.png
```

大文件可另外使用 Git LFS。

---

## 3. 每课交付必须回答

1. 本课目标是什么？
2. 我实际做了什么？
3. 交付物在哪里？
4. 哪些判断标准已满足？
5. 哪些判断标准未满足？
6. 当前最明显的三个问题是什么？
7. 下一次修改优先级是什么？

使用 `templates/lesson-delivery.md`。

---

## 4. Review 状态

统一只使用四种状态：

- `NOT_STARTED`：未开始
- `IN_PROGRESS`：正在实践
- `REVISE`：未通过，需要修改
- `PASS`：达到课程标准

不要使用“差不多”“基本完成”一类模糊状态。

---

## 5. Gate 规则

每个 Stage 最后有一个 Gate。

Gate 检查的是综合能力，而不是单课知识。

原则：

```text
Lesson Pass ≠ Stage Pass
```

某个阶段全部 Lesson 完成后，仍必须单独提交 Gate 交付。

---

## 6. 雕刻版本管理

关键阶段不要覆盖文件。

建议：

```text
portrait-v01-primary.blend
portrait-v02-proportion.blend
portrait-v03-secondary.blend
portrait-v04-asymmetry.blend
```

这样可以比较形体决策，而不是只保留最终版本。

---

## 7. 截图规范

人物 Sculpt 交付默认至少包含：

- Front
- Side
- 3/4
- Silhouette 或低曝光轮廓观察

如果课程涉及局部结构，再补充 Close-up。

截图原则：

- 使用中性灰材质
- 避免夸张景深
- 避免复杂环境光
- 不使用美化结构的极端灯光
- 相机焦距保持一致，除非课程专门研究焦距

---

## 8. 禁止“细节掩盖大形”

S0–S2 的结构训练阶段，除课程明确要求外：

- 禁止毛孔
- 禁止皮肤贴图
- 禁止复杂毛发
- 禁止强烈电影灯光
- 禁止通过后期修图改变形体判断

如果缩略图下形体不成立，应回到 Primary / Secondary Form，而不是继续增加细节。

---

## 9. 参考资料使用规则

允许：

- 真人照片
- Anatomy 图谱
- 高质量雕塑参考
- 官方 Blender 文档
- 专业课程作为补充

但交付必须说明：

- 哪些是观察所得
- 哪些是直接临摹
- 是否使用 Base Mesh
- 是否使用扫描 / 商业贴图 / Alpha

课程目标是形成可迁移能力，不是假装所有资产都从零制作。

---

## 10. 正式作品与训练的区别

训练：

> 可以从 Sphere 开始，优先训练结构理解。

作品：

> 可以使用高质量 Base Mesh、商业纹理、Alpha 等生产资产，但必须理解并记录其作用。

这两种方式不冲突。

---

## 11. 向 ChatGPT 提交 Review 的推荐方式

完成某课后，可以直接说：

```text
Review blind2blender 的 L1.2.1。
这是我的交付：<PR / commit / 文件截图>。
按课程标准判断 Pass / Revise，不要因为是初学者降低标准；
如果 Revise，最多给我 3 个最高优先级修改项。
```

Review 应优先回答：

```text
结论
↓
证据
↓
最高优先级错误
↓
怎么验证修改是否成功
```

而不是给出几十条零散建议。