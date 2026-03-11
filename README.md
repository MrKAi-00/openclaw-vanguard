# 🛡️ OpenClaw-Vanguard (先锋卫士)

[![English](https://img.shields.io/badge/Language-English-blue.svg)](#english) [![简体中文](https://img.shields.io/badge/Language-简体中文-red.svg)](#简体中文)

---

<a id="english"></a>
## 🇬🇧 English

> **"Endowing your AI Agent with physical eyes and ears."**

OpenClaw-Vanguard is an experimental **multi-modal IoT Security Node** architecture. It defends against malicious digital commands while actively monitoring physical environments via camera and microphone.

### 🚀 Core Features
* **👁️ Multi-modal Perception:** Dual-thread execution capturing high-decibel noise and unauthorized faces in real-time.
* **🧠 LLM Threat Assessment:** Transcripts of audio (e.g., arguments) are sent to an LLM for intent analysis, accurately judging threat levels (HIGH/LOW).
* **🥊 Active Deterrence:** Triggers TTS warnings and smart home lighting alerts when strangers linger.
* **☢️ Panic Lockdown:** Specific panic words trigger immediate screen lock, stealth snapshotting, and fallback disguise mode.
* **📋 Daily SITREP:** Automatically summarizes daily security logs into a secret-agent-style briefing.

### 🛠️ Status
Currently a **Proof of Concept (PoC)**. The logic is decoupled and ready for real OpenCV/PyAudio streams and LLM APIs. PRs are highly welcome to help deploy Vanguard on edge devices like Raspberry Pi!

---

<a id="简体中文"></a>
## 🇨🇳 简体中文

> **"为你的 AI Agent 赋予物理世界的双眼与双耳。"**

OpenClaw-Vanguard 是一个实验性的**多模态物理空间安防节点 (IoT Security Node)** 架构。它不仅能在数字世界防御恶意指令，更能通过摄像头和麦克风监控现实物理环境的异常。

### 🚀 核心战术能力
* **👁️ 多模态环境感知：** 双线程独立运行，实时捕获高分贝环境噪音与未授权的陌生人面孔。
* **🧠 LLM 威胁判定：** 拒绝死板的声控报警。拦截到的争吵录音将转交给大语言模型进行语义与意图分析，精准判定威胁等级 (HIGH/LOW)。
* **🥊 主动威慑协议：** 当检测到陌生人长时间驻留时，自动触发 TTS 语音警告，并可联动智能家居进行声光威慑。
* **☢️ Panic Lockdown (紧急熔断)：** 捕捉到特定“安全词”或危险动作时，瞬间触发系统锁屏、截取当前画面发送备用邮箱并进入静默伪装模式。
* **📋 每日特工简报 (Daily SITREP)：** 自动汇总全天安防日志，生成特工风格的安全简报。

### 🛠️ 当前状态
当前版本为 **核心架构概念验证 (PoC)**。代码已完成多模态多线程的逻辑解耦，随时可接入真实的 OpenCV 摄像头流、PyAudio 麦克风流以及各类开源 LLM 接口。欢迎提交 PR，一起把 Vanguard 部署到边缘硬件节点上！

---
*Developed by @hangkairuan-debug*
