# 🤖 ChaosController

**Version:** 1.0.0  
**Platform:** Discord  
**Primary Language:** Python / discord.py

---

## 📜 Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Setup & Installation](#setup--installation)
4. [Commands](#commands)
   - [Moderation](#moderation)
   - [Utility](#utility)
   - [Fun](#fun)
   - [Configuration](#configuration)
5. [Permissions](#permissions)
6. [Troubleshooting](#troubleshooting)
7. [Support](#support)

---

## 1. Overview

**ChaosController** is a multi-purpose Discord bot designed to bring order to chaos. Whether you need strict moderation tools, engaging utility commands, or just some fun interactions, ChaosController keeps your server running smoothly. Built with stability and ease of use in mind, it offers granular permission controls so you decide exactly what the bot can do.

---

## 2. Features

- **🛡️ Advanced Moderation:** Auto-moderation, logging, and clean-up tools.
- **⚙️ Role Management:** Self-assignable roles and temporary role grants.
- **🎉 Community Engagement:** Giveaways, reaction roles, and welcome messages.
- **📊 Server Stats:** Voice channel stats and server insights.
- **🔒 Secure:** Admin-only commands are locked behind role permissions.

---

## 3. Setup & Installation

### Invite the Bot

Click the link below to invite ChaosController to your server:

[![Invite ChaosController](https://img.shields.io/badge/Invite-ChaosController-blue)](https://flourishing-gecko-376c6c.netlify.app)

### Required Permissions

When inviting, ensure the bot has the following permissions:
- `Administrator` (Recommended) *or* the specific permissions listed in the [Permissions](#permissions) section.

### First Launch

1. Type `/help` to see the available commands.
2. Use `/setup` (if applicable) to configure log channels and welcome settings.

---

## 4. Commands

All commands use the **Slash Command (`/`)** interface.

### 🛡️ Moderation

| Command | Description | Usage |
|---------|-------------|-------|
| `/ban` | Permanently bans a user. | `/ban user:@Username reason:Spamming` |
| `/kick` | Kicks a user from the server. | `/kick user:@Username reason:Rule violation` |
| `/timeout` | Temporarily mutes a user. | `/timeout user:@Username duration:10m reason:Slowmode` |
| `/clear` | Deletes a specified number of messages. | `/clear amount:50` |
| `/warn` | Issues a warning to a user. | `/warn user:@Username reason:Self-promo` |
| `/warnings` | View warnings for a user. | `/warnings user:@Username` |

### 🎲 Utility

| Command | Description | Usage |
|---------|-------------|-------|
| `/userinfo` | Displays detailed info about a user. | `/userinfo user:@Username` |
| `/serverinfo` | Displays detailed info about the server. | `/serverinfo` |
| `/avatar` | Fetches the avatar of a user. | `/avatar user:@Username` |
| `/poll` | Creates a reaction-based poll. | `/poll question:"Is this working?"` |

### 🎉 Fun

| Command | Description | Usage |
|---------|-------------|-------|
| `/8ball` | Ask the magic 8-ball a question. | `/8ball question:"Will it rain?"` |
| `/roll` | Roll a dice. | `/roll sides:20` |
| `/meme` | Fetches a random meme from Reddit. | `/meme` |

### ⚙️ Configuration (Admin Only)

| Command | Description | Usage |
|---------|-------------|-------|
| `/set-modlog` | Sets the channel for moderation logs. | `/set-modlog channel:#logs` |
| `/set-welcome` | Sets the welcome channel and message. | `/set-welcome channel:#welcome message:Hello {user}` |
| `/autorole` | Sets a role to be given to new members. | `/autorole role:@Member` |

---

## 5. Permissions

ChaosController uses Discord's built-in permission system.

- **Administrator:** Users with the Administrator permission can use all commands and configure the bot.
- **Moderator Role:** Users with a role named "Mod", "Moderator", or a role with `Manage Messages` permission can use moderation commands.
- **Everyone:** Utility and Fun commands are accessible to all users by default.

*To change which roles can use specific commands, use Discord's Server Settings > Integrations > ChaosController.*

---

## 6. Troubleshooting

**Q: The bot is online but doesn't respond to commands.**  
**A:** Ensure the bot has `Send Messages` and `Embed Links` permissions in the channel. Also, check if the bot was invited with the `applications.commands` scope.

**Q: I get an error saying "Missing Permissions".**  
**A:** The bot's role must be higher than the role it is trying to manage in the Discord role hierarchy (Server Settings > Roles). Ensure the ChaosController role is above the members you are trying to moderate.

**Q: Moderation logs aren't showing up.**  
**A:** Run `/set-modlog` to define a specific channel for logs. Ensure the bot has permission to view and send messages in that channel.

---

## 7. Support

- **Support Server:** [Click Here](https://discord.gg/3YyGk2KKp9)
- **Website:** [flourishing-gecko-376c6c.netlify.app](https://flourishing-gecko-376c6c.netlify.app)
- **Report a Bug:** Please report any bugs in our [Support Server](https://discord.gg/3YyGk2KKp9) by opening a ticket.

---

**ChaosController** — *Controlling the chaos, one command at a time.*
