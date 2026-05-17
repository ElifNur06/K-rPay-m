# 📊 KarPayim (Arpaca MVP)

[![Flutter](https://img.shields.io/badge/Frontend-Flutter%20%2F%20Dart-02569B?style=for-the-badge&logo=flutter)](https://flutter.dev)
[![FastAPI](https://img.shields.io/badge/Backend-FastAPI%20%2F%20Python-009688?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com)
[![Gemini](https://img.shields.io/badge/AI-Google%20Gemini%201.5%20Flash-8E44AD?style=for-the-badge&logo=googlegemini)](https://deepmind.google/technologies/gemini/)

An advanced, production-ready SaaS cross-platform (Web & Mobile) tool designed for e-commerce sellers, dropshippers, and retail arbitrage experts. It automates real-time product scraping, complex logistic/customs financial computations, AI-driven background processing, and global marketplaces SEO generation.

---

## 🎯 Key Features (14 Operational Modules)

1. **Dynamic Financial Sliders:** Instant recalculation of Logistics, Customs, and Target Profit Margin without page reloads (Reactive UX).
2. **Global Arbitrage Mode:** Real-time exchange rate sync (TRY, USD, EUR) via background API connectivity.
3. **Robust Cache Kalkanı:** Secure persistence of search history using `SharedPreferences` with structural payload verification to explicitly prevent data type parsing crashes (`_JsonMap` validation).
4. **Cross-Platform Screenshot Report:** Single-tap UI capturing and binary report sharing (`karpayim_rapor.png`) fully compatible with both Web and Mobile platforms.
5. **AI Global SEO Assistant:** Embedded **Google Gemini 1.5 Flash** engine optimizing English titles, high-converting bullet points, and high-traffic tags validated via structural Regex pattern filtering.
6. **AI Background Remover:** ML-powered server-side background removal utilizing `rembg` on CPU architectures to stream transparent alpha-channel studio product images (PNG).
7. **Marketplace Commission Simulator:** Multi-platform commission modeling for major global systems including Amazon (%15), Etsy (%6.5), and Shopier (%5).
8. **Gamified Sales Goals:** Interactive and animated commercial milestone progression tracker ("Haftalık 10.000 TL Kâr Hedefi") implemented locally.
9. **Volumetric Weight (Desi) Engine:** Volumetric shipping calculation model utilizing a flexible physical pricing formula (+8 TL/desi over base price).
10. **Retail Arbitrage Hardware Scanner:** Low-level physical hardware camera access integrating `mobile_scanner` to turn real-world barcodes directly into programmatic search queries.
11. **Bulk Processing Module:** Asynchronous concurrent pipeline processing multiple target store listings simultaneously on the FastAPI backend layer.
12. **Background Price Drop Alerts:** Predictive internal cron jobs driven by `APScheduler` tracking price variance every 12 hours.
13. **Product Trend Scoring Algorithm:** Dynamic telemetry and user-interaction analysis rendering an evaluation index (e.g., 85/100) decorated with a high-fidelity visual engine.
14. **Interactive Financial Charting:** High-end contextual data rendering utilizing `fl_chart` giving clear visual segments of structural operational overhead versus net margin.

---

## Görseller
<img width="995" height="560" alt="image" src="https://github.com/user-attachments/assets/05be0d92-4017-4592-819f-25fdb21e3f69" />
<img width="994" height="562" alt="image" src="https://github.com/user-attachments/assets/1a8cb6c9-6ab7-4501-b1bb-fbcc056632f2" />
<img width="989" height="560" alt="image" src="https://github.com/user-attachments/assets/936aee89-b521-4ac0-918c-2a0d9ec5748c" />
<img width="989" height="559" alt="image" src="https://github.com/user-attachments/assets/d7df91f4-7792-4d96-b075-25f589ddd76b" />
<img width="992" height="558" alt="image" src="https://github.com/user-attachments/assets/d1f61c64-6778-4513-ab4b-246027ba72bb" />
<img width="989" height="561" alt="image" src="https://github.com/user-attachments/assets/688739e9-409e-4231-89da-72e15a0f07ce" />
<img width="990" height="558" alt="image" src="https://github.com/user-attachments/assets/0b4bb00c-64cf-411e-bc3a-fdd3a9c2f29a" />
<img width="991" height="553" alt="image" src="https://github.com/user-attachments/assets/5ade9558-f714-4b55-915d-b4c77d75f541" />
<img width="992" height="558" alt="image" src="https://github.com/user-attachments/assets/cf627800-8010-4025-b5fd-336bc7c57d98" />
<img width="992" height="559" alt="image" src="https://github.com/user-attachments/assets/b97d5df2-99f4-4013-ae8e-b0d38dbde7fd" />
<img width="994" height="559" alt="image" src="https://github.com/user-attachments/assets/2834909f-c1b5-4f0c-873c-c37de26bcf31" />
<img width="992" height="556" alt="image" src="https://github.com/user-attachments/assets/32cb1358-3581-45b5-b006-49c425c6d45f" />


## 🏗️ System Architecture & Folder Layout

The frontend layer implements rigorous **Clean Architecture** patterns separating functional visual structures from structural service data streams to bypass tight coupling spaghetti antipatterns.

```text
lib/
├── core/
│   └── app_colors.dart         # Monolithic UI design system token store
├── services/
│   ├── api_service.dart        # Asynchronous HTTP network payload engine
│   └── storage_service.dart    # High-level SharedPreferences abstractions & state guard
└── screens/
    ├── home_screen.dart        # Unified dashboard, gamification UI & state persistence
    ├── result_screen.dart      # PieChart data rendering, AI triggers & operational panel
    └── scanner_screen.dart     # Hardware camera abstraction wrapper for mobile scanning
