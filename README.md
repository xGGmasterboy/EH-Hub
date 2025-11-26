# 🌟 EH-Hub Bot: The Ultimate Community Management Suite

## 🤖 Overview: Enterprise-Grade Discord Management

The **EH-Hub Bot** represents a comprehensive, high-performance solution for modern Discord communities. It is **entirely engineered using native JavaScript (Node.js)**, ensuring speed and reliability.

This bot is professionally **hosted on a Virtual Private Server (VPS) 24/7**, guaranteeing maximum uptime and continuous service delivery. EH-Hub provides sophisticated administrative, engagement, and specialized command features designed to optimize community management and interaction, making it the central pillar of your Discord server's operations.

---

## 🔗 Quick Access

| **Platform** | **Link** |
| :--- | :--- |
| **Invite Bot** | [Add EH-Hub to your Server](https://discord.com/discovery/applications/1349441086275195021) |
| **Support Server** | [Join Our Community](https:/discord.gg/fZHRF3xcJe) |

---

## ✨ Core Functionality

EH-Hub is built to be robust and highly adaptable, focusing on critical community needs:

### 🛡️ Moderation & Administration

* **Audit Logging:** Comprehensive, detailed logging of all moderator actions, message activities, and user status changes.
* **Automated Content Filtering:** Proactive mechanisms for instantly filtering spam, unauthorized links, and prohibited language.
* **Management Utilities:** Efficient tools for server information retrieval, detailed user lookups, and channel administration.

### 🎲 Engagement & Customization

* **Interactive Games:** Integrated mini-games designed to foster community engagement and boost daily activity.
* **Custom Responses:** Define fun, tailored responses triggered by specific keywords or phrases to enrich chat flow.

---

## 🚨 EH HUB BOT COMMANDS (Emergency Hamburg Integration)

EH-Hub is optimized for the Emergency Hamburg Roblox environment, featuring powerful slash commands (`/`) to bridge in-game data with Discord functionality:

| Command | Description |
| :--- | :--- |
| `/gangs` | **Gang Leaderboard:** Instantly check and display real-time statistics for top-performing EH gangs. |
| `/emergencysetup` | **Critical Callout:** Sets up a dedicated reaction button for immediate mobilization. Pressing it notifies in-game members (cop/med/crim) with essential details for urgent support. |
| `/ehgroup` | **Group Info:** Provides a direct link and informational details for the official Emergency Hamburg Roblox group. |
| `/userinfo` | **Roblox Player Lookup:** Retrieves detailed Roblox user information, including their join date for the Emergency Hamburg experience. |
| `/ehtraining` | **Training Tracker:** Command under development. Designed to manage and track member training progress within the community. |

### 🔜 Upcoming Features (Development Pipeline)

We are actively working on advanced features to further enhance management and integrity:

* **`/activity_check`:** An automated feature to monitor and report on user activity within the server.
* **Auto-Prefix Enforcement:** A critical security feature that monitors and notifies server administrators if a designated gang member removes their required gang prefix (e.g., `EH_Roblox`). This system will be deployed soon.

---

## 🚀 Deployment & Configuration: Launching Your Instance

EH-Hub is built entirely on **Node.js** (JavaScript). Follow these critical steps to initialize and secure your dedicated bot instance.

### 1. System Prerequisites

Ensure the following foundational components are installed on your deployment server:

* **Node.js (LTS):** The latest Long-Term Support version is mandatory.
* **Discord Bot Token:** A unique authorization token secured from the Discord Developer Portal.

### 2. Critical Configuration Setup

The bot relies exclusively on environment variables for security and operational parameters.

1.  **Template File:** Reference the `.env.example` template for required variables.
2.  **Secure File Creation:** Create a file named `.env` in the project's root directory.
3.  **Populate Credentials:** Fill the file with your specific, sensitive data:

```bash
# BOT IDENTIFICATION
BOT_ID=896682505279770727

# SUPPORT/INVITE LINKS (For internal embedding)
BOT_SUPPORT_INVITE=discord.gg/fZHRF3xcJe
