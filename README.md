# PlexClaw - Desktop AI Assistant

## Overview

**PlexClaw** is a cross-platform desktop AI assistant application that provides an intuitive graphical interface for the OpenClaw AI agent runtime. Built on Electron, using React 19 + TypeScript + Vite, supporting Windows, macOS, and Linux.

---

## Features

### 1. Chat
- Multi-session management with new conversation support
- Session history grouped by time (Today, Yesterday, This Week, Last Two Weeks, This Month, Older)
- Multi-agent switching
- Real-time AI conversation

### 2. Agent Management
- Create, configure, and manage multiple AI agents
- Agent-channel account binding
- Default account configuration per channel
- Agent status monitoring

### 3. Channel Management
Supported messaging platforms:
- Telegram
- Discord
- WhatsApp
- WeChat
- DingTalk
- Feishu
- WeCom
- QQ

Features:
- Account configuration and connection status
- QR code login support
- Account deletion and refresh
- Real-time connection status display

### 4. Skill Management
- Browse and search available skills
- Skill install/uninstall
- Skill enable/disable
- Local and community skills support
- Skill details view

### 5. Scheduled Tasks
- Cron expression configuration
- Preset schedules (every minute, every 5 minutes, hourly, daily, etc.)
- Task enable/pause
- Execution history view
- Channel-specific task distribution

### 6. Analytics
- Session count
- Message count
- Average response time
- Time distribution

### 7. Settings
- Gateway settings
- Theme switching (Light, Light Green, Dark, System)
- Language switching (Chinese, English, Japanese, Russian)
- Developer tools (OpenClaw Doctor diagnostics)

---

## Developer Features

### OpenClaw Gateway Integration
- Built-in OpenClaw backend service management
- Auto-start and monitor Gateway process (port 18789)
- Real-time gateway status display

### Developer Console
- Quick access to OpenClaw console via sidebar
- Real-time log viewing and debugging

### Diagnostic Tools
- Built-in `openclaw doctor` command
- One-click environment detection and repair
- JSON format diagnostic reports

---

## Interface Features

### Sidebar Navigation
- Collapsible sidebar
- Session history grouped by time
- Quick session switching
- Session deletion
- External links (Website, Recharge Center)

### Multi-language Support
- Chinese
- English
- Japanese
- Russian

### Multi-theme Support
- Light theme
- Light Green theme
- Dark theme
- System theme

### User Experience
- Responsive design
- Modern UI (Radix UI + Tailwind CSS)
- Smooth animations (Framer Motion)
- Toast notification system

## Security Features

- API keys stored securely in OS keychain
- Telemetry data stored locally only
- No automatic download/execution of third-party plugins

---

## System Requirements

| Platform | Minimum Version | Architecture |
|----------|----------------|--------------|
| Windows | Windows 10 | x64 |
| macOS | macOS 12+ | x64, arm64 (Apple Silicon) |
| Linux | Ubuntu 22.04+ | x64, arm64 |

---

## Key Advantages

1. **Cross-platform**: Single codebase supports Windows, macOS, Linux
2. **Modern tech stack**: React 19, Electron 40
3. **Multi-platform messaging**: 8 major messaging platforms
4. **Agent management**: Flexible agent configuration and channel binding
5. **Skill system**: Extensible plugin architecture
6. **Scheduled tasks**: Powerful Cron job scheduling
7. **Analytics**: Token usage and cost tracking
8. **Developer-friendly**: Complete dev tools, testing, and diagnostics
9. **Secure**: Keychain storage, local data
10. **Internationalization**: 4 languages
11. **Open source**: MIT License

---

## Project Info

- **Website**: https://plexai.ai
- **License**: MIT
- **Current Version**: 2026.4.11
