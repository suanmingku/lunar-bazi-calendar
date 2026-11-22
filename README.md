# @suanmingku/lunar-bazi-calendar

Deterministic TypeScript reference library for **Jingfang Najia 64-hexagram assembly (京房納甲六爻裝卦)**, **True Solar Time (真太陽時)**, **24 Solar Terms (二十四節氣)**, and **Chinese sexagenary calendar (干支曆法)** calculations, maintained by **[Suanmingku (算命庫)](https://suanmingku.com/)**.

> **Status**: Official repository reserved. Initial TypeScript implementation and test fixtures are scheduled for upcoming release.

## Planned Modules

1. **Jingfang Najia Hexagram Engine (Priority v0.1)**
   - Deterministic 64-hexagram lookup, Najia Heavenly Stems & Earthly Branches assignment, Palace classification (八宮), Shi/Ying positions (世應), Six Relatives (六親), Six Spirits (六神), and moving-line transformation.
   - Live interactive benchmark: [I Ching hexagram casting](https://suanmingku.com/en/liuyao).
2. **True Solar Time & Solar-Term Boundaries**
   - Longitude offset + Equation of Time solar correction.
   - Minute-accurate 24 Solar Terms (every 15° solar longitude) for sexagenary Year/Month pillar transitions.
   - Configurable early/late Zi-hour (`23:00–23:59`) day-rollover rules.
   - Live interactive benchmark: [BaZi chart calculator](https://suanmingku.com/en).
3. **Reference Test Suite**
   - Reproducible boundary cases (Li Chun transitions, leap months, Taipei/Hong Kong/Tokyo/UTC solar offsets, and `23:30` Zi-hour edge cases).

## Licensing & Scope Boundary

- **Code & Test Fixtures**: Released under the [MIT License](./LICENSE).
- **Not Included in Open Source**: The `Suanmingku` / `算命庫` brand name, logo, website copy, interpretation reports, and curated classical Chinese text editions on [Suanmingku](https://suanmingku.com/) are **not** included in this repository and remain all rights reserved.

## Contact

- Official Website: [https://suanmingku.com](https://suanmingku.com/)
- Contact: `support@suanmingku.com`
