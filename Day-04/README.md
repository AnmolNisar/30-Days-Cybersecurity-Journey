# Session 04 — MyFirstHack Days 10–12

**Status:** In Progress — lessons done, hands-on tasks pending
**Career-path notes:** Still deciding.

## Day 10 — Data

**Core idea:** Every day of learning so far (computers, internet, IPs, DNS, passwords, phishing) is infrastructure that exists to protect one thing: data. Every major breach (Equifax, Yahoo, Marriott, Colonial Pipeline, LastPass, Change Healthcare) is ultimately about data. Three categories every defender uses: **PII** (personally identifiable info), **Credentials**, and **Proprietary data**.
**Quiz takeaway:** The three categories used to classify valuable data are PII, Credentials, and Proprietary data.

## Day 11 — The Web

**Core idea:** The web is a layer on top of the internet — pages, browsers, and the HTML/scripts that render them. Most pages load code from dozens of third-party domains (trackers, analytics, ad networks) that run with the same trust as the page itself.
**Quiz takeaway:** External JavaScript is worth investigating because code loaded from a domain you don't recognize runs with the same trust as the page — a malicious third-party script can read forms, cookies, and rewrite the page.
**Takeaway line from the lesson:** The internet moves data; the web is what you see when that data is shaped into pages a browser can render.

## Day 12 — HTTPS

**Core idea:** The padlock icon only proves the connection is encrypted — it does not prove the site is safe or that you're talking to who you think you are. That's a much narrower guarantee than most people assume.
**Quiz takeaway:** A certificate issued 2 days ago by Let's Encrypt, valid for 90 days, is normal — short certificate lifetimes are now the industry standard, not a red flag.
**Takeaway line from the lesson:** HTTPS protects the channel, not the destination.

## Hands-on task(s) — pending, need to actually perform these

**Day 10 task — Map your personal data landscape** *(step 1 of 2)*
List ~15–20 services across PII (8–10), Credentials (3–5), and Proprietary (4–6) categories.
_What to capture:_ total service count · which category had the most · one genuinely surprising/forgotten service · one service you've never reviewed privacy settings on.
⚠️ Per the root README's privacy note — keep the literal list of real, named accounts private; the count and category breakdown is the shareable part.

**Day 11 task — See behind a real page** *(step 1 of 3; steps 2–3 not yet revealed)*
View Page Source (Ctrl+U / Cmd+Option+U) on a frequently used site; count `<script>` tags; search for "tracker" or known analytics names.
_What to capture:_ the site · rough script-tag count · any third-party trackers spotted.

**Day 12 task — Inspect a real certificate** *(step 1 of 3; steps 2–3 not yet revealed)*
Click the padlock on a trusted site (e.g. bbc.co.uk) → view certificate details.
_What to capture:_ site inspected · issuing CA (e.g. DigiCert, Let's Encrypt, Sectigo) · certificate validity window in days · one unexpected detail.

## Maya's angle

Not yet applied directly in these three days.

## Key takeaways (across all 3 days)

- Everything defended so far boils down to protecting three kinds of data: PII, Credentials, Proprietary — this is "thinking like a security professional" rather than just "learning security."
- A single web page is rarely just "the site" — it's dozens of third-party scripts running with full page trust.
- The HTTPS padlock is a narrower promise than most people think: encrypted channel, not verified safety or identity.

## Proof / files

*(Add a redacted screenshot or notes file here once the Day 10–12 tasks are actually done.)*

## LinkedIn post

**Status:** Not posted — waiting until the hands-on tasks above are actually completed.

```
Days 10–12 of 90 with @MyFirstHack.

Learned the three categories every security pro uses to think about data (PII, credentials, proprietary), looked at the raw HTML and third-party scripts behind a page I use daily, and opened up a real HTTPS certificate for the first time.

[One honest line: what your data-landscape map revealed, a tracker you didn't expect, or something about the certificate that surprised you.]

Following MyFirstHack's 90-day path from beginner to cybersecurity foundations, tracking the whole thing here: [repo link]

#myfirsthack #cybersecurity
```

## Next up

Do the actual hands-on tasks for Days 10–12, then move to Session 05 (Days 13–15: cookies, Wi-Fi, and one more day still to be read).
