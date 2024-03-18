# PWA vs Native Capabilities
- **✅**: This indicates that the feature is fully supported by the platform. For PWAs, this means that the technology or capability can be utilized effectively across supported browsers. For Native Apps, it means the feature can be utilized across various devices and operating systems without significant limitations.

- **🚫**: This indicates that the feature is not supported by the platform. For PWAs, a "No" might mean that current web technologies do not allow for this capability, or it is restricted due to security, privacy, or technical reasons. For Native Apps, it typically means that the feature cannot be implemented due to OS-level restrictions or lack of API support.

- **🤔**: This signifies conditional or partial support for the feature. For PWAs, this could mean that the feature is supported only in certain browsers, under specific conditions, or might require user permissions. It may also indicate that the feature is experimental or under development. For Native Apps, "Maybe" could mean that the feature is available on some but not all operating systems, or its implementation can vary significantly between devices.

| Feature | Description | PWA | Native App |
|---------|-------------|-----|------------|
| Desktop Installation | You can install a PWA on macOS, Windows, and Chrome OS. You'll need to create one separate app for each operating system. | ✅ | ✅ |
| Mobile Installation | You can install a PWA on iOS and Android. On native You'll need to create one separate app for each operating system. | ✅ | ✅ |
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
| Shape Detection | PWAs can use the Shape Detection API for face and QR code recognition, but it may have limitations. Native apps can integrate more advanced recognition libraries. | 🤔 | ✅ |
| Device Memory | PWAs can access some device memory information for optimizing performance. Native apps can get more detailed memory stats and control. | 🤔 | ✅ |
| One-Time Passwords | PWAs can integrate with OTPs for authentication, but might not have as seamless an integration as native apps. | 🤔 | ✅ |
| Virtual Keyboard | PWAs can trigger the virtual keyboard, but don't have as much control over its behavior compared to native apps. | 🤔 | ✅ |
| Pointer Lock | PWAs can lock the pointer (useful for games), but face some browser restrictions. Native apps can often provide a more consistent experience. | 🤔 | ✅ |
| Detect Device Orientation | Allows detecting the orientation of the device, whether landscape or portrait. In a PWA, you can use the DeviceOrientation event. | ✅ | ✅ |
| Detect Device Motion | Allows the app to detect device motion such as shakes or tilts. In a PWA, you can use the DeviceMotion event. | ✅ | ✅ |
| Block Screenshots & Recording | PWAs don't have native support for blocking screenshots and video recording. Sensitive native apps (e.g., banking) can prevent screen capture or recording for security reasons. | 🚫 | ✅ |
| Direct Printing | PWAs face limitations with direct printing without user interaction. Native apps can often directly interface with printers. | 🚫 | ✅ |
| Home Screen Widgets | PWAs cannot create home screen widgets on most platforms. Native apps can provide widgets for quick access to app functionalities. | 🚫 | ✅ |
| Direct Graphics Hardware Access | This feature refers to the capability of an app to directly utilize the GPU of a device. Bypassing any intermediate layers (e.g., the browser) often provides a smoother user experience. | 🚫 | ✅ |
