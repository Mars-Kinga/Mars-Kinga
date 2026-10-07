# Hi, I'm Jinjia Zheng

Software engineering student at East China Normal University and former visiting student in computer science at UC Berkeley.

I build native iOS applications, AI-assisted tools, and software at the intersection of AI and hardware, with experience in embedded AI companion robots, industrial data acquisition, engineering diagnostics, and interactive web applications. I am particularly interested in AI-assisted tools for hardware analysis, testing, and debugging workflows.

## Featured projects

### [Swipick | Native iOS Photo Management App](https://github.com/Mars-Kinga/swipick)

**iOS Developer · Sep – Oct 2026**

A native iOS app that helps users review unwanted photos and videos and manage their photo library. Swipe-based decisions, on-device AI suggestions, and resumable sessions turn photo cleanup into a guided workflow, with confirmation before changes are applied to the system photo library.

- **Native interface:** Built in Swift and SwiftUI with stacked swipe cards, photo and video previews, and haptic feedback. PhotoKit and SwiftData support resumable reviews and recoverable Live Photo conversion.
- **On-device AI and recommendations:** Used Vision APIs for feature extraction, OCR, and aesthetic scoring to group similar photos and recommend images to keep. SHA-256 hashing identifies duplicate originals; age and content signals flag outdated temporary screenshots.
- **Caching, background processing, and power control:** Cached analysis results and limited background workloads according to Low Power Mode and thermal conditions. Suggestion scans use locally available resources without downloading iCloud originals.

<p align="center">
  <a href="https://github.com/Mars-Kinga/swipick"><img src="https://raw.githubusercontent.com/Mars-Kinga/swipick/main/docs/screenshots/home-light.jpg" width="200" alt="Swipick home in light mode"></a>
  <a href="https://github.com/Mars-Kinga/swipick"><img src="https://raw.githubusercontent.com/Mars-Kinga/swipick/main/docs/screenshots/photo-review-light.jpg" width="200" alt="Swipick photo review"></a>
  <a href="https://github.com/Mars-Kinga/swipick"><img src="https://raw.githubusercontent.com/Mars-Kinga/swipick/main/docs/screenshots/suggestions-preview-light.jpg" width="200" alt="Swipick suggestions screenshot in review preview"></a>
</p>

[Explore the project, UI and implementation →](https://github.com/Mars-Kinga/swipick)

`Swift` `SwiftUI` `PhotoKit` `SwiftData` `Vision` `CryptoKit` `Swift Testing`

### [Kitchen Assistant Robot Skill](https://github.com/Mars-Kinga/kitchen_assistant)

A Python Robot Skill runtime built around a deterministic state machine, optional Qwen text and vision services, a validated local recipe catalog, safety rules, and offline automated tests. Its capability adapters cover speech, display, motion, lighting, and facial expressions and can be replaced by a target robot SDK.

`Python` `LLM APIs` `Computer Vision` `State Machines` `Test Automation`

### [Online Museum](https://github.com/Mars-Kinga/OnlineMuseum)

A responsive Vue 3 museum experience with an interactive Silk Road map, country pages, and a mobile-friendly 3D exhibition hall containing three selectable exhibits.

`Vue 3` `JavaScript` `Vue Router` `model-viewer` `Responsive Design`

## Technical focus

- **Native iOS development:** Swift, SwiftUI, PhotoKit, SwiftData, media interactions, local persistence, and on-device image analysis
- **AI and machine learning:** LLM API integration, TensorFlow Lite Micro, PyTorch, scikit-learn
- **Embedded and hardware workflows:** ESP32-S3, FreeRTOS, peripheral integration, TCP/IP, data acquisition and diagnostics
- **Software and data:** Python, JavaScript/TypeScript, C/C++, C#/.NET, SQL, REST APIs, automated testing

Currently based in Shanghai and open to a six-month full-time software engineering internship.
