# Issue #957 — idsa_marketing render evidence

Source repo: `idsamarketing/idsa_marketing`
Source ref: `origin/main`
Source SHA: `a6b7a58b476ce29e05d68149061c0e4c809a3782`
Audit mode: read-only snapshot; no marketing source files modified.

Captured with PHP 8.2.12 + Puppeteer/Chrome using exact CSS viewports 375×812 and 1280×900.

Representative pages: `index.php`, `services.php`, `ac-repair-service-support.php`, `learn2earn-plc-training.php`, `login.php`.

Inventory-warning page: `digital-services-india.php` (repo validator reports 4 phantom inventory references, but `PHANTOM_LINKS_RENDERED=0`).

Viewport verification for all captured pages: `innerWidth == documentElement.scrollWidth == body.scrollWidth` at both 375 and 1280. No horizontal-overflow defect reproduced. Earlier direct `chrome --window-size=375` files were rejected as a Windows minimum-window capture artifact and replaced by these exact Puppeteer captures.
