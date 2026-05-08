---
AIGC:
    ContentProducer: Minimax Agent AI
    ContentPropagator: Minimax Agent AI
    Label: AIGC
    ProduceID: 239d2cf23808df3373b7f6d0a72a3604
    PropagateID: 239d2cf23808df3373b7f6d0a72a3604
---

# 会议智能引导数字人 - MeetingSage

## 1. Concept & Vision

MeetingSage 是一个具有"灵魂"的虚拟会议引导数字人。它不仅仅是一个工具，而是一个有性格、有原则、有温度的AI会议伙伴。用户可以深度定制它的核心理念（灵魂）、必须遵守的行为准则（原则）、以及擅长的会议流程（流程库）。当数字人开口说话时，它的每一句引导都透露着它独特的个性。

## 2. Design Language

### 色彩系统
- Primary: #6366f1 (靛蓝紫)
- Secondary: #8b5cf6 (紫罗兰)
- Accent: #f472b6 (玫瑰粉)
- Background: #0f172a (深色)

## 3. 功能特性

### 核心功能

- **数字人灵魂配置**
  - 自定义名称（2-8字）
  - 5种头像风格
  - 5种声音风格
  - 核心价值观
  - 4种说话风格

- **会议原则管理**
  - 守时原则
  - 平等原则
  - 共识原则
  - 情感原则
  - 效率原则
  - 创意原则

- **会议流程模板**
  - 头脑风暴（20分钟）
  - 决策讨论（30分钟）
  - 项目复盘（40分钟）
  - 每日站会（15分钟）
  - 规划会议（60分钟）

- **会议录音** - MediaRecorder API
- **语音播报** - Web Speech API
- **会议纪要** - 本地记录导出
- **智能计时器** - 圆形进度环

## 4. 技术栈

- HTML5 + CSS3 + JavaScript
- Web Speech API
- MediaRecorder API
- localStorage

## 5. 浏览器兼容性

- Chrome ✅ 推荐
- Edge ✅ 推荐
- Firefox ✅ 支持
- Safari ⚠️ 部分支持