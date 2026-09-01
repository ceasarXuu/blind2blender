# Blind2Blender 课程地图

> 目标：Blender 0 基础 → 独立完成高精写实人物静帧。

## 总览

| Stage | Module | Lessons | 阶段交付 |
|---|---:|---:|---|
| S0 基础 | 3 | 9 | 人头 Blockout |
| S1 头部 | 3 | 9 | 男 / 女 / 老年人头 |
| S2 Likeness | 3 | 9 | 真人灰模肖像 |
| S3 人体 | 3 | 9 | 全身人体灰模 |
| S4 Production Mesh | 3 | 9 | Retopo + UV + Bake |
| S5 LookDev | 3 | 9 | Skin / Eye / Micro Detail |
| S6 完整角色 | 3 | 9 | Hair / Clothing / Render |
| S7 毕业项目 | 3 | 9 | 4K 成片 + Breakdown |

总计：**72 Lessons**。

---

# S0｜CG 与 Blender 基础

## M0.1｜理解人物生产管线

### L0.1.1 高精人物到底在做什么
- 目标：建立人物 CG 全流程认知。
- 交付：一张人物 Production Pipeline 图。
- Pass：能解释 Sculpt / Retopo / UV / Texture / Groom / Render 各自解决什么问题。

### L0.1.2 Macro / Secondary / Tertiary
- 目标：理解三级细节层级。
- 交付：对 3 张人物参考图标注三级结构。
- Pass：不把毛孔、皱纹误判为决定 Likeness 的主要因素。

### L0.1.3 静帧、动画、游戏角色的区别
- 目标：确定本课程目标边界。
- 交付：一页项目范围说明。
- Pass：明确当前目标是高精写实静帧，不以实时游戏拓扑和完整动画 Rig 为主目标。

## M0.2｜Blender 生存基础

### L0.2.1 Viewport 与导航
- 目标：掌握视图观察。
- 交付：同一物体的正 / 侧 / 顶 / 3/4 截图。
- Pass：可独立完成视图旋转、平移、缩放与正交视图切换。

### L0.2.2 G / R / S 与 Object / Edit Mode
- 目标：掌握最基本物体操作。
- 交付：一个由基本体修改得到的简单模型。
- Pass：能正确区分 Object Mode 与 Edit Mode。

### L0.2.3 Mirror 与 Subdivision
- 目标：掌握人物建模常用 Modifier。
- 交付：一个左右对称模型。
- Pass：Mirror 与 Subdivision 顺序正确，无明显中缝、破面。

## M0.3｜进入 Sculpt

### L0.3.1 Grab / Clay / Smooth
- 目标：只依赖三个核心 Brush 改大形。
- 交付：简单头部体块。
- Pass：能主动使用 Grab 改轮廓、Clay 堆体积、Smooth 控制表面，而不是随机刷。

### L0.3.2 Voxel Remesh
- 目标：理解自由雕刻阶段的拓扑重建。
- 交付：从 Sphere 雕出的头部轮廓。
- Pass：修改大形后可自行 Remesh，无严重孔洞或结构丢失。

### L0.3.3 对称与非对称
- 目标：理解雕刻阶段的 Symmetry 策略。
- 交付：一个对称头部 Blockout + 一次非对称调整记录。
- Pass：能解释何时保持 X Symmetry、何时取消。

### S0 Gate
必须能不查教程完成：创建 Sphere → Sculpt → Voxel Remesh → 对称编辑 → 保存版本。

---

# S1｜头部结构与基础雕刻

## M1.1｜理解头骨

### L1.1.1 头不是一个球
- 目标：区分脑颅与面颅。
- 交付：简化头骨体块。
- Pass：侧面轮廓能明确看出脑颅与面部的前后关系。

### L1.1.2 五个骨性标志
- 目标：掌握眉弓、眼眶、颧骨、下颌、下巴。
- 交付：带结构标记的头部灰模。
- Pass：正 / 侧 / 3/4 位置关系基本一致。

### L1.1.3 正侧面比例
- 目标：建立基础头部比例感。
- 交付：无五官头部。
- Pass：不依赖眼鼻口也能看出自然人头体块。

## M1.2｜眼鼻口结构

### L1.2.1 眼窝，不是眼睛
- 目标：理解 Orbit、眼球、眼睑的空间关系。
- 交付：完整眼眶结构。
- Pass：移除眼球后仍有明确眼窝结构。

### L1.2.2 鼻骨与鼻软骨
- 目标：理解鼻子的骨性与软组织体块。
- 交付：完整鼻部雕刻。
- Pass：正、侧、仰视均成立。

### L1.2.3 嘴不是两根香肠
- 目标：理解口周体块与上下唇嵌入关系。
- 交付：自然闭嘴结构。
- Pass：嘴唇不是贴在脸表面的独立条状体。

## M1.3｜完善整个头

### L1.3.1 下巴与下颌
- 目标：理解 Jaw Line 对脸型的决定作用。
- 交付：3 种不同下颌形态。
- Pass：仅调整 Jaw / Chin 就能产生明显不同脸型。

### L1.3.2 耳朵结构
- 目标：掌握耳朵主要体块。
- 交付：一个完整耳朵。
- Pass：缩小观察仍有合理轮廓，不依赖密集沟槽伪装结构。

### L1.3.3 头颈连接
- 目标：解决“脑袋插在圆柱上”。
- 交付：头颈半身灰模。
- Pass：主要颈部转折与锁骨连接合理。

### S1 Gate
交付男性、女性、老年人头。只使用灰材质与普通侧光；禁止毛孔、皮肤、头发。正面、侧面、3/4 与 Silhouette 都必须成立。

---

# S2｜真人肖像与 Likeness

## M2.1｜参考图系统

### L2.1.1 如何选真人参考
- 目标：构建可靠 Reference Set。
- 交付：8–20 张同人物参考图。
- Pass：包含正、侧、3/4，且避免严重美颜与夸张广角。

### L2.1.2 焦距如何骗人
- 目标：理解透视与焦距对脸部比例的影响。
- 交付：35 / 50 / 85 / 120mm 对比分析。
- Pass：能说明广角为何改变鼻子、脸宽与耳朵的视觉比例。

### L2.1.3 Reference Board
- 目标：区分结构参考与材质参考。
- 交付：完整 Reference Board。
- Pass：参考图用途标注清楚。

## M2.2｜Likeness 方法

### L2.2.1 先看轮廓
- 目标：从 Silhouette 判断人物身份特征。
- 交付：真人轮廓分析。
- Pass：黑色剪影中仍保留明显特征。

### L2.2.2 比例关系
- 目标：提取关键比例。
- 交付：眼距、脸宽、鼻长、下巴等比例分析图。
- Pass：比例测量与模型调整能够对应。

### L2.2.3 特征优先级
- 目标：找到最重要的 5 个身份特征。
- 交付：Feature Priority List。
- Pass：能解释优先改哪 5 个地方最能提升相似度。

## M2.3｜第一次真人肖像

### L2.3.1 Primary Pass
- 目标：先建立整体体积与比例。
- 交付：第一版肖像灰模。
- Pass：不做眼睑、皱纹等细节也已有基本相似度。

### L2.3.2 Secondary Pass
- 目标：建立眼鼻口、面颊与脂肪转折。
- 交付：第二版肖像灰模。
- Pass：局部结构清楚且没有破坏整体比例。

### L2.3.3 Asymmetry
- 目标：引入自然不对称。
- 交付：最终灰模肖像。
- Pass：左右不完全镜像，但不存在故意“做歪”的人工感。

### S2 Gate
将肖像截图缩小到 300–500 px；仍能明显辨识参考人物才通过。失败时禁止进入毛孔与材质阶段。

---

# S3｜人体与全身人物

## M3.1｜人体骨架与比例

### L3.1.1 人体比例
- 目标：建立全身比例。
- 交付：简化 Mannequin。
- Pass：正侧面无明显头身、四肢比例错误。

### L3.1.2 胸腔与骨盆
- 目标：理解人体两大质量块。
- 交付：Ribcage + Pelvis Blockout。
- Pass：两个体块可独立旋转并形成自然躯干。

### L3.1.3 Gesture
- 目标：避免僵硬站桩。
- 交付：5 个简化 Pose。
- Pass：重心与动作主线清晰。

## M3.2｜躯干与四肢

### L3.2.1 肩膀与手臂
- 目标：理解肩胛、锁骨、上臂连接。
- 交付：上半身模型。
- Pass：手臂抬起时肩部结构合理。

### L3.2.2 骨盆与腿
- 目标：理解腿根、臀部、股骨关系。
- 交付：下半身模型。
- Pass：大腿不是简单圆柱插入骨盆。

### L3.2.3 Torso Surface
- 目标：建立躯干主要表面转折。
- 交付：完整 Torso。
- Pass：不刻肌肉沟仍能看出骨性与软组织结构。

## M3.3｜手脚与整合

### L3.3.1 手
- 目标：掌握 Palm + Finger 结构。
- 交付：一双手。
- Pass：远看像手而不是五根等粗圆柱。

### L3.3.2 脚
- 目标：掌握足弓与脚趾结构。
- 交付：一双脚。
- Pass：正、侧面都有明确足弓与受力逻辑。

### L3.3.3 Head-Hand-Foot Integration
- 目标：完成全身比例整合。
- 交付：裸体 Base Character。
- Pass：头、手、脚与身体比例协调。

### S3 Gate
完成无衣服、无头发、无材质的全身人体灰模。判断 Silhouette / Anatomy / Proportion / Gesture / Weight。

---

# S4｜Production Mesh

## M4.1｜Retopology

### L4.1.1 为什么必须重拓扑
- 目标：理解高模与生产网格的角色差异。
- 交付：高低模对比说明。
- Pass：能解释 Sculpt Mesh 为什么不能直接承担所有后续任务。

### L4.1.2 Face Loops
- 目标：学习面部基本 Loop。
- 交付：Retopo Head。
- Pass：眼、嘴、鼻周围 Loop 合理。

### L4.1.3 Body Topology
- 目标：完成身体拓扑。
- 交付：全身低模。
- Pass：肩、肘、膝等区域密度合理，无大量无意义面数。

## M4.2｜UV

### L4.2.1 UV 的本质
- 目标：理解 3D → 2D 展开。
- 交付：Head UV。
- Pass：无非预期重叠。

### L4.2.2 Seam 设计
- 目标：控制切缝位置。
- 交付：完整 UV。
- Pass：正面关键区域无明显 Seam。

### L4.2.3 Texel Density
- 目标：建立纹理密度意识。
- 交付：UV Layout 对比。
- Pass：重点区域纹理精度合理且一致。

## M4.3｜Multires 与 Baking

### L4.3.1 Multires 工作流
- 目标：建立多层级雕刻习惯。
- 交付：Multires Character。
- Pass：不同层级分别承担大形、中形、小形调整。

### L4.3.2 Normal 与 Displacement
- 目标：理解两类细节表达方式。
- 交付：对比 Render。
- Pass：能判断某一类细节应进入 Normal 还是 Displacement。

### L4.3.3 Bake 高模细节
- 目标：完成高低模细节转移。
- 交付：第一套 Bake Maps。
- Pass：无明显接缝、投射错误与爆点。

### S4 Gate
Retopo + UV + Bake 全流程可复现，无技术阻塞。

---

# S5｜写实皮肤与面部系统

## M5.1｜皮肤材质

### L5.1.1 皮肤不是一个颜色
- 目标：理解 Skin Color Variation。
- 交付：Base Color。
- Pass：不同区域存在自然色彩变化而不是单色填充。

### L5.1.2 Roughness 比颜色更重要
- 目标：理解高光分布。
- 交付：Roughness Map。
- Pass：鼻头、额头、嘴唇等反射差异合理。

### L5.1.3 SSS
- 目标：理解皮下散射。
- 交付：Skin Shader。
- Pass：薄区域透光自然，不出现蜡像感。

## M5.2｜眼睛与口腔

### L5.2.1 写实眼球结构
- 目标：建立 Cornea / Iris / Sclera 分层。
- 交付：完整眼球。
- Pass：近距离不呈现“贴图玻璃球”感。

### L5.2.2 Eyelid + Tearline
- 目标：处理眼球与眼睑接触。
- 交付：完整眼部 LookDev。
- Pass：不存在悬空、穿插或干涩假眼感。

### L5.2.3 Teeth / Gum / Tongue
- 目标：建立基础口腔系统。
- 交付：口腔模型。
- Pass：张嘴状态不出现黑洞或纯白假牙。

## M5.3｜Micro Detail

### L5.3.1 毛孔为什么不能乱撒
- 目标：理解毛孔区域差异。
- 交付：Pore Reference Sheet。
- Pass：能区分鼻、脸颊、额头毛孔类型和密度。

### L5.3.2 Wrinkle Hierarchy
- 目标：理解皱纹层级。
- 交付：Wrinkle Pass。
- Pass：存在主次结构而不是均匀噪声。

### L5.3.3 Micro Displacement
- 目标：完成微表面。
- 交付：最终 Skin Detail。
- Pass：正常观看距离几乎不可见，近距离才增加真实感。

### S5 Gate
关闭 Base Color，只保留灰度材质与灯光；如果模型明显崩坏，返回 S2 修结构。

---

# S6｜Hair / Clothing / Rendering

## M6.1｜Hair Groom

### L6.1.1 Guide Hair
- 目标：学习 Hair Curves Guide。
- 交付：基础 Guides。
- Pass：只看 Guides 就能辨认发型。

### L6.1.2 Clump / Frizz
- 目标：建立毛发层级。
- 交付：完整 Hair Groom。
- Pass：同时存在大束、中束、碎发。

### L6.1.3 Brow / Lash / Peach Fuzz
- 目标：完善面部毛发。
- 交付：Facial Hair。
- Pass：眉毛、睫毛方向符合自然生长规律。

## M6.2｜服装

### L6.2.1 Clothing Blockout
- 目标：建立衣服大形。
- 交付：简单上衣。
- Pass：服装有厚度，不直接吸附身体表面。

### L6.2.2 Fold Hierarchy
- 目标：理解褶皱主次。
- 交付：Cloth Sculpt。
- Pass：存在 Primary / Secondary Folds。

### L6.2.3 Fabric Detail
- 目标：添加织物微细节。
- 交付：Clothing Material。
- Pass：远看依赖大褶皱，近看才出现织物纹理。

## M6.3｜Portrait Rendering

### L6.3.1 Portrait Camera
- 目标：建立合理肖像镜头。
- 交付：Camera Setup。
- Pass：无明显不必要广角畸变。

### L6.3.2 观察式布光
- 目标：让灯光服务结构表达。
- 交付：Portrait Lighting。
- Pass：主要面部体块清楚，不靠极端阴影掩盖问题。

### L6.3.3 Cycles Final
- 目标：完成稳定最终渲染。
- 交付：2K+ Portrait。
- Pass：Noise、Fireflies、曝光与色彩无明显技术问题。

### S6 Gate
角色从建模到 LookDev、毛发、服装、镜头与灯光形成完整静帧生产链。

---

# S7｜毕业项目

## M7.1｜Pre-production

### L7.1.1 Character Brief
- 目标：明确角色目标。
- 交付：一页 Brief。
- Pass：年龄、气质、服装、镜头与目标风格明确。

### L7.1.2 Reference Pack
- 目标：建立完整资料。
- 交付：Reference Board。
- Pass：Anatomy / Skin / Hair / Clothing / Lighting 均有参考。

### L7.1.3 Definition of Done
- 目标：防止无限精雕。
- 交付：DoD Checklist。
- Pass：能明确项目何时算完成。

## M7.2｜生产 Milestone

### L7.2.1 Shape Gate
- 目标：锁定一级形体。
- 交付：Gray Sculpt。
- Pass：不依赖材质仍成立。

### L7.2.2 Production Gate
- 目标：完成生产网格。
- 交付：Retopo + UV + Bake。
- Pass：技术层无阻塞问题。

### L7.2.3 LookDev Gate
- 目标：完成人物外观。
- 交付：Skin + Hair + Clothing。
- Pass：近、中、远距离都成立。

## M7.3｜Final Review

### L7.3.1 Error Hunting
- 目标：训练主动发现问题。
- 交付：Defect List。
- Pass：至少主动找到 10 个可改问题并排序。

### L7.3.2 Final Render
- 目标：完成最终作品。
- 交付：4K 主图 + 至少 3 张 Detail。
- Pass：无明显结构、穿模、材质或渲染错误。

### L7.3.3 Portfolio Breakdown
- 目标：总结制作过程。
- 交付：Breakdown Sheet。
- Pass：可清晰展示 Sculpt → Topology → Texture → Hair → Render 流程。

### S7 Gate / Graduation
完成 1 个可公开展示的高精写实人物项目，并能解释主要设计与技术决策。