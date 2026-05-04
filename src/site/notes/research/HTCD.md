---
{"dg-publish":true,"permalink":"/research/htcd/","title":"HCTD 研究成果展示","dg-note-properties":{"permalink":"research/htcd","title":"HCTD 研究成果展示"}}
---


# HCTD：基于 CNN-Transformer 混合架构的高精度无人机影像目标检测器

> **作者**：郭帅  
> **研究领域**：计算机视觉、无人机影像 (UAV)、小目标检测

---

## 📄 1. 论文/报告在线预览 (PDF)

> [!abstract] 提示
> 如果下方窗口未显示，请尝试刷新页面。你也可以使用预览窗顶部的工具栏进行放大或旋转。

[[HTCD.pdf\|HTCD.pdf]]

---

## 📊 2. 汇报幻灯片下载 (PPTX)

由于 PPTX 为二进制格式，为了保证最佳的下载体验且不发生页面跳转，请点击下方按钮。

<div style="background-color: #f8f9fa; border: 1px solid #dee2e6; padding: 20px; border-radius: 8px; text-align: center; margin: 20px 0;">
    <p style="margin-bottom: 15px; color: #495057;">包含模型架构、实验对比及可视化结果的完整 PPT</p>
    <a href="https://github.com/marybethmwook78-wq/my-notes/raw/main/src/site/notes/research/HTCD.pptx" 
       download="HTCD_郭帅汇报.pptx" 
       style="background-color: #007bff; color: white; padding: 10px 25px; text-decoration: none; border-radius: 5px; font-weight: bold; display: inline-block;">
       📥 立即下载 HTCD 演示文稿 (PPTX)
    </a>
</div>

---

## 🚀 核心创新点回顾
1. **FFM (特征过滤模块)**：利用双全局池化压制背景噪声。
2. **CASFI (卷积加性自注意力)**：将复杂度从 $O(N^2D)$ 降至线性级。
3. **GC²FPN (全局上下文流金字塔)**：通过语义过滤解决小目标丢失问题。

---

## 📈 实验表现 (VisDrone2019)
| 模型 | 推理速度 (FPS) | $AP_{50}$ (%) | $AP_S$ (%) |
| :--- | :--- | :--- | :--- |
| **HCTD (Res50)** | **94** | **43.7** | **14.7** |
| RT-DETR-R50 | 90 | 41.5 | 13.2 |