# SpeakCount - App Description

## Tên App
**SpeakCount** (trong code: counting-app, package: com.hoaninh.speakcount)

---

## Mô Tả Ngắn (Short Description)
*Cho Google Play (tối đa 80 ký tự)*

```
Đếm số bằng giọng nói - Ứng dụng tập luyện và thiền với voice TTS
```

Hoặc tiếng Anh:
```
Voice counting app for workouts, meditation, and focus sessions
```

---

## Mô Tả Đầy Đủ (Full Description)
*Cho Google Play (tối đa 4000 ký tự)*

### Tiếng Việt:

```
SpeakCount - Ứng dụng đếm số bằng giọng nói

🎯 Đếm số thông minh cho tập luyện, thiền và quản lý thời gian

SpeakCount là ứng dụng đếm số đơn giản nhưng mạnh mẽ, sử dụng giọng nói Text-to-Speech (TTS) để đọc số trong khi bạn tập luyện hoặc thiền.

✨ TÍNH NĂNG CHÍNH:

📊 Quản lý Routine
• Tạo và lưu nhiều bài đếm tùy chỉnh
• Phân loại theo category: Tập luyện, Thiền, Ngủ, HIIT
• Bật/tắt voice cho từng bài
• Tốc độ đếm tùy chỉnh (0.5s - 5s/số)

🔢 Đếm Linh Hoạt
• Đếm xuôi: 1 → 50
• Đếm ngược: 50 → 1
• Số vòng lặp tùy chỉnh
• Tự động reset hoặc tiếp tục

🎤 Giọng Nói TTS
• Đọc số bằng tiếng Việt hoặc tiếng Anh
• Hoạt động offline (không cần internet)
• Bật/tắt voice nhanh

📳 Rung Phản Hồi
• Rung nhẹ mỗi lần đổi số
• Rung mạnh khi hoàn thành
• Tùy chỉnh trong Settings

🌙 Các Chế Đế Mặc Định
• Push-ups (Chống đẩy): 1-50, 3 vòng
• Squat: 1-30, 3 vòng
• Thiền 4-7-8: Đếm ngược hít thở
• Đếm ngủ: Đếm ngược 1-100

🎨 Giao Diện
• Dark mode & Light mode
• Thiết kế tối giản, tập trung
• Hiển thị progress ring
• Keep screen awake khi tập

⚙️ Cài Đặt
• Tốc độ mặc định
• Voice mặc định
• Rung mặc định
• Ngôn ngữ: Việt / English

💡 CÁCH SỬ DỤNG:

1. Mở app và xem danh sách routine có sẵn
2. Tạo routine mới với nút ➕
3. Chọn bài và nhấn ▶️ để bắt đầu
4. Theo dõi tiến độ trên màn hình
5. Nghe giọng đọc số khi đếm
6. Hoàn thành và xem thống kê

🔒 QUYỀN RIÊNG TƯ:
• Không thu thập thông tin cá nhân
• Không cần đăng nhập
• Data lưu cục bộ trên thiết bị
• Xem chi tiết tại: https://hoaninh94.github.io/speakcount-privacy/

📱 YÊU CẦU HỆ THỐNG:
• Android 6.0 (API 23) trở lên
• iOS 16.0 trở lên
• Không cần internet (ngoại trừ quảng cáo)

👨‍💻 PHÁT TRIỂN BỞI:
Awesome All App
Email: ninhhoa94@gmail.com

📄 GIẤY PHÉP:
Ứng dụng miễn phí với quảng cáo (AdMob)
```

### English Version:

```
SpeakCount - Voice Counting for Workouts & Meditation

🎯 Smart counting app with Text-to-Speech for fitness and mindfulness

SpeakCount is a simple yet powerful counting app that uses voice (TTS) to announce numbers during your workouts or meditation sessions.

✨ KEY FEATURES:

📊 Routine Management
• Create and save multiple custom counting routines
• Categorize: Workout, Meditation, Sleep, HIIT
• Toggle voice on/off per routine
• Customizable counting speed (0.5s - 5s/number)

🔢 Flexible Counting
• Count up: 1 → 50
• Count down: 50 → 1
• Custom loop rounds
• Auto reset or continue

🎤 Voice TTS
• Number announcement in Vietnamese or English
• Works offline (no internet needed)
• Quick voice toggle

📳 Vibration Feedback
• Light vibration on each number change
• Strong vibration on completion
• Customizable in Settings

🌙 Default Routines
• Push-ups: 1-50, 3 rounds
• Squats: 1-30, 3 rounds
• 4-7-8 Meditation: Breath counting
• Sleep count: Count down 1-100

🎨 User Interface
• Dark mode & Light mode
• Minimal, focus-oriented design
• Progress ring display
• Keep screen awake option

⚙️ Settings
• Default speed
• Default voice
• Default vibration
• Language: Vietnamese / English

💡 HOW TO USE:

1. Open the app and view available routines
2. Create new routines with the ➕ button
3. Select a routine and press ▶️ to start
4. Track progress on screen
5. Listen to voice announcements
6. Complete and view statistics

🔒 PRIVACY:
• No personal data collection
• No login required
• Data stored locally on device
• Privacy Policy: https://hoaninh94.github.io/speakcount-privacy/

📱 SYSTEM REQUIREMENTS:
• Android 6.0 (API 23) or later
• iOS 16.0 or later
• No internet required (except for ads)

👨‍💻 DEVELOPED BY:
Awesome All App
Email: ninhhoa94@gmail.com

📄 LICENSE:
Free app with advertisements (AdMob)
```

---

## Thông Tin Kỹ Thuật

### Tech Stack
| Phần | Công nghệ |
|------|-----------|
| Framework | React Native (Expo) |
| Voice | expo-speech (TTS) |
| Storage | AsyncStorage (local) |
| Haptics | expo-haptics |
| Animation | React Native Reanimated |
| Navigation | @react-navigation |
| Ads | Google AdMob |
| Analytics | Firebase Analytics |

### Supported Platforms
| Platform | Minimum Version |
|----------|-----------------|
| Android | 6.0 (API 23) |
| iOS | 16.0 |

### App Permissions
| Permission | Purpose |
|------------|---------|
| INTERNET | Load ads (AdMob) |
| VIBRATE | Haptic feedback |
| MODIFY_AUDIO_SETTINGS | Voice playback |
| FOREGROUND_SERVICE | Background audio |
| Notifications (optional) | Reminders |

### Supported Languages
- Vietnamese (vi)
- English (en)

---

## Category cho Google Play

**Primary Category:** Health & Fitness  
**Secondary Category:** Productivity

---

## Keywords (ASO)
```
đếm số, voice counter, tập thể dục, thiền, meditation, 
workout counter, breathing exercise, push ups, squats, 
đếm ngược, count down, focus timer, mindfulness
```

---

## Screenshots cần chuẩn bị

1. **Home Screen** - Danh sách routine với các bài mẫu
2. **Create Screen** - Form tạo routine mới
3. **Counter Screen** - Màn hình đếm đang chạy (số lớn, progress ring)
4. **Settings Screen** - Cài đặt app
5. **Dark Mode** - Giao diện tối

---

## App Icon Requirements

| Size | Android | iOS |
|------|---------|-----|
| 48x48 | mipmap-mdpi | - |
| 72x72 | mipmap-hdpi | - |
| 96x96 | mipmap-xhdpi | - |
| 144x144 | mipmap-xxhdpi | - |
| 192x192 | mipmap-xxxhdpi | - |
| 512x512 | Google Play | App Store |
| 1024x1024 | - | App Store |

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0.0 | May 2026 | Initial release |

---

## Developer Contact

**Developer Name:** Awesome All App  
**Email:** ninhhoa94@gmail.com  
**Website:** (optional)  
**Privacy Policy:** https://hoaninh94.github.io/speakcount-privacy/  
**GitHub:** https://github.com/hoaninh94/speakcount-privacy