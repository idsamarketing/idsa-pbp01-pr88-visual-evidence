# Issue #957 — idsa_marketing render evidence

Source repo: `idsamarketing/idsa_marketing`
Source ref: `origin/main`
Source SHA: `a6b7a58b476ce29e05d68149061c0e4c809a3782`
Audit mode: read-only snapshot; no marketing source files modified.

Representative pages captured from the exact source snapshot using local PHP 8.2.12 + headless Chrome at 375×812 and 1280×900:
- `index.php`
- `services.php`
- `ac-repair-service-support.php`
- `learn2earn-plc-training.php`
- `login.php`

Observation: 1280px captures render cleanly. The 375px captures show right-edge clipping/overflow in the shared Fraud / Recruitment Alert area and page content on the sampled pages; this is recorded as a responsive visual finding, not fixed in this audit phase.
