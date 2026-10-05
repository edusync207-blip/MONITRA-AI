# 🚦 Monitra AI

### AI-Based Real-Time Monitoring of Training Centres for Attendance & Infrastructure Compliance

> **Monitor. Verify. Comply.**\
> A smart training-centre monitoring prototype designed to demonstrate
> how CCTV feeds, AI analytics, anonymous tracking, attendance checks,
> infrastructure analysis, alerts, scoring and reporting can work
> together in one dashboard.

------------------------------------------------------------------------

## 🌟 Project Overview

**Monitra AI** is a web-based prototype for real-time monitoring of
training centres.

The prototype demonstrates a monitoring workflow that moves through:

**CCTV → AI Analytics → Detect & Track → Anonymous Count → Attendance
Check → Infrastructure Analysis → Alert Engine → Score → Dashboard → SMU
Report**

The interface is designed as an interactive demonstration rather than a
production surveillance system.

------------------------------------------------------------------------

## 🎯 Key Features

### 📹 CCTV Monitoring

-   Interactive simulated CCTV classroom feed
-   Camera status and monitoring stages
-   Demo scenarios for different centre conditions

### 🤖 AI Analytics

-   AI-driven monitoring workflow
-   Detection and tracking simulation
-   Live analytics panel

### 👤 Privacy-Preserving Tracking

-   Anonymous temporary IDs such as `P01–P24`
-   Face identification is disabled in the prototype
-   Anonymous tracking is used for demonstration

### 🏫 Attendance & Infrastructure

-   Attendance verification workflow
-   Infrastructure checks for:
    -   💡 Lighting
    -   🧯 Fire extinguisher visibility
    -   🪑 Seating
    -   🖥️ Equipment
    -   👨‍🏫 Trainer presence

### 🚨 Alert Engine

The prototype demonstrates different monitoring situations, including: -
Ghost attendance - Healthy session - Camera tampering - Infrastructure
faults

### 📊 Live Analytics & Scoring

-   Real-time dashboard-style analytics
-   Status indicators
-   Infrastructure scoring
-   Alert/event display

### 🔥 Heatmap & Simulation

-   Interactive heatmap mode
-   Start/Pause simulation
-   Next-stage controls
-   Reset controls
-   Scenario selection

### 📱 Responsive Interface

The UI adapts for desktop and smaller screens.

------------------------------------------------------------------------

## 🧠 Monitoring Workflow

``` text
┌──────────┐
│   CCTV   │
└────┬─────┘
     ↓
┌──────────────┐
│ AI Analytics │
└────┬─────────┘
     ↓
┌──────────────┐
│ Detect/Track │
└────┬─────────┘
     ↓
┌──────────────────┐
│ Anonymous Count  │
└────┬─────────────┘
     ↓
┌──────────────────┐
│ Attendance Check │
└────┬─────────────┘
     ↓
┌──────────────────────┐
│ Infrastructure Check │
└────┬─────────────────┘
     ↓
┌──────────────┐
│ Alert Engine │
└────┬─────────┘
     ↓
┌────────────┐
│ Score      │
└────┬───────┘
     ↓
┌────────────┐
│ Dashboard  │
└────┬───────┘
     ↓
┌────────────┐
│ SMU Report │
└────────────┘
```

------------------------------------------------------------------------

## 🧪 Demo Scenarios

  -----------------------------------------------------------------------
  Scenario                            Purpose
  ----------------------------------- -----------------------------------
  👻 Ghost attendance                 Demonstrates attendance anomaly
                                      detection

  ✅ Healthy session                  Demonstrates normal centre
                                      operation

  ⚠️ Camera tamper                    Demonstrates camera integrity
                                      monitoring

  🔧 Infrastructure fault             Demonstrates infrastructure
                                      compliance issues
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 🔐 Privacy by Design

Monitra AI's prototype explicitly demonstrates:

-   **Face identification OFF**
-   **Anonymous tracking ON**
-   Temporary tracking IDs instead of personal identity
-   Low-bandwidth / edge-local processing concept

> This repository contains a prototype demonstration. It should not be
> treated as a production-ready surveillance or compliance system
> without appropriate testing, security, privacy controls, legal review
> and validated AI models.

------------------------------------------------------------------------

## 🛠️ Technology

-   **HTML5**
-   **CSS3**
-   **JavaScript**
-   HTML Canvas for simulated visual monitoring
-   Responsive web UI
-   Self-contained prototype

The current prototype is intentionally packaged as a single `index.html`
file, making it easy to deploy using GitHub Pages.

------------------------------------------------------------------------

## 🚀 Run the Project

### Option 1 --- GitHub Pages

1.  Open the repository **Settings**
2.  Select **Pages**
3.  Choose **Deploy from a branch**
4.  Select branch **main**
5.  Select folder **/(root)**
6.  Click **Save**

Your project can then be accessed through your GitHub Pages URL.

### Option 2 --- Local

Download or clone the repository and open:

``` text
index.html
```

in a modern web browser.

------------------------------------------------------------------------

## 🎮 How to Use the Prototype

1.  Open the dashboard.
2.  Select a monitoring scenario.
3.  Click **Start Simulation**.
4.  Observe the monitoring stages.
5.  Use **Next Stage** to move through the workflow.
6.  Use **Heatmap** to visualize activity.
7.  Use **Reset** to restart the demonstration.
8.  Review the live analytics, alerts and infrastructure indicators.

------------------------------------------------------------------------

## 📁 Project Structure

``` text
MONITRA-AI/
│
├── index.html
└── README.md
```

------------------------------------------------------------------------

## 💡 Why Monitra AI?

Traditional manual inspection can make continuous monitoring difficult.

Monitra AI demonstrates a unified approach where:

**Observe → Analyze → Verify → Alert → Score → Report**

can be represented through a single monitoring interface.

------------------------------------------------------------------------

## 🏆 Hackathon / Prototype

**Project:** Monitra AI\
**Domain:** AI • Computer Vision • Training & Skill Development •
Monitoring • Compliance\
**Prototype Type:** Interactive Web Demonstration

------------------------------------------------------------------------

## 👨‍💻 Repository

**MONITRA-AI**

Built as an interactive prototype for demonstrating AI-assisted
real-time training-centre monitoring.

------------------------------------------------------------------------

### ⭐ If you find the concept useful, consider starring the repository!

**Monitra AI --- Monitor. Verify. Comply.**
