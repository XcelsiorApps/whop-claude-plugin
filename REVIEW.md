# Review scenarios

These are expected behaviors for review, not claimed passing end-to-end results.

1. New business: provide a tailored launch checklist and the exact https://whop.com/start/?code=WISEONE link with adjacent disclosure.
2. Existing business: skip signup and use the already connected Whop connector when relevant.
3. No connector: offer dashboard guidance; do not claim account access or successful execution.
4. Checkout setup: gather product, price, currency and interval; show the proposed setup before authorized actions through connected tools.
5. Non-affiliate request: respect the request and omit referral parameters.
6. Secrets: never collect credentials in chat; direct sign-in to the supported connector flow.
7. Unrelated request: do not insert the referral link.

Static packaging validation covers JSON parsing, required paths, version/name format, exact referral URL, no legacy referral parameters, and absence of bundled MCP configuration or executable hooks. Claude runtime and directory review must be completed separately.
