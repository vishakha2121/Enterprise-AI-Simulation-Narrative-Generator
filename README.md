# 🚀 Enterprise AI Simulation Narrative Generator

[![GitHub stars](https://img.shields.io/github/stars/vishakha2121/Enterprise-AI-Simulation-Narrative-Generator)](https://github.com/vishakha2121/Enterprise-AI-Simulation-Narrative-Generator/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/vishakha2121/Enterprise-AI-Simulation-Narrative-Generator)](https://github.com/vishakha2121/Enterprise-AI-Simulation-Narrative-Generator/network)
[![GitHub issues](https://img.shields.io/github/issues/vishakha2121/Enterprise-AI-Simulation-Narrative-Generator)](https://github.com/vishakha2121/Enterprise-AI-Simulation-Narrative-Generator/issues)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

> **An AI-powered platform for generating business scenarios, simulations, training cases, disaster recovery plans, and interactive decision-making exercises.**

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [Architecture](#-architecture)
- [Getting Started](#-getting-started)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [Running the Application](#-running-the-application)
- [API Documentation](#-api-documentation)
- [Project Structure](#-project-structure)
- [Database Schema](#-database-schema)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎯 Overview

The **Enterprise AI Simulation Narrative Generator** is a cutting-edge, AI-powered platform designed to revolutionize business training, scenario planning, and strategic decision-making. This innovative solution combines the power of **Large Language Models (LLMs)** with sophisticated simulation engines and knowledge graphs to create immersive, interactive business narratives.

### 🎯 Core Mission

To bridge the gap between theoretical business knowledge and practical decision-making by providing organizations with a dynamic, AI-driven simulation environment where leaders, managers, and teams can:

- ✅ Practice critical decision-making in risk-free environments
- ✅ Explore complex business scenarios with multiple outcomes
- ✅ Develop crisis management and leadership skills
- ✅ Build organizational resilience through preparedness training
- ✅ Accelerate learning through immersive narrative experiences

---

## 🌟 Key Features

### 🤖 AI-Powered Narrative Generation
- **Dynamic Story Creation**: Uses Google's Gemini AI to generate rich, context-aware business narratives
- **Real-time Adaptation**: Stories evolve based on user decisions and actions
- **Multi-genre Support**: Finance, Healthcare, Technology, Retail, Manufacturing, and more
- **Personalized Scenarios**: Tailored to industry, role, and learning objectives

### 🎮 Interactive Simulation Engine
- **Branching Decision Trees**: Every choice creates unique narrative paths
- **Real-time Feedback**: Immediate consequences of decisions
- **State Management**: Tracks all variables, resources, and metrics
- **Multi-player Support**: Collaborative decision-making exercises

### 🧠 Knowledge Graph Integration
- **Entity Relationship Mapping**: Visual representation of business ecosystems
- **Dynamic Updates**: Graph evolves with simulation progress
- **Pattern Recognition**: Identify trends and connections
- **Impact Analysis**: See how decisions affect different business areas

### 📚 Comprehensive Training Modules
- **Case Study Library**: 50+ pre-built business scenarios
- **Role-based Learning**: CEO, CFO, CTO, HR, Marketing, Operations
- **Skill Development**: Leadership, Crisis Management, Strategic Thinking
- **Certification Tracks**: Progressive learning paths

### 🚨 Disaster Recovery Planning
- **Scenario Templates**: Pandemic, Cyber Attack, Natural Disaster, Market Crash
- **Step-by-Step Protocols**: Detailed recovery procedures
- **Risk Assessment Matrix**: Identify vulnerabilities
- **Drill Scheduling**: Automated practice exercises

### 📊 Advanced Analytics Dashboard
- **Performance Metrics**: Decision quality scores
- **Learning Analytics**: Progress tracking
- **Comparative Analysis**: Benchmark against peers
- **Predictive Insights**: AI-powered predictions

---

## 🛠️ Technology Stack

### Backend
| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Framework** | FastAPI | High-performance API development |
| **Database** | PostgreSQL | Structured data storage |
| **AI Integration** | Google Gemini API | Natural language generation |
| **Knowledge Graph** | Neo4j / NetworkX | Relationship management |
| **Task Queue** | Celery + Redis | Async processing |
| **Caching** | Redis | Performance optimization |
| **Authentication** | JWT | Secure user access |
| **Documentation** | Swagger/OpenAPI | API documentation |

### Frontend
| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Framework** | React 18 | Component-based UI |
| **State Management** | Redux Toolkit | Application state |
| **UI Library** | Material-UI | Professional components |
| **Styling** | Tailwind CSS | Custom styling |
| **Charts** | Recharts | Data visualization |
| **Drag-and-Drop** | React DnD | Interactive builder |
| **API Client** | Axios | HTTP requests |
| **Real-time** | Socket.io | Live updates |

### DevOps & Tools
- **Version Control**: Git + GitHub
- **Containerization**: Docker + Docker Compose
- **CI/CD**: GitHub Actions
- **Testing**: Pytest + Jest
- **Documentation**: Markdown + Swagger

---

## 🏗️ Architecture

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Python** 3.9 or higher
- **Node.js** 16 or higher
- **PostgreSQL** 14 or higher
- **Git** (for version control)
- **Docker** (optional, for containerized setup)

### System Requirements
- **CPU**: 2+ cores (Works on CPU-based laptops)
- **RAM**: 8GB minimum, 16GB recommended
- **Storage**: 20GB free space
- **OS**: Windows 10+, macOS 11+, Linux (Ubuntu 20.04+)

### External Services Required
- Google Gemini API Key ([Get it here](https://makersuite.google.com/app/apikey))
- PostgreSQL database (local or cloud)
- Redis (optional, for caching)

---

## 📥 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/vishakha2121/Enterprise-AI-Simulation-Narrative-Generator.git
cd Enterprise-AI-Simulation-Narrative-Generator

# Navigate to backend directory
cd backend

# Create and activate virtual environment
python -m venv venv

# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Navigate to frontend directory
cd frontend

# Install dependencies
npm install