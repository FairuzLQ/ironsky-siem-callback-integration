# IronSKY × SIEM — Realtime Integration via SDK Callback

Beginner-friendly documentation site for forwarding IronSKY (SecIron) mobile-RASP
events to your SIEM **in realtime** by capturing the SDK's `RISKEVENT` callback in
the app and relaying it through a collector.

**Live site:** https://fairuzlq.github.io/ironsky-siem-callback-integration/

Companion to the batch method: https://fairuzlq.github.io/ironsky-siem-log-forwarding/

Covers: architecture (app callback → collector → SIEM), callback vs S3 trade-offs,
the `RISKEVENT`/`DEVINFO` callbacks, the payload schema (kept identical to the S3
method so the same SIEM rules apply), sending from the app, a minimal collector,
feeding into the SIEM, per-framework code (Kotlin, Java, Flutter, React Native,
iOS Swift), verification, security, troubleshooting, and FAQ.

Single self-contained `index.html` (no build step). All endpoints, tokens, APP_IDs,
and udids shown are placeholders.
