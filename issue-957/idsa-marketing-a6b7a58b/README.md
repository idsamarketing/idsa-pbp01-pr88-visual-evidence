# Issue #957 — idsa_marketing render evidence

Source repo: `idsamarketing/idsa_marketing`
Source ref: `origin/main`
Source SHA: `a6b7a58b476ce29e05d68149061c0e4c809a3782`
Audit mode: read-only snapshot; no marketing source files modified.

Representative pages captured with PHP 8.2.12 + Puppeteer/Chrome using exact CSS viewports 375×812 and 1280×900:
- `index.php`
- `services.php`
- `ac-repair-service-support.php`
- `learn2earn-plc-training.php`
- `login.php`

Viewport verification for all 5 pages: `innerWidth == documentElement.scrollWidth == body.scrollWidth` at both 375 and 1280. No horizontal-overflow defect was reproduced with the exact Puppeteer viewport. The earlier direct `chrome --window-size=375` capture was rejected as a Windows minimum-window capture artifact and is superseded by these files.
