# MotionAid - Motion Sickness Stabilization Companion 🚗🌀

**Next-gen motion sickness prevention system with adaptive visuals, biofeedback integration, and background overlay support**

[![.NET MAUI](https://img.shields.io/badge/.NET%20MAUI-8.0+-512BD4?logo=.net)](https://dotnet.microsoft.com/apps/maui)
[![Platforms](https://img.shields.io/badge/platforms-Android%20|%20iOS-lightgrey)](https://learn.microsoft.com/en-us/dotnet/maui/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## 🌟 Features

- **Smart Overlay System**  
  Persistent stabilization visuals across all apps (Android)
- **Scientific Visual Therapies**
  - Dynamic dot fields 🌌
  - Horizon stabilization lines 🚢
  - Adaptive color temperature system 🌓
- **Biometric Integration**
  - Heart rate monitoring ❤️
  - Motion pattern analysis 📈
  - Stress detection algorithms 🧠
- **Background Service**  
  Continuous protection even when app is minimized
- **Personalized Adaptation**  
  ML-powered settings optimization (using ML.NET)
- **AR Stabilization**  
  Augmented reality-based stabilization techniques 🕶️
- **Wearable Device Integration**  
  Support for various wearable devices ⌚
- **Cross-Platform Overlay Solutions**  
  Consistent overlay experience across Android and iOS 📱

## 🛠️ Technology Stack

```mermaid
graph TD
    A[.NET MAUI] --> B{Core Components}
    B --> C[SkiaSharp Visual Engine]
    B --> D[MAUI Background Services]
    B --> E[ML.NET Adaptation Model]
    A --> F[Platform Services]
    F --> G[Android Overlay System]
    F --> H[iOS Background Modes]
    A --> I[Biofeedback]
    I --> J[Heart Rate Monitoring]
    I --> K[Accelerometer Processing]
    A --> L[AR Stabilization]
    L --> M[ARCore/ARKit Integration]
    A --> N[Wearable Devices]
    N --> O[Smartwatch Integration]
```

## 📱 Installation

### Android
```bash
# Requires overlay permission
adb shell appops set <package_name> SYSTEM_ALERT_WINDOW allow
```

### iOS  
*(Limited background capabilities due to platform restrictions)*

## 🚀 Getting Started

1. Clone repo
```bash
git clone https://github.com/swapnilpopatgaikwad/MotionSicknessApp.git
```

2. Restore packages
```bash
dotnet restore
```

3. Run Android emulator
```bash
dotnet build -t:Run -f net8.0-android
```

## 🌈 Customization

Edit `Themes/VisualPresets.json`:
```json
{
  "Themes": [
    {
      "Name": "Ocean Calm",
      "BaseColor": "#89CFF0",
      "PatternType": "Wave",
      "AnimationSpeed": 0.7
    }
  ]
}
```

## 🤝 Contributing

We welcome contributions in:
- AR stabilization implementations 🕶️
- Machine learning model improvements 🤖
- Wearable device integration ⌚
- Cross-platform overlay solutions 📱

See our [contribution guidelines](CONTRIBUTING.md) for details.

## 📄 License

MIT License - See [LICENSE](LICENSE) for details

---

**Disclaimer**: This app should not replace medical advice. Always consult healthcare professionals for severe motion sickness cases.

---