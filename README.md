<div align="center">

# Ahmad Alnahal
### Flutter Mobile App Developer

[![Portfolio](https://img.shields.io/badge/Portfolio-ahmad--alnahal.github.io-14B8A6?style=flat-square&logo=googlechrome&logoColor=white)](https://ahmad-alnahal.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ahmadalnahal-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmadalnahal/)
[![Behance](https://img.shields.io/badge/Behance-ahmadalnahal-1769FF?style=flat-square&logo=behance&logoColor=white)](https://www.behance.net/ahmadalnahal)
[![Email](https://img.shields.io/badge/Email-alnahal2003@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:alnahal2003@gmail.com)
[![Status](https://img.shields.io/badge/Status-Open%20to%20Remote%20Work-34D399?style=flat-square)](#)

</div>

---

Final-year IT student at the **Islamic University of Gaza**, specializing in Mobile Computing & Smart Device Applications.  
2+ years building Flutter applications — from architecture decisions to pixel-perfect UI.

I work at the intersection of engineering and design: I design in **Figma** and engineer in **Flutter**, with a strict focus on Clean Architecture, BLoC, and production-grade code standards.

---

## Tech Stack

**Core**  
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

**Architecture & State**  
![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-333?style=flat-square)
![BLoC](https://img.shields.io/badge/BLoC-333?style=flat-square)
![GetIt](https://img.shields.io/badge/GetIt-333?style=flat-square)
![Provider](https://img.shields.io/badge/Provider-333?style=flat-square)
![GetX](https://img.shields.io/badge/GetX-333?style=flat-square)

**Backend & Networking**  
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Dio](https://img.shields.io/badge/Dio%20%2F%20REST%20APIs-333?style=flat-square)

**Design**  
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Material 3](https://img.shields.io/badge/Material%20Design%203-757575?style=flat-square&logo=material-design&logoColor=white)

**Other**  
![Go Router](https://img.shields.io/badge/Go%20Router-333?style=flat-square)
![SharedPreferences](https://img.shields.io/badge/SharedPreferences-333?style=flat-square)
![RTL/LTR](https://img.shields.io/badge/RTL%20%2F%20LTR-333?style=flat-square)
![Localization](https://img.shields.io/badge/Localization-333?style=flat-square)

---

## Featured Projects

### 🔄 Rotate Rules — Per-App Rotation Engine `System-Level Tool`
> Android utility app that controls screen rotation behavior per app using a foreground service and rule engine. Detects the current foreground app, matches saved rotation rules, applies rotation automatically, and supports fallback and restore of previous system rotation behavior.  
> `Flutter` `Kotlin` `Foreground Service` `UsageStatsManager` `MethodChannel` `BLoC` `Clean Architecture`  
> [Repository](https://github.com/Ahmad-alnahal/rotate_rules_app)

---

### 🗂️ MARJIY — Legal Library Curation Tool `Windows Desktop App`
> Flutter Desktop app built for my father to organize a legal document library: safely importing PDFs (source files always stay read-only), detecting duplicates via SHA-256, adding legal metadata, full-text search through SQLite FTS5, and preparing reviewed export batches for a future public legal-library website. Delivered as a Windows installer and in daily use for about a month with zero reported bugs.  
> `Flutter Desktop` `BLoC` `Clean Architecture` `Drift / SQLite` `FTS5` `Win32 FFI` `GetIt`  
> [Repository](https://github.com/Ahmad-alnahal/legal_library_manager)

---

### ✅ Taskora — Freelancer Time & Earnings Tracker `Full-Stack`
> Productivity app for freelancers and students juggling several small projects at once, tying logged hours per task directly to an hourly rate so real per-project earnings are always visible. Backend rebuilt with Laravel from a written API contract after an earlier third-party API proved unreliable. Real offline-first support (local SQLite via Drift with a sync queue), and every issued auth token is activated independently through its own email OTP step rather than a single account-wide verification.  
> `Flutter` `BLoC` `Clean Architecture` `Drift / SQLite` `Dio` `Laravel 12` `Sanctum` `Pest`  
> [Flutter repo](https://github.com/Ahmad-alnahal/Taskora) · [Laravel repo](https://github.com/Ahmad-alnahal/Taskora-Laravel)

---

### 🚗 Naqlah — P2P Car Rental Platform `Private Project`
> Took over an existing Flutter car-rental app built by a previous team and rebuilt it into a new product for a different market: full rebrand (name, identity, colors, domain, backend), a systematic Clean Architecture cleanup, a centralized guest-access security gate across 16+ screens, and dozens of documented data-integrity and logic bugs fixed with real before/after verification on a physical device. Delivered stable and production-tested; the client engagement later paused for licensing reasons unrelated to the technical work.  
> Source code is private.  
> `Flutter` `BLoC/Cubit` `Clean Architecture` `GetIt` `GoRouter` `Dio` `Hive` `Firebase` `Google Maps`

---

### 🍽️ QR Tap — Restaurant QR Ordering Platform `Private Product`
> Private restaurant platform built as two Flutter apps: a customer app and an admin dashboard.  
> Customer app: QR table sessions, menu browsing, cart/order flow, reservations with QR check-in, support requests, feedback, notifications, and offline restaurant/menu continuity.  
> Admin app: order management, reservations, support tickets, feedback, FAQs, notifications, and configurable settings.  
> Source code is private. Screenshots and walkthrough available on request.  
> `Flutter` `Dart` `BLoC` `Clean Architecture` `REST API` `QR Scanner` `Offline UX` `Admin Dashboard`

---

### ⚖️ Qwaeid (قواعد) — Legal Platform `Solo Dev`
> Full Flutter legal resource platform for browsing Palestinian legislation, judicial studies, and official publications. Includes PDF viewer/download, SSO login via a custom MethodChannel plugin, and Lottie animations. Designed and engineered solo from architecture to delivery.  
> `Flutter` `GetX` `Dio` `Syncfusion PDF` `SSO / MethodChannel` `Lottie`  
> [Repository](https://github.com/Ahmad-alnahal/Qwaeid) · [Figma design](https://www.figma.com/design/I76PNG31s808lsA36LOl4K/qwaeid-app?node-id=0-1)

---

### 🍳 Cook App — Food Delivery Platform `Delivered · Client Project`
> Production-grade food delivery application built under strict architectural standards for Zagency. Clean Architecture + BLoC + GetIt DI + Firebase Auth, Firestore, and multi-language RTL/LTR support. Strict layer separation from presentation to domain to data with use cases and repositories.  
> `Flutter` `BLoC` `Clean Architecture` `GetIt` `Firebase` `Go Router` `Localization`  
> [Repository](https://github.com/Ahmad-alnahal/cook_app)

---

### 🎨 NROMA — Marketing Website Redesign `UI/UX Design`
> Full UI/UX redesign of a marketing website with an outdated, inconsistent interface. Designed a modern visual identity, layout system, and responsive structure end-to-end in Figma. Implementation is pending a separate decision on the client side.  
> `Figma` `UI/UX Design` `Visual Identity` `Responsive Web`  
> [Figma design](https://www.figma.com/design/boisi41NchA71K1oAzKxU7/NROMA?node-id=0-1)

---

## Certifications

| Course | Platform | Hours | Year |
|--------|----------|-------|------|
| The Complete Flutter & Dart: Basics to Advanced | Udemy — Abdallah Yassein | 55h | 2026 |
| Flutter Clean Architecture [Flutter 3] | Udemy — Usama Elgendy | 8h | 2023 |

---

## Education

🎓 **B.Sc. Information Technology** — Mobile Computing & Smart Device Applications  
Islamic University of Gaza (IUG) · Expected 2026  
Graduation Project: **UUP-IUG** — Unified University Platform (UI/UX Designer)

---

<div align="center">

📍 Gaza, Palestine · 🌐 Remote Ready · 📧 alnahal2003@gmail.com

</div>
