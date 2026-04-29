<!--
  ╭───────────────────────────────────────────────────────────╮
  │  hello, source-viewer.                                    │
  │                                                           │
  │  if you're reading this, you're our kind of weird.        │
  │  send us something you built: hi@voiddo.com               │
  │  (we read everything. we reply to most.)                  │
  │                                                           │
  │  no hidden recruiter pings. no tracking pixel.            │
  │  just a comment, because the void deserves an easter egg. │
  ╰───────────────────────────────────────────────────────────╯
-->

# vøiddo

```
        ██╗   ██╗ ██████╗ ██╗██████╗ ██████╗  ██████╗
        ██║   ██║██╔═══██╗██║██╔══██╗██╔══██╗██╔═══██╗
        ██║   ██║██║   ██║██║██║  ██║██║  ██║██║   ██║
        ╚██╗ ██╔╝██║   ██║██║██║  ██║██║  ██║██║   ██║
         ╚████╔╝ ╚██████╔╝██║██████╔╝██████╔╝╚██████╔╝
          ╚═══╝   ╚═════╝ ╚═╝╚═════╝ ╚═════╝  ╚═════╝
                  building software in the vøid
```

**building software in the vøid.**

independent software studio shipping tools, games and infrastructure. no venture capital, no artificial deadlines. just a tight loop of building, releasing and maintaining software that solves actual problems.

---

## what we ship

| product | what it is | where |
|---|---|---|
| **scrb** | ai product description generator for e-commerce | [scrb.voiddo.com](https://scrb.voiddo.com/) |
| **rankd** | ai culture judge — tier letter + verdict in 4 seconds | [rankd.voiddo.com](https://rankd.voiddo.com/) |
| **void factory** | factory-builder roguelike with a dark sense of humour | [play.voiddo.com](https://play.voiddo.com/) |
| **gridlock** | minimalist block puzzle on a 4×4 grid | [games.voiddo.com/gridlock](https://games.voiddo.com/gridlock/) |
| **fe2o3.io** | a study in patient decay — you are the formula of rust | [games.voiddo.com/fe2o3](https://games.voiddo.com/fe2o3/) |

---

## browser extensions

six chrome / firefox / edge extensions. paid + free. zero-tracking, manifest v3, vendor-agnostic copy. the AI-flavoured ones run through one studio backend with hard daily caps so we never lose money on a runaway prompt.

| extension | what it does |
|---|---|
| [interviewprep](https://github.com/voidd0/interviewprep) | open a job posting → 5 likely questions + STAR answer scaffolds + company card |
| [jobmeta](https://github.com/voidd0/jobmeta) | one-click ATS autofill across 11 platforms + AI cover letter |
| [pricepulse](https://github.com/voidd0/pricepulse) | watch competitor SaaS pricing pages and get notified when they move |
| [tabsnap](https://github.com/voidd0/tabsnap) | format your open tabs as markdown / readme / json — free forever |
| [tokcount](https://github.com/voidd0/tokcount) | count LLM tokens for any URL or selection — Claude / GPT / Gemini |
| [randumb](https://github.com/voidd0/randumb) | random numbers, dice, picks, names, lorem — context-menu based |

Listings live at [extensions.voiddo.com](https://extensions.voiddo.com/).

---

## free dev tools

twenty-one open-source command-line utilities under [`@v0idd0/*`](https://www.npmjs.com/org/v0idd0) on npm. small, single-purpose, zero-tracking. solve one infrastructure headache each, install in one line.

| tool | what it does |
|---|---|
| [cronwtf](https://github.com/voidd0/cronwtf) | decode any cron expression in plain english |
| [ctxstuff](https://github.com/voidd0/ctxstuff) | pack context for LLM prompts, token-aware |
| [depcheck](https://github.com/voidd0/depcheck) | audit npm dependencies (unused / missing / outdated) |
| [dotdig](https://github.com/voidd0/dotdig) | DNS lookup for humans, formatted output |
| [envguard](https://github.com/voidd0/envguard) | validate `.env` files against a schema |
| [fakeit](https://github.com/voidd0/fakeit) | generate seedable fake test data |
| [gitstats](https://github.com/voidd0/gitstats) | git contribution stats by author / file / hour |
| [gitwhen](https://github.com/voidd0/gitwhen) | pinpoint when a string entered or left a repo |
| [httpwut](https://github.com/voidd0/httpwut) | explain any HTTP status or header, cited to RFC |
| [jsonyo](https://github.com/voidd0/jsonyo) | format, query and validate JSON — simpler than jq |
| [licenseme](https://github.com/voidd0/licenseme) | generate a LICENSE file in seconds |
| [logparse](https://github.com/voidd0/logparse) | parse nginx / apache / syslog into structured records |
| [passgen](https://github.com/voidd0/passgen) | secure passwords + diceware passphrases — zero deps |
| [portcheck](https://github.com/voidd0/portcheck) | see what's listening on local ports |
| [promptdiff](https://github.com/voidd0/promptdiff) | diff two LLM prompts at the token level |
| [regexlab](https://github.com/voidd0/regexlab) | explain any regex pattern in plain english |
| [secscan](https://github.com/voidd0/secscan) | find accidentally-committed secrets across a repo |
| [slugmint](https://github.com/voidd0/slugmint) | i18n-aware URL slug generator |
| [sslcheck](https://github.com/voidd0/sslcheck) | inspect TLS certificates from CLI — expiry / chain / SAN |
| [timecheck](https://github.com/voidd0/timecheck) | convert timestamps between formats / timezones |
| [tzdiff](https://github.com/voidd0/tzdiff) | compare timezones side by side — meeting planner |

```bash
npm i -g @v0idd0/cronwtf @v0idd0/jsonyo @v0idd0/regexlab
```

Hub at [tools.voiddo.com](https://tools.voiddo.com/).

---

## shipped this week

*refreshed 2026-04-29 · manual update, not a feed*

- **interviewprep extension** — Tier 1 monetized launch. landing + 5 paddle pages + drop bundle live.
- **tabsnap** — extension + npm CLI dual-surface. one engine, two faces. drop ready for AMO + Edge first.
- **GH+NPM canon locked** — 7-stage pre-ship gate, footer enforcement across 27 repos via pre-commit hook, README anti-anorexia rewrites.
- **org cross-promo sync** — `from-the-studio.md` shipped to all 27 repos with quarterly refresh cadence.
- **org pinning curated** — 6 flagship repos pinned: jobmeta, interviewprep, pricepulse, tabsnap, regexlab, secscan.

---

## how we operate

- **we ship early.** code on a local machine is a liability.
- **metrics are the only truth.** server logs and conversion rates do not lie.
- **craft requires discipline.** staying small forces us to automate and write code we can read in a year.
- **everything one studio backend.** every AI-flavoured product routes through the same Gemini chokepoint with hard daily / monthly caps. one bug fix patches every product.
- **no lifetime deals.** recurring subscriptions only. windfalls are windfalls, not pillars.

---

## what we don't do

- **no venture capital.** no board, no growth-at-all-costs, no exit timeline. revenue funds the next thing we build.
- **no tracking, no analytics SDKs.** server logs and Stripe-equivalent receipts are enough. nobody at vøiddo needs to know which button you hovered.
- **no lifetime deals, no AppSumo as a strategy.** windfalls are accepted, never planned around. recurring is the only sustainable shape.
- **no cargo-cult AI.** if a feature works better as `awk` or a regex, it ships as `awk` or a regex. AI gets pulled in only when the alternative is genuinely worse.
- **no platform lock-in.** chrome extensions also build for firefox + edge from day one. CLIs run on darwin / linux / win32. data exports as json / markdown by default.
- **no over-promising.** if the README says "30 lines of code, zero deps", the package on npm is 30 lines of code with zero deps. claims and reality match or the README gets rewritten.

---

[website](https://voiddo.com/) · [tools](https://tools.voiddo.com/) · [extensions](https://extensions.voiddo.com/) · [games](https://games.voiddo.com/) · [contact](https://voiddo.com/contact/) · [npm](https://www.npmjs.com/org/v0idd0)

---

Built by [vøiddo](https://voiddo.com/) — a small studio shipping AI-flavoured products, free dev tools, Chrome extensions and weird browser games.
