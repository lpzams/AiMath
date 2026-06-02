# AiMath - 数学知识问答系统

<div align="center">

![AiMath Logo](https://img.shields.io/badge/AiMath-数学知识问答-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.11+-green?style=for-the-badge&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-0.109+-009688?style=for-the-badge&logo=fastapi)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**基于 RAG 技术的智能数学知识问答系统**

[功能特性](#功能特性) • [技术架构](#技术架构) • [快速开始](#快速开始) • [文档](#文档) • [贡献指南](#贡献指南)

</div>

---

## 📖 项目简介

AiMath 是一个专注于数学领域的智能问答系统，采用 **RAG（检索增强生成）** 技术，能够处理多种格式的数学资料（PDF、Word、Markdown、LaTeX 公式、图片等），构建结构化的数学知识库，并提供准确、详细的数学问题解答。

### 核心优势

- 🎯 **专业数学处理**：支持 LaTeX 公式解析、数学符号识别、定理证明理解
- 📚 **多源知识整合**：统一处理教材、论文、笔记、网页等异构数据源
- 🧠 **知识图谱增强**：构建概念关系网络，支持知识推理和关联查询
- ⚡ **高性能检索**：向量检索 + 混合检索，毫秒级响应
- 🔄 **持续学习**：支持知识库动态更新和质量评估

---

## ✨ 功能特性

### 1. 文档处理模块

- ✅ **多格式支持**
  - PDF 文档（原生 + 扫描版）
  - Word 文档（.docx）
  - Markdown 文件
  - LaTeX 源文件
  - 图片（公式识别）
  - 网页内容

- ✅ **智能解析**
  - 文档结构识别（章节、段落、列表）
  - 表格提取与结构化
  - 公式识别与标准化
  - 图片 OCR（Mathpix）
  - 元数据提取

- ✅ **内容分块**
  - 语义感知分块
  - 保持公式完整性
  - 上下文窗口优化
  - 分块质量评估