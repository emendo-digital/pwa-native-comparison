# PWA vs Native Capabilities
| Feature | Description | PWA | Native App |
|---------|-------------|-----|------------|
| Desktop Installation | You can install a PWA on macOS, Windows, and Chrome OS. You'll need to create one separate app for each operating system. | ✅ | ✅ |
| Mobile Installation | You can install a PWA on iOS and Android. You'll need to create one separate app for each operating system. | ✅ | ✅ |
| Universal Installation | PWA is the only format that allows one single app to be installed on iOS, Android, macOS, Windows, and Chrome OS. | ✅ | 🚫  |
| Push Notifications | You can send push notifications to iOS and Android users from native apps and PWAs (with [iOS 16.4 or higher](https://intercom.help/progressier/en/articles/7120026-what-are-the-requirements-for-sending-web-push-notifications-on-ios)). | ✅ | ✅ |
| Offline Capabilities | Both PWA and Native Apps can function offline, but the methods for storage and access may vary. PWAs often utilize Service Workers and the Cache API, which are typically more complex than their native app counterparts. | 🤔 | ✅ |
| Performance | Native Apps usually offer better performance since they are optimized for their specific platform. PWAs can be efficient but might face performance issues on certain devices or browsers. | 🤔 | ✅ |
| Instant Updates | PWAs can be updated on-the-fly by refreshing the app in the browser. Native Apps require updates through app stores, which might take time to be approved and then downloaded by users. | ✅ | 🤔 |
| Integration with App Stores | PWAs aren't typically found on app stores but can be added with wrappers. Native Apps are primarily distributed through app stores. | 🤔 | ✅ |
| Freedom of Monetization | PWAs are not tied to app store payment systems and can offer a wider range of payment options. Native Apps, especially on platforms like iOS, might require the use of the app store's payment system, which can take a significant cut of the revenue. | ✅ | 🚫  |
| SEO | PWAs, being web-based, can be indexed by search engines and can be optimized for search. Native Apps are not directly indexable, but their app store listings can be optimized. | ✅ | 🤔 |
| Easy Maintenance | PWAs require maintenance for web standards and browsers. Native Apps require maintenance for each platform and updates for new OS versions. | 🤔 | 🤔 |
| Affordable Development Cost | Developing a PWA can be more cost-effective since you target multiple platforms with a single codebase. Native Apps might require separate development for iOS and Android, which can be more expensive. | ✅ | 🤔 |
| Quick Development Time | PWAs can often be developed more quickly due to the single codebase. Native Apps might require more time, especially if targeting multiple platforms. | ✅ | 🤔 |
| Discoverability | PWAs benefit from regular web search and SEO practices. Native Apps rely on app store search and discovery mechanisms. | ✅ | ✅ |
| Geolocation | Both native apps and PWAs allow you to access the user's location. | ✅ | ✅ |
| Audio Recording | You can record audio from a PWA and a native app. Note that in PWAs, audio recording tends to be interrupted when the screen dims. Native apps are a better choice for recordings longer than a few minutes. | 🤔 | ✅ |
| Video Recording | You can record video from a PWA and a native app. Note that in PWAs, video recording tends to be interrupted when the screen dims. Native apps are a better choice for recordings longer than a few minutes. | 🤔 | ✅ |
| Virtual Reality | Both PWAs and native apps support VR content and can interface with VR hardware. | ✅ | ✅ |
| Connect Gamepads | With the Gamepad API, a PWA can connect to and interact with external game controllers. Native apps also have access to external gamepads. | ✅ | ✅ |
| Biometric Authentication | Native apps and PWAs both support authentication methods like fingerprint, facial recognition, etc. | ✅ | ✅ |
| Speech Synthesis | Most mobile apps can use native methods to produce spoken language from text. | ✅ | ✅ |
| Voice Recognition | This feature allows apps to effortlessly recognize and process human voice commands. | ✅ | ✅ |
| Share To Other Apps | The Web Share API allows sharing of content/data to other installed apps. | ✅ | ✅ |
| Clipboard Access | Native and Progressive Web Apps can access and modify the device clipboard. | ✅ | ✅ |
| Fullscreen Content | Both types of apps can display content in full screen, covering the entire display area. | ✅ | ✅ |
| App Badges | Both native apps and PWAs can display notification badges/counts over the app icon. | ✅ | ✅ |
| Shortcuts | Supports quick actions via app icon shortcuts. PWAs currently only support shortcuts on Android. | 🤔 | ✅ |
| Camera Controls | The APIs for controlling camera pan, tilt, and zoom are less mature on the web than in native apps. | 🤔 | ✅ |
| Bluetooth | Apps can connect to Bluetooth devices and write and read from them. iOS PWAs do not support Bluetooth yet. | 🤔 | ✅ |
| NFC | PWAs can only use NFC on Android. Native apps can make use of NFC on both iOS and Android. | 🤔 | ✅ |
| USB Devices | Desktop PWAs can connect to devices connected by USB. Native macOS and Windows apps have better access to serial peripherals. | 🤔 | ✅ |
| Human Interface Devices | The WebHID API allows PWAs (desktop only) to connect various human interface devices such as keyboards, mice, etc. | 🤔 | ✅ |
| Ambient Light | Theoretically, a PWA can use the AmbientLightSensor API to detect the surrounding light, but 🚫  mainstream browser currently supports this API. | 🚫  | ✅ |
| Vibration | A PWA can control the device's vibration motor but it's more limited than the API accessible to native apps. | 🤔 | ✅ |
| Augmented Reality | Native apps and PWAs support overlaying digital content on the real world using AR technologies. Native apps offer more options for tracking and an overall smoother experience. | 🤔 | ✅ |
| Orientation Lock | A PWA can lock the device's display orientation on Android. Both iOS and Android native apps can lock the device's orientation. | 🤔 | ✅ |
| Secondary Display | You can present content on an external display with the Presentation API (Android & Desktop Chrome only). | 🤔 | ✅ |
| Pointer Lock | Locks the pointer/mouse to the app window, useful for gaming. | 🤔 | ✅ |
| File System | Both PWAs and native apps come with a variety of methods for accessing, reading, saving, and modifying files. | ✅ | ✅ |
| Contact Picker | Android PWAs can open a selection of contacts from the device's contact list. Not currently possible on iOS. | 🤔 | ✅ |
| Background Sync | Sync data in the background, even if the app isn't running. | 🤔 | ✅ |
| Periodic Background Sync | Allows apps to synchronize data in the background at periodic intervals. | 🤔 | ✅ |
| Play Media | PWAs can play media but might face limitations in terms of codecs and DRM protected content. Native apps have broader support. | ✅ | ✅ |
| Network Information | PWAs can access a limited set of information about the network speed. Native apps have more extensive network monitoring capabilities. | 🤔 | ✅ |
| Screen Capture | PWAs have limited screen capture capabilities. Native apps often offer more advanced features. | 🤔 | ✅ |
| Shape Detection | PWAs can use the Shape Detection API for face and QR code recognition, but it may have limitations. Native apps can integrate more advanced recognition libraries. |