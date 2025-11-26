# 🌟 EH-Hub Bot: The Ultimate Community Management Suite

## 🤖 Overview

The EH-Hub Bot is a sophisticated, multi-purpose administrative and engagement solution specifically engineered for **Discord** communities. Designed for high performance and modularity, EH-Hub streamlines essential management tasks and enhances user interaction, providing a centralized platform for operational excellence.

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

EH-Hub provides specialized slash commands for communities centered around the Emergency Hamburg environment (Roblox):

| Command | Description |
| :--- | :--- |
| `/gangs` | Check and view the statistics for the best Emergency Hamburg (EH) gangs. |
| `/emergencysetup` | Initiate a critical call button setup. Pressing the button immediately notifies in-game members when cop/med assistance or specific crim roles are urgently needed, sending vital help information. |
| `/ehgroup` | Provides a direct link and information regarding the official Emergency Hamburg Roblox group. |

---

## 🚀 Deployment & Configuration

To deploy your own secure instance of EH-Hub, follow the critical steps below. This bot requires Node.js and a Discord Bot Token.

### 1. Prerequisites

* **Node.js (LTS):** Required runtime environment.
* **Bot Token:** Must be obtained from the Discord Developer Portal.

### 2. Configuration Setup

The bot secures configuration via environment variables.

1.  **Template File:** Utilize the provided `.env.example` file as a reference.
2.  **Environment File:** Create a file named `.env` in the root directory.
3.  **Fill Values:** Populate the file with your specific credentials:

```bash
# Example content of your actual .env file
BOT_TOKEN=YOUR_DISCORD_BOT_TOKEN_HERE
BOT_PREFIX=!
OWNER_ID=YOUR_USER_ID
