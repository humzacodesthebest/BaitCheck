# BaitCheck

BaitCheck is a privacy-first, browser-only phishing education and triage tool. It identifies suspicious patterns in messages and links, explains the evidence, and recommends safer next steps. It does **not** prove that a message or website is safe.

## Run locally

Open `index.html` in a browser. No build step, account, backend, or pasted-content upload is required.

## Privacy and limitations

- Analysis happens locally in the browser.
- No third-party fonts, analytics, reputation APIs, or automatic URL requests are used.
- A link is never visited or expanded by BaitCheck.
- Results are heuristic signals, not a verdict or a substitute for the company’s official support channel.
- Browser-local recent checks can be cleared at any time.

## Safety model

BaitCheck separates high-confidence structural indicators (for example, an `@` in a URL or a domain that impersonates a known brand) from weaker context indicators (for example, urgency). HTTPS only encrypts a connection; it does not make a site legitimate.
