# 🌍 EcoSystem - Dynamic Ecological System for Minecraft

[![Java](https://img.shields.io/badge/Java-17+-orange.svg)](https://java.com)
[![Spigot](https://img.shields.io/badge/Spigot-1.16.5+-yellow.svg)](https://spigotmc.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/day2s/EcoSystem.svg)](https://github.com/day2s/EcoSystem/stargazers)

> Transform your Minecraft world into a living, breathing ecosystem that evolves over time!

## ✨ Features

### 🌱 **Natural Plant Spread**
- Grass, flowers, and saplings naturally spread across the world
- Configurable spread rates and plant types
- Visual particle effects during growth

### 🧬 **Intelligent Mob Evolution**
- Mobs adapt and become stronger over time
- Unique evolutions for each mob type:
  - **Zombies** → Armored zombies with speed boost
  - **Skeletons** → Elite archers with powered bows
  - **Creepers** → Charged creepers with larger explosions
  - **Spiders** → Jumping spiders with increased agility
- Evolution based on natural selection principles

### ⚙️ **Highly Configurable**
- Enable/disable individual systems
- Adjust evolution chances and intervals
- Customize plant spread behavior
- Localization support

### 🚀 **Performance Optimized**
- Asynchronous processing for heavy operations
- Smart chunk loading management
- Minimal impact on server performance
- Built-in metrics with bStats

## 📦 Installation

1. **Download** the latest `EcoSystem.jar` from [Releases](https://github.com/day2s/EcoSystem/releases)
2. **Place** the JAR file in your server's `plugins/` folder
3. **Restart** your server
4. **Configure** `plugins/EcoSystem/config.yml` to your liking
5. **Enjoy** a living world!

## 🎮 Usage

### Basic Commands
| Command | Description | Permission |
|---------|-------------|------------|
| `/eco` | Show help menu | `ecosystem.use` |
| `/eco status` | Check system status | `ecosystem.use` |
| `/eco reload` | Reload configuration | `ecosystem.admin` |
| `/eco forcecheck` | Force immediate check | `ecosystem.admin` |

### Permissions
```yaml
ecosystem.use:       # Basic command access
  default: op
ecosystem.admin:     # Administrative functions
  default: op
