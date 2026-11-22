# 🎓 QuizPro v2.0.0 — Modern Cross-Platform Examination Simulator

QuizPro v2.0.0 is an enterprise-grade, cross-platform MCQ examination simulator and adaptive learning platform engineered for standardized certification preparation (e.g., AWS, CIA, CISA, PMP, SQL, and medical licensure).

---

## 📦 Multi-Platform Release Downloads

| Platform | File | Type | Target Architecture / Compatibility |
| :--- | :--- | :--- | :--- |
| 🤖 **Android** | [`QuizPro-Android.apk`](https://github.com/Coderaryanyadav/QuizPro/releases/latest/download/QuizPro-Android.apk) | Standalone APK | ARM64-v8a, ARMv7, x86_64 (Android 7.0+) |
| 🍎 **iOS** | [`QuizPro-iOS.ipa`](https://github.com/Coderaryanyadav/QuizPro/releases/latest/download/QuizPro-iOS.ipa) | Packaged IPA | Sideloadable via AltStore / Sideloadly / TestFlight |
| 🍏 **macOS** | [`QuizPro-macOS.dmg`](https://github.com/Coderaryanyadav/QuizPro/releases/latest/download/QuizPro-macOS.dmg) | Disk Image (DMG) | Universal macOS (Apple Silicon M1/M2/M3 & Intel) |
| 🍏 **macOS** | [`QuizPro-macOS.zip`](https://github.com/Coderaryanyadav/QuizPro/releases/latest/download/QuizPro-macOS.zip) | Application Bundle | Portable `QuizPro.app` |
| 🪟 **Windows** | [`QuizPro-Windows-x64.zip`](https://github.com/Coderaryanyadav/QuizPro/releases/latest/download/QuizPro-Windows-x64.zip) | Portable Archive | Windows 10 & 11 (64-bit with runtime DLLs) |
| 🌐 **Web PWA** | [**Live Web App**](https://web-sandy-five-55.vercel.app) | Progressive Web App | Chrome, Edge, Safari, Firefox |

---

## 🚀 Key Highlights & New Features

### 1. Crash-Resilient Atomic Storage Architecture
- Zero data corruption guarantee via atomic staging files (`.tmp`) and atomic file-system rename operations.
- Dedicated recovery mechanism with checksum validations ensuring user state is never truncated during abrupt shutdowns.

### 2. Multi-Student Profile Isolation
- Fully isolated student workspaces with customizable avatar emojis and color accents.
- Attempt histories, bookmarks, and topic mastery scores are strictly isolated between students.

### 3. Hierarchical Taxonomy Engine
- 4-tier taxonomy model: **Course → Subject → Chapter → Topic**.
- Real-time question counting and matrix filtering for targeted study drills.

### 4. Supabase Cloud Sync & Web PWA
- Two-way PostgreSQL cloud synchronization with offline-first local fallbacks.
- Progressive Web App deployed on Vercel with responsive desktop and mobile viewport adaptations.

### 5. Multi-Platform Native Compilation
- Automated CI/CD pipeline building native releases across Android, iOS, macOS, and Windows.

---

## 🔐 Cryptographic Checksums (SHA-256)

```text
b2d4a02cea1015ea923e4eaec9dc2b228bcf95559990d91723ea2523ca206e34  QuizPro-Android.apk
4bebf82b42bbdbba3df0ab7184c347c93aaadbc8941c8f87dae559922894ded9  QuizPro-iOS-App.zip
77547e8d649702df8a04e0f614b6202ec4aaf9c1a71108837871ad67d164bd36  QuizPro-iOS.ipa
140e18d839a1b373157b215fb970006d72ef323123209fa3c84ec233891bcf12  QuizPro-macOS.dmg
33b89f8632fc79d7b44ba17aef39b0d07468464bd23b108db895910382a3f0da  QuizPro-macOS.zip
```
