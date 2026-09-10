# Session 05 — MyFirstHack Days 13–15

**Status:** In Progress — Day 13's lesson is read (this is the current/latest lesson in the app, not yet marked complete); Days 14–15 not yet started.
**Career-path notes:** Still deciding.

## Day 13 — Cookies

**Core idea:** Cookies are how a site remembers who you are between page loads (why you stay logged in, why an abandoned cart persists). A stolen session cookie is dangerous because the site treats whoever holds it as the logged-in user — MFA doesn't help, because MFA already passed when the original cookie was issued.
**Quiz takeaway:** If an attacker steals a session cookie (e.g. over coffee-shop Wi-Fi) and the account has MFA enabled, pasting that cookie into their own browser still logs them in — the site has no way to know it isn't the real user, since authentication already happened once.
**Takeaway line from the lesson:** Cookies are how the web remembers you between page loads — and one of the most stolen things in cybersecurity, because holding someone's cookie means the website thinks you *are* them.

## Day 14 — Wi-Fi *(title only — lesson not yet read)*

Previewed at the end of Day 13: your home router, the encryption setting most people never change, and small misconfigurations that expose traffic before HTTPS even applies.

## Day 15 — *(not yet known)*

Day 1 mentioned that Day 15 is when the program "properly polishes your [LinkedIn] profile" — beyond that, the lesson title and content aren't known yet.

## Hands-on task(s) — pending, need to actually perform these

**Day 13 task — Look at your own cookies** *(step 1 of 3; steps 2–3 not yet revealed)*
Open DevTools → Application (Chrome/Edge) or Storage (Firefox) → Cookies, on a site you're logged into.
_What to capture:_ the site inspected · how many cookies it set · the likely session-cookie name · whether Secure / HttpOnly / SameSite are set on it.

**Day 14 & 15 tasks:** Unknown until those lessons are opened.

## Maya's angle

Not yet applied directly in Day 13.

## Key takeaways so far

- Cookies are the mechanism that makes "staying logged in" possible — and a stolen one bypasses MFA entirely, because MFA is checked once at login, not on every request.
- This is the reason "Secure" and "HttpOnly" cookie flags matter: they limit how a cookie can leak (HTTPS-only, no JS access) even if something else on the page is compromised.

## Proof / files

*(Add a redacted screenshot or notes file here once the Day 13 task is actually done.)*

## LinkedIn post

**Status:** Not posted — Days 14–15 not done yet, and the Day 13 task is still pending.

```
Days 13–15 of 90 with @MyFirstHack.

[Fill in once Days 14–15 are done: what Wi-Fi security misconfigurations you learned about, and whatever Day 15 turns out to cover.]

Today's cookie lesson stuck with me most: a stolen session cookie bypasses MFA completely, because MFA only gets checked once, at login — not on every request after.

[One honest line from the actual cookie-inspection task once you've done it.]

Following MyFirstHack's 90-day path from beginner to cybersecurity foundations, tracking the whole thing here: [repo link]

#myfirsthack #cybersecurity
```

## Next up

Read Days 14–15, do the hands-on tasks for Days 13–15, then move to Session 06 (Days 16–18).
