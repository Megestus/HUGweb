---
title: NormalEdit module
icon: fa-solid fa-wand-magic-sparkles
category:
  - Tools Module
tags:
  - Normal Edit
  - Maya
date: 2024-03-21
# star: 1
article: false
---

NormalEdit 模块提供了一套用于操作和编辑模型法线的功能

## 主要功能

### 1. 显示控制

- **法线显示开关**：快速打开或关闭法线显示。
- **法线长度调整**：通过滑块或数值输入精确控制法线显示长度。

### 2. 法线锁定

- **锁定法线**：防止法线被意外修改。
- **解锁法线**：允许编辑法线。

### 3. 快速设置

- **轴向设置**：将选定顶点的法线设置为 +X, +Y, +Z, -X, -Y, -Z 方向。
- **轴向平均**：分别在 X, Y, Z 轴上平均法线。
- **整体平均**：平均所有选定顶点的法线。

### 4. 手动编辑

- **获取法线**：读取选定顶点或面的当前法线值。
- **设置法线**：通过手动输入 X, Y, Z 值精确设置法线方向。

### 5. 法线传递

- **获取源模型**：选择模型作为法线的来源。
- **传递法线**：将源模型的法线传递到目标模型。
