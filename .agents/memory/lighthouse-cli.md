---
name: Lighthouse CLI verification
description: Local Lighthouse runs in this environment need the optional error-reporting prompt disabled.
---

Use Lighthouse with its anonymous error-reporting prompt disabled when running non-interactively; otherwise the CLI can fail before auditing the page even when the site is healthy.

**Why:** The CLI prompt cannot be answered reliably from a non-interactive shell and can surface a readline error unrelated to the site.

**How to apply:** Add the no-error-reporting flag to local Lighthouse commands before interpreting a failed run as a product or build failure.