# Live Voice Agents with Google ADK

A collection of voice agents built using Google's Agent Development Kit (ADK), created as part of the DeepLearning.AI course.

## 🚀 Project Overview

This repository contains my implementations of various voice agents using Google's ADK, progressing from basic to advanced features.

## 📁 Project Structure

## 🛠️ Agents

| Agent | Description | Status |
|-------|-------------|---------|
| [Basic Voice Agent](/agents/basic-voice-agent) | First voice agent with web interface | ✅ Complete |
| [Tool-Enabled Agent](/agents/tool-agent) | Agent with external tools | 🔄 In Progress |
| [Research Agent](/agents/research-agent) | Agent with research capabilities | ❌ Planned |

## 📚 Lessons

- [Lesson 1: Introduction](/docs/lessons/lesson-01-introduction.md)
- [Lesson 2: Running Voice Agents](/docs/lessons/lesson-02-running-agents.md)
- [Lesson 3: Build Your First Agent](/docs/lessons/lesson-03-first-agent.md)

## 🚀 Quick Start

```bash
# Create agent folder
!adk create --type=code app_01 --model gemini-2.0-flash-live-001 --api_key $GEMINI_API_KEY

# Launch web interface
cd L1
adk web --host 0.0.0.0 --port 8001
