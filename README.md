# 🧭 Wanderer Releases

Public releases repository and web landing page for **Wanderer** — a local-first, cloud-synced travel active workspace and trip companion mobile app built with React Native (Expo), NestJS, and Supabase.

---

## 🚀 Latest Release: v0.4

- **Version:** `v0.4`
- **Release Date:** October 2026
- **Format:** Android Standalone APK (`.apk`)
- **Direct Download:** [`releases/app-release-v0.4.apk`](./releases/app-release-v0.4.apk)

### 🌟 What's New in v0.4

1. **Custom Calendar & Date Selection**
   - Added an in-app calendar to easily select trip and activity dates with a single tap instead of manual text entry.

2. **Form Validations & Helpful Error Messages**
   - Added smart checks across trips, activities, and login forms that catch mistakes early (such as ensuring your trip end date isn't set before your start date).

3. **Haptic Touch Feedback**
   - Added subtle tactile vibrations when tapping buttons, selecting dates, and saving items for a more responsive feel.

4. **Skeleton Loading Screens**
   - Added smooth loading card previews so you see clean placeholders instead of blank screens while your trips and places load.

5. **Dark Mode Implementation**
   - Full dark theme support that is comfortable on the eyes at night and helps save battery on your phone.

---

### 📜 Previous Releases

#### v0.3 (Oct 2026)
- **Direct Download:** [`releases/app-release-v0.3.apk`](./releases/app-release-v0.3.apk)
- Native Android Manifest intent-filter scheme for `wanderer://` deep linking.
- Google & Supabase OAuth 1-tap sign-in and token capture.
- Automatic guest-to-user offline trip data migration.
- NestJS backend profile synchronization and request timeout guards.

---

## 🛠️ Core Capabilities (v0.1 + v0.2 + v0.3 + v0.4)

- 🧭 **Multi-State Trip Engine:** Organize trips across custom lifecycles: *Idea, Planning, Upcoming, Active, Completed, Archived*.
- 📍 **Places & Knowledge Base:** Save temples, cafes, stays, and scenic spots with star ratings, visited toggles, and personal tips.
- ⏱️ **Itinerary Timeline:** Schedule flight transfers, hotel check-ins, and sightseeing milestones with completion checkboxes.
- 📝 **Emergency Notes:** Store confirmation codes, packing lists, driver numbers, and Wi-Fi credentials.
- ⚡ **Offline-First Storage:** Local-first architecture using `AsyncStorage` for 100% offline access during flight mode, synced to cloud when connected.
- 🎨 **Oceanic Material 3 UI:** Premium dark theme aesthetic with fluid micro-interactions and dynamic elevation cards.

---

## 📱 How to Install on Android

1. Download [`app-release-v0.4.apk`](./releases/app-release-v0.4.apk) onto your Android device.
2. If prompted by your browser, tap **Settings** and turn on **"Allow from this source"**.
3. Tap **Install**, open **Wanderer**, and start planning your next journey!

---

## 📂 Repository Structure

```
Wanderer-Releases/
├── index.html                           # GitHub Pages landing page
├── README.md                            # Release documentation & overview
└── releases/
    ├── app-release-v0.1.apk            # Initial preview build
    ├── app-release-v0.2.apk            # v0.2 Release build
    ├── app-release-v0.3.apk            # v0.3 Release build
    └── app-release-v0.4.apk            # v0.4 Release build (Current)
```

---

© 2026 Wanderer. Open source travel companion system.
