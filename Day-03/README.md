# Session 03 — MyFirstHack Days 7–9

**Status:** In Progress — lessons done, hands-on tasks pending
**Career-path notes:** Still deciding.

## Day 7 — DNS *(Week 1 checkpoint)*

**Core idea:** Revisits DNS properly as the glue connecting everything from Week 1 (the 7-stop journey, IP addresses, public/private IPs, NAT). Closes out Week 1 of the program.
**Quiz takeaway:** DNS's primary purpose is translating human-readable domain names into IP addresses.
**Also this day:** A Week-1 reflection exercise — pick 3 of 6 prompts (where you started / what almost stopped you / a moment that clicked / a new capability / who else needs this / what surprised you) and write 2–3 sentences each, for a "one week in" LinkedIn post. The program itself flags that a bigger reflection post is expected again at Day 90 (i.e., in our compressed plan, around Day 30) — this lines up with the wrap-up recap already in our plan.

## Day 8 — Passwords

**Core idea:** The classic "complexity + change every 90 days" password rule was invented in 2003 and publicly retracted by its own author (Bill Burr, NIST) in 2017 for making security worse, not better. Length beats complexity; uniqueness and 2FA matter more than either.
**Quiz takeaway:** A 2013 breach database still being used to break into accounts in 2026 is called credential stuffing.

## Day 9 — Phishing

**Core idea:** Phishing is behind roughly 70–90% of successful cyberattacks. It's a psychology exploit (urgency, authority, curiosity), not a technology problem — which is why even security professionals get caught.
**Case study:** The 2016 Podesta/DNC email hack — a fake "Google security alert" phishing email, forwarded internally with a typo that accidentally called it "legitimate," led to a real password being typed into a fake login page.
**Quiz takeaway:** Password strength is irrelevant against phishing — you type the real password into the attacker's fake page yourself; they don't need to crack anything.

## Hands-on task(s) — pending, need to actually perform these

**Day 7 task — Run a real DNS query** *(step 1 of 2)*
Use `nslookup` (Terminal/Command Prompt) on google.com, reddit.com, cnn.com, then explicitly against `8.8.8.8` and `1.1.1.1`.
_What to capture:_ first IP for google.com · how many IPs returned for cnn.com · whether 8.8.8.8 and 1.1.1.1 agreed · one surprise.
_Plus:_ the Week-1 reflection post (3 of the 6 prompts above).

**Day 8 task — Install a password manager, add one account** *(step 1 of 2)*
Set up Bitwarden (or keep your existing manager), create a passphrase master password, add and autofill one real account.
_What to capture:_ which manager · the first account added · passphrase vs. shorter complex string · installed on browser + phone, or just one.

**Day 9 task — Hunt for a real phishing email** *(step 1 of 2)*
Check inbox and spam for a real phishing attempt; examine sender domain vs. hovered link URL vs. display text.
_What to capture:_ impersonated company · actual sender domain · actual destination URL · which psychological lever (urgency/authority/curiosity) · one convincing detail. (If truly none found, an empty spam folder screenshot is a valid — and honestly rarer — result.)

## Maya's angle

Not yet applied directly in these three days.

## Key takeaways (across all 3 days)

- Week 1 complete: DNS, IPs, and the network fundamentals all connect into one map of "every stop is an attack surface."
- Long-standing password advice (frequent complexity-forced changes) was wrong and has been retracted by its own author — length + uniqueness + 2FA is what actually matters.
- Phishing succeeds through psychology, not weak passwords or naive users — even experts get caught, so the defense is structural habits (hover before clicking, never authenticate from an email link, verify through a second channel) rather than "being smart enough to spot it."

## Proof / files

*(Add a redacted screenshot or notes file here once the Day 7–9 tasks are actually done.)*

## LinkedIn post

**Status:** Not posted — waiting until the hands-on tasks above are actually completed.

```
Days 7–9 of 90 with @MyFirstHack. Week 1 wrapped.

Ran real nslookup queries to see DNS resolve domains to IPs, learned that the password advice we've all followed for 20 years was retracted by the person who wrote it, and went hunting for a real phishing email in my own inbox.

[One honest line: what nslookup showed you, what surprised you about the password history, or what you found hunting for phishing.]

Following MyFirstHack's 90-day path from beginner to cybersecurity foundations, tracking the whole thing here: [repo link]

#myfirsthack #cybersecurity
```

## Next up

Do the actual hands-on tasks for Days 7–9, then move to Session 04 (Days 10–12: data, the web, HTTPS).
