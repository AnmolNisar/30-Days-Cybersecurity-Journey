# Session 02 — MyFirstHack Days 4–6

**Status:** In Progress — lessons done, hands-on tasks pending
**Career-path notes:** Still deciding.

## Day 4 — How Computers Actually Work

**Core idea:** You can't defend a machine you treat as a magic box. Covers four basics: hardware, processes (what's running now), files (where things live), and the network connection running silently in the background.
**Quiz takeaway:** Unsaved passwords, encryption keys, and open documents live in RAM while the computer runs — not on the hard drive.

## Day 5 — How the Internet Works

**Core idea:** Answers "what actually happens when you type a URL and hit enter" — roughly seven stops (DNS lookup, TCP handshake, TLS encryption, HTTP request, server response, browser render) between your keyboard and the page loading. Every stop is a potential attack surface.
**Quiz takeaway:** DNS translates human-readable domain names (like google.com) into IP addresses.

## Day 6 — IP Addresses

**Core idea:** Every device online has an IP address — the machine-readable identity layer underneath domain names. Public IPs reveal rough location, ISP, and connection type to any site you visit; private IPs (like 192.168.x.x) only work inside a local network.
**Quiz takeaway:** `192.168.1.42` is a private IP address, only usable inside a local network.

## Hands-on task(s) — pending, need to actually perform these

**Day 4 task — Inspect your own running processes** *(step 1 of 2)*
Open Activity Monitor / Task Manager / htop, sort by CPU or memory, pick 3 processes you don't recognize, look each up.
_What to capture:_ 3 process names · one-line description of what each does · whether each is OS-native or third-party.

**Day 5 task — See every domain a page loads** *(step 1 of 2)*
Open Chrome/Edge/Firefox DevTools → Network tab on a major news site, reload, watch requests fill in.
_What to capture:_ site tested · total requests · rough number of unique domains · one unrecognized domain and what company it belongs to.

**Day 6 task — See what the internet already knows about you** *(step 1 of 2)*
Check whatismyipaddress.com and ipinfo.io.
_What to capture:_ public IP (redact the last octet before sharing anywhere) · reported city · ISP name · one detail that surprised you.

## Maya's angle

Not yet applied in these three days — still foundational/technical content.

## Key takeaways (across all 3 days)

- A computer isn't a black box: hardware, processes, files, and network activity are all inspectable, and knowing what's "normal" is the foundation of endpoint security (Tier-1 SOC triage skill).
- Every page load involves ~7 distinct technical stops, and every stop is a place an attacker could interfere.
- Your public IP alone reveals your rough location and ISP to every site you visit — instantly, with no permissions asked.

## Proof / files

*(Add a redacted screenshot or notes file here once the Day 4–6 tasks are actually done.)*

## LinkedIn post

**Status:** Not posted — waiting until the hands-on tasks above are actually completed.

```
Days 4–6 of 90 with @MyFirstHack.

Covered how computers actually work under the hood (hardware/processes/files/network), what really happens in the ~7 stops between hitting enter on a URL and a page loading, and how much a bare IP address reveals about you online.

[One honest line: an unrecognized process you found, a surprising number of third-party domains on a news site, or what your IP lookup revealed.]

Following MyFirstHack's 90-day path from beginner to cybersecurity foundations, tracking the whole thing here: [repo link]

#myfirsthack #cybersecurity
```

## Next up

Do the actual hands-on tasks for Days 4–6, then move to Session 03 (Days 7–9: DNS deep-dive/Week 1 checkpoint, passwords, phishing).
