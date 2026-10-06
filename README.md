# 🧭 Wanderer Releases

Public releases repository and web landing page for **Wanderer** — a local-first, cloud-synced travel active workspace and trip companion mobile app built with React Native (Expo), NestJS, and Supabase.

---

## 🚀 Latest Release: v0.3

- **Version:** `v0.3`
- **Release Date:** October 2026
- **Format:** Android Standalone APK (`.apk`)
- **Direct Download:** [`releases/app-release-v0.3.apk`](./releases/app-release-v0.3.apk)

### 🌟 What's New in v0.3

1. **Native Android Manifest Scheme Filter**
   - Configured `wanderer://` BROWSABLE scheme intent filter in native `AndroidManifest.xml` enabling Android OS to route OAuth redirects directly to the standalone APK.

2. **Linking Deep-Link Event Listener**
   - Implemented React Native `Linking` listener to capture authentication tokens directly from Chrome intent redirections.

3. **Google & Supabase OAuth Integration**
   - Seamless 1-tap Google Sign-In with native deep-linking support (`wanderer://`).

4. **Automatic Guest-to-User Data Migration**
   - Offline trips, places, milestone timeline events, and notes created in Guest Mode automatically transfer to your signed-in cloud account upon login.

5. **NestJS Backend Auth Sync Engine**
   - Secure token exchange and profile synchronization endpoint (`POST /api/v1/auth/sync`) with JWT authentication guards.

6. **Non-Blocking UI Loader & 6s Request Timeout**
   - Immediate loading state transitions and AbortController timeout protection on all API calls preventing infinite loading screens.

7. **Auth Token Protection**
   - Updated storage clearing logic to preserve Supabase authentication session tokens.

---

## 🛠️ Core Capabilities (v0.1 + v0.2 + v0.3)

- 🧭 **Multi-State Trip Engine:** Organize trips across custom lifecycles: *Idea, Planning, Upcoming, Active, Completed, Archived*.
- 📍 **Places & Knowledge Base:** Save temples, cafes, stays, and scenic spots with star ratings, visited toggles, and personal tips.
- ⏱️ **Itinerary Timeline:** Schedule flight transfers, hotel check-ins, and sightseeing milestones with completion checkboxes.
- 📝 **Emergency Notes:** Store confirmation codes, packing lists, driver numbers, and Wi-Fi credentials.
- ⚡ **Offline-First Storage:** Local-first architecture using `AsyncStorage` for 100% offline access during flight mode, synced to cloud when connected.
- 🎨 **Oceanic Material 3 UI:** Premium dark theme aesthetic with fluid micro-interactions and dynamic elevation cards.

---

## 📱 How to Install on Android

1. Download [`app-release-v0.3.apk`](./releases/app-release-v0.3.apk) onto your Android device.
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
    └── app-release-v0.3.apk            # v0.3 Release build (Current)
```

---

© 2026 Wanderer. Open source travel companion system.
