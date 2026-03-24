# zs-pkg-flutter-ui

> **Part of:** [ZarishSphere Platform](https://github.com/zarishsphere) | **Layer:** Mobile
> **Framework:** Flutter 3.41.2 | **Language:** Dart 3.11 | **Offline:** PowerSync 1.x
> **Status:** 🔴 Bootstrap

Shared Flutter component library — design system for mobile

## Repository Structure

```
zs-pkg-flutter-ui/
├── lib/
│   ├── main.dart        # App entry point
│   ├── features/        # Feature modules (FHIR-domain organised)
│   ├── shared/          # Shared widgets, utilities
│   ├── fhir/            # FHIR client, models (offline-first)
│   └── l10n/            # Localization (EN, BN, MY, UR, HI, TH)
├── android/             # Android configuration
├── ios/                 # iOS configuration
├── test/                # Unit and widget tests
├── .github/
│   └── workflows/       # CI/CD pipelines
├── Makefile
├── pubspec.yaml
└── README.md
```

## Technology Stack

| Component | Version |
|-----------|---------|
| Flutter | **3.41.2** |
| Dart | **3.11** |
| Riverpod (state) | **2.6+** |
| PowerSync (offline sync) | **1.x** |
| drift (SQLite ORM) | **2.x** |

---

*Part of the [ZarishSphere Platform](https://zarishsphere.com) — Free · Open Source · FHIR R5 · Offline-First*
