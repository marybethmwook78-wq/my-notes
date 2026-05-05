---
dg-publish: true
permalink: research/hctd-presentation
title: HCTD 高精度无人机影像检测汇报
---

# HCTD：基于 CNN-Transformer 混合架构的高精度无人机影像目标检测器

> **汇报人**：郭帅  
> **研究课题**：针对深山搜救（SAR）场景下的小目标自适应检测  

---

## 📄 1. 论文/报告在线预览 (PDF)

> [!abstract] 预览说明
> 下方窗口将直接渲染 `imgs` 文件夹中的 PDF 文件。如果无法显示，请尝试刷新页面。

![[HCTD.pdf]]

---

## 📊 2. 汇报幻灯片下载 (PPTX)

由于 PPTX 为二进制加密格式，为了保证点击即下载且不发生跳转，我们直接调用 GitHub 原始数据源。

<div style="background-color: #f1f3f5; border: 2px dashed #adb5bd; padding: 25px; border-radius: 12px; text-align: center; margin: 25px 0;">
    <h3 style="margin-top: 0; color: #343a40;">HCTD 完整汇报演示文稿</h3>
    <p style="color: #6c757d; font-size: 0.9em;">包含 YOLOv8 与 RT-DETR 对比实验数据及特征图可视化</p>
    <br>
    <a href="https://github.com/marybethmwook78-wq/my-notes/raw/main/src/site/notes/imgs/HCTD.pptx" 
       download="HCTD_郭帅汇报.pptx" 
       style="background-color: #228be6; color: white; padding: 12px 30px; text-decoration: none; border-radius: 8px; font-weight: bold; display: inline-block; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
       📥 立即下载 PPTX 文件
    </a>
</div>

---

## 🚀 核心技术点
* **FFM**：有效过滤深山背景噪声，提升小目标显著性。
* **CASFI**：以加法代替点积，在 **94 FPS** 下实现全局交互。
* **GC²FPN**：解决传统 FPN 在下采样过程中的语义丢失问题。
