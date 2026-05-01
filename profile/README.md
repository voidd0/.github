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

> **a small, bootstrapped studio shipping AI products, browser extensions, free dev tools and weird browser games.** no venture capital. no dark patterns. no lifetime deals dressed up as strategy. one studio backend, one cost ceiling, dozens of surfaces. if it works, you'll know. if it doesn't, the README will say so.

---

## three subscription products

these are the things we'd actually like to pay rent with.

| product | one-line truth | live at |
|---|---|---|
| **scrb** | ai product description generator for amazon / etsy / shopify sellers — 25 languages, no chatgpt copy-pasting, no per-listing tax | [scrb.voiddo.com](https://scrb.voiddo.com/) |
| **rankd** | "the internet's meanest culture judge" — feed it a movie / game / book / album, get a tier letter and a one-liner that ruins your weekend | [rankd.voiddo.com](https://rankd.voiddo.com/) |
| **tells** | forensic ai for reading what people don't say — read a message, read a person, read a profile · waitlist open | [voiddo.com/tells](https://voiddo.com/tells/) |

---

## four subportals

we organise everything by surface, not by hype-cycle. pick whichever side of the studio you came for.

```
   ┌───────────────────────────────┬───────────────────────────────┐
   │   tools.voiddo.com            │   extensions.voiddo.com       │
   │   21 free cli + npm utils     │   4 live · 8 incoming         │
   │   npm i -g @v0idd0/<thing>    │   chrome / firefox / edge     │
   │   zero tracking, one purpose  │   manifest v3, cross-vendor   │
   ├───────────────────────────────┼───────────────────────────────┤
   │   games.voiddo.com            │   ai.voiddo.com               │
   │   8 weird browser games       │   ai tools that don't spam    │
   │   no microtransactions        │   flagships + experiments     │
   │   factory builders, decay sims│   one gemini chokepoint       │
   └───────────────────────────────┴───────────────────────────────┘
```

- **[tools.voiddo.com](https://tools.voiddo.com/)** — 21 single-purpose dev cli tools on `@v0idd0/*` npm. each does one thing, in 30 seconds, with zero deps. the kind of utility you'd write yourself in a flight delay if you weren't busy.
- **[extensions.voiddo.com](https://extensions.voiddo.com/)** — chrome / firefox / edge extensions. the AI-flavoured ones share one studio backend with hard daily caps so a runaway prompt can't bankrupt the whole studio.
- **[games.voiddo.com](https://games.voiddo.com/)** — eight browser games. one factory builder, one rust simulator, one block puzzle, one anchor-the-ship physics toy, several others. nothing tries to sell you gems. all OSTs released as standalone albums.
- **[ai.voiddo.com](https://ai.voiddo.com/)** — where the ai-flavoured products live. flagships above plus the experiments still cooking. one model router, one cost ceiling, one place to break.

extras for the curious: **[voiddo.com/music](https://voiddo.com/music/)** (4 game OSTs, one composer, no spotify-payola) · **[voiddo.com/studio](https://voiddo.com/studio/)** (how we operate, what we use, why no LTDs ever) · **[voiddo.com/blog](https://voiddo.com/blog/)** (one essay/week, no listicles) · **[voiddo.com/log](https://voiddo.com/log/)** (devlog, RSS, no medium).

---

## the reddit experiment (deadline: 2026-06-30)

reddit launched a developer funds program with a 60-day payout window. we're shipping a cap-protected trio of devvit apps to find out whether mods will actually install indie tools or whether everything reddit-shaped requires a series A.

| app | personality | dev sub |
|---|---|---|
| **rankd-judge** | pixel-art arcade verdict screen, gold-on-black, CRT scanlines | [r/rankd_judge_dev](https://www.reddit.com/r/rankd_judge_dev/) |
| **comment-summary** | mod-tool brutalism — terminal green on pure black, IBM Plex Mono | [r/comment_summary_dev](https://www.reddit.com/r/comment_summary_dev/) |
| **subbit-pulse** | hand-drawn newsletter on a torn journal page, daily 19:00 UTC recap | [r/subbit_pulse_dev](https://www.reddit.com/r/subbit_pulse_dev/) |

three different mediums, zero overlap. all hit one studio backend (`scrb.voiddo.com/api/v1/devvit/*`) routed to gemini flash lite. if this works, apps 4-10 follow. if it doesn't, this paragraph will be edited honestly.

---

## shipped lately

*manual update, not a feed. last refresh 2026-05-01.*

- **devvit trio scaffolded → uploaded → installed** — three reddit-native apps live in dev subs with owner-supplied pixel-art assets and a `tail-all-logs.sh` script that streams 3-color logs from one terminal.
- **chrome 3-pack approved in one sweep** — three extensions cleared the chrome web store on 2026-05-01. only randumb still in chrome review. firefox + edge listings staggered behind.
- **subportal architecture locked** — tools / extensions / games / ai each have a dedicated subdomain. apex is now a studio storefront, not a product list.
- **mergebench + anchorage shipped** — games portfolio went 6 → 8 with a noir merge-puzzle and a 3-anchor calm physics game.
- **wordpress plugin directory launch** — `scrb-ai-product-descriptions` cleared WP.org review. rankd WP plugin built and ready, on hold until scrb's queue clears.
- **admin dashboard rebuilt** — admin.voiddo.com pulls 12/15 sections live (revenue, costs, extension installs across 3 stores, npm downloads, github stars, mailer health, infra). honest "—" stubs for not-yet-connected sources.

---

## browser extensions (live + incoming)

```
LIVE     [tabsnap]  [tokcount]  [randumb]  [jsonyo*]  [jobmeta]
INCOMING [pricepulse]  [interviewprep]  [profilebrief]
         [videotldr]   [replyr]          [calmscreen]
         [shophunt]    [stackmap-lite]   [gigprime]
                                                       *also npm
```

all listings → [extensions.voiddo.com](https://extensions.voiddo.com/) · individual repo source under [github.com/voidd0](https://github.com/voidd0).

---

## free dev tools (`@v0idd0/*` on npm)

twenty-one open-source utilities. small, single-purpose, zero-tracking. install in one line, never think about them again.

```bash
npm i -g @v0idd0/cronwtf @v0idd0/jsonyo @v0idd0/regexlab \
         @v0idd0/secscan @v0idd0/passgen @v0idd0/sslcheck
```

| tool | what it does | tool | what it does |
|---|---|---|---|
| [cronwtf](https://github.com/voidd0/cronwtf) | decode any cron expression in plain english | [licenseme](https://github.com/voidd0/licenseme) | generate a LICENSE file in seconds |
| [ctxstuff](https://github.com/voidd0/ctxstuff) | pack context for LLM prompts, token-aware | [logparse](https://github.com/voidd0/logparse) | parse nginx / apache / syslog → structured |
| [depcheck](https://github.com/voidd0/depcheck) | audit npm deps (unused / missing / outdated) | [passgen](https://github.com/voidd0/passgen) | secure passwords + diceware, zero deps |
| [dotdig](https://github.com/voidd0/dotdig) | DNS lookup for humans | [portcheck](https://github.com/voidd0/portcheck) | see what's listening on local ports |
| [envguard](https://github.com/voidd0/envguard) | validate `.env` files against a schema | [promptdiff](https://github.com/voidd0/promptdiff) | diff two LLM prompts at the token level |
| [fakeit](https://github.com/voidd0/fakeit) | generate seedable fake test data | [regexlab](https://github.com/voidd0/regexlab) | explain any regex pattern in plain english |
| [gitstats](https://github.com/voidd0/gitstats) | git contribution stats by author / file / hour | [secscan](https://github.com/voidd0/secscan) | find committed secrets across a repo |
| [gitwhen](https://github.com/voidd0/gitwhen) | pinpoint when a string entered or left a repo | [slugmint](https://github.com/voidd0/slugmint) | i18n-aware URL slug generator |
| [httpwut](https://github.com/voidd0/httpwut) | explain any HTTP status / header, cited to RFC | [sslcheck](https://github.com/voidd0/sslcheck) | inspect TLS certs from CLI |
| [jsonyo](https://github.com/voidd0/jsonyo) | format / query / validate JSON, simpler than jq | [timecheck](https://github.com/voidd0/timecheck) | convert timestamps between formats / TZs |
| | | [tzdiff](https://github.com/voidd0/tzdiff) | compare timezones side by side |

hub at [tools.voiddo.com](https://tools.voiddo.com/).

---

## wordpress plugins

same studio backend, different distribution surface. wordpress sellers don't install chrome extensions and don't paste into web apps — they want a button inside their wp-admin. so we ship one.

| plugin | what it does | status |
|---|---|---|
| **scrb-ai-product-descriptions** | scrb's product description generator as a wp plugin — woocommerce-aware, 25 languages, same daily caps as the web app | live on wordpress.org |
| **rankd-content-quality-scorer** | rankd's quality verdict for posts and pages, in the editor sidebar | v1.0.0 built, queued behind scrb (wp.org one-plugin-at-a-time policy) |

we ship one wp plugin at a time, deliberately. the directory rejects spam and we'd rather pass review than rush submissions.

---

## the games

we make eight. nothing pay-to-win, nothing seasonal-FOMO, nothing that asks for your phone number.

| game | the one-line | live at |
|---|---|---|
| **void factory** | factory-builder roguelike with a dark sense of humour · also playable as android app at [play.voiddo.com](https://play.voiddo.com/) | [games.voiddo.com/void-factory](https://games.voiddo.com/void-factory/) |
| **gridlock** | minimalist block puzzle on a 4×4 grid | [games.voiddo.com/gridlock](https://games.voiddo.com/gridlock/) |
| **fe2o3.io** | a study in patient decay — you are the formula of rust | [games.voiddo.com/fe2o3](https://games.voiddo.com/fe2o3/) |
| **mergebench** | anti-dark-pattern merge puzzle, walnut + brass clockmaker noir | [games.voiddo.com/mergebench](https://games.voiddo.com/mergebench/) |
| **anchorage** | 3-anchor calm physics — dock the boat, don't break the cup | [games.voiddo.com/anchorage](https://games.voiddo.com/anchorage/) |
| **mossplots** | gardening sim where the moss outlives you | [games.voiddo.com/mossplots](https://games.voiddo.com/mossplots/) |
| **syncstrike** | rhythm puzzle, 60s loops, no DRM | [games.voiddo.com/syncstrike](https://games.voiddo.com/syncstrike/) |
| **crestfall** | one-screen roguelike, permadeath, 5 minutes per run | [games.voiddo.com/crestfall](https://games.voiddo.com/crestfall/) |

all OSTs by [Egor Michurin](https://voiddo.com/music/), released as standalone albums (bandcamp + spotify, no payola) at [voiddo.com/music](https://voiddo.com/music/).

---

## how we operate

- **ship before you're ready.** code on a laptop is a liability. production is the only place feedback lives.
- **server logs and conversion rates do not lie.** every other metric we publish is a marketing fiction.
- **one studio backend.** every AI-flavoured product routes through the same gemini chokepoint with hard daily caps. one bug fix patches every product.
- **craft requires staying small.** four-figure-per-month MRR is the current measuring stick. we'd rather grow slowly than die in series-A debt.
- **one canon, no exceptions.** every public-facing surface ends with the same studio signature. footer enforced via pre-commit hook in all 27 repos.

---

## what we don't do

- **no venture capital.** no board, no growth-at-all-costs, no exit timeline. revenue funds the next thing we build.
- **no tracking, no analytics SDKs.** server logs and stripe-equivalent receipts are enough. nobody at vøiddo needs to know which button you hovered.
- **no lifetime deals as a strategy.** windfalls accepted, never planned around. recurring is the only sustainable shape.
- **no cargo-cult AI.** if a feature works better as `awk` or a regex, it ships as `awk` or a regex. AI gets pulled in when the alternative is genuinely worse.
- **no platform lock-in.** chrome extensions also build for firefox + edge from day one. CLIs run on darwin / linux / win32. data exports as json / markdown by default.
- **no over-promising.** if the README says "30 lines of code, zero deps", the package on npm is 30 lines of code with zero deps. claims and reality match or the README gets rewritten.

---

[apex](https://voiddo.com/) · [tools](https://tools.voiddo.com/) · [extensions](https://extensions.voiddo.com/) · [games](https://games.voiddo.com/) · [ai](https://ai.voiddo.com/) · [music](https://voiddo.com/music/) · [studio](https://voiddo.com/studio/) · [blog](https://voiddo.com/blog/) · [log](https://voiddo.com/log/) · [contact](https://voiddo.com/contact/) · [npm](https://www.npmjs.com/org/v0idd0) · [reddit](https://www.reddit.com/user/voiddo/)

---

Built by [vøiddo](https://voiddo.com/) — a small studio shipping AI-flavoured products, free dev tools, Chrome extensions and weird browser games.
