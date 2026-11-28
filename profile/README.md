<p align="center"><img src="https://raw.githubusercontent.com/voidd0/.github/main/profile/banner.png" alt="vøiddo: public web data, delivered clean" width="100%"></p>

# vøiddo

**Public web data, delivered clean.** We build scrapers, run them for people who would rather receive a file, publish
the data we collect, and keep a shelf of small command line tools. Our scrapers and AI agents do the legwork; Egor
Michurin answers for every file that leaves.

**100** scrapers on the [Apify Store](https://apify.com/v0iddo) · **23** command line tools on
[npm](https://www.npmjs.com/~v0idd0) · **11** puzzle books on [Amazon](https://voiddo.com/books/?src=gh) ·
weekly salary data for Poland, Mexico and Colombia in [data-samples](https://github.com/voidd0/data-samples)
<sub>(counted 2026-11-28)</sub>

## Data

**[Scrapers on the Apify Store](https://apify.com/v0iddo).** Job boards, shops and marketplaces, app stores, ad libraries, maps, reviews and public registries. Each one takes a JSON input and returns rows you can download as CSV, JSON or Excel, or call from Python, Node.js or curl. You run them from your own Apify account and pay per result.

- The full list with prices per 1,000 results: [apify-actors](https://github.com/voidd0/apify-actors)
- A guide per scraper, with the output fields and ready inputs: [voidd0.github.io](https://voidd0.github.io/)
- Skills that let Claude Code, Codex, Copilot or Cursor pick and run the right scraper: [apify-skills](https://github.com/voidd0/apify-skills)
- Ready n8n workflows, one per scraper: [n8n-apify-workflows](https://github.com/voidd0/n8n-apify-workflows)
- Working example code for single scrapers: the repositories named `*-scraper` below

**[Data to order](https://voiddo.com/data/?src=gh).** Name a site and a search, and we run the scraper and email you the rows as CSV, Excel and JSON at a fixed price. You can ask for 50 rows of your own search first, at no charge.

**[data-samples](https://github.com/voidd0/data-samples).** Real rows from real runs, as CSV and JSON, under CC BY 4.0, so you can see the columns before you order. The weekly salary files are replaced every Monday.

## Command line tools

Small tools on npm under `@v0idd0`, each doing one job. Most have no dependencies, every one is tested on Node.js 18, 20, 22 and 24, and all are MIT licensed. Try one without installing:

```bash
npx @v0idd0/jsonyo --help
npx @v0idd0/sslcheck example.com
```

| tool | what it does |
|---|---|
| [cronwtf](https://github.com/voidd0/cronwtf) | explain a cron expression in plain English and list its next runs |
| [ctxstuff](https://github.com/voidd0/ctxstuff) | pack a code directory into one context file for LLM prompts |
| [depcheck](https://github.com/voidd0/depcheck) | find unused and missing npm and Python dependencies |
| [dotdig](https://github.com/voidd0/dotdig) | DNS lookups, optionally through a chosen public resolver |
| [envguard](https://github.com/voidd0/envguard) | validate a .env file against a typed schema |
| [gitstats](https://github.com/voidd0/gitstats) | lines of code, commits over time and hotspots of a git repository |
| [gitwhen](https://github.com/voidd0/gitwhen) | find when a string, a line or a file changed in git history |
| [httpwut](https://github.com/voidd0/httpwut) | an HTTP request with its timing breakdown and redirect chain |
| [jsonyo](https://github.com/voidd0/jsonyo) | validate, format, query, diff and convert JSON |
| [licenseme](https://github.com/voidd0/licenseme) | write a LICENSE file, or detect the license of a project |
| [logparse](https://github.com/voidd0/logparse) | parse, filter and count log lines (JSON, nginx, apache, plain) |
| [passgen](https://github.com/voidd0/passgen) | passwords and passphrases with an entropy estimate |
| [portcheck](https://github.com/voidd0/portcheck) | the ports your machine listens on, with the owning process |
| [promptdiff](https://github.com/voidd0/promptdiff) | compare two versions of an LLM prompt |
| [randumb](https://github.com/voidd0/randumb) | random test data that fits one locale |
| [regexlab](https://github.com/voidd0/regexlab) | explain a regular expression token by token |
| [secscan](https://github.com/voidd0/secscan) | find credentials committed by accident |
| [slugmint](https://github.com/voidd0/slugmint) | URL slugs from titles in many scripts |
| [sslcheck](https://github.com/voidd0/sslcheck) | inspect the TLS certificate of a host |
| [tabsnap](https://github.com/voidd0/tabsnap) | format a browser tab list as markdown, text or JSON |
| [timecheck](https://github.com/voidd0/timecheck) | convert unix and ISO timestamps |
| [tokcount](https://github.com/voidd0/tokcount) | estimate LLM tokens and input cost per model |
| [tzdiff](https://github.com/voidd0/tzdiff) | the time in several time zones side by side |

The same list with live output: [voiddo.com/packages](https://voiddo.com/packages/?src=gh).

## What we work with

Web scraping · Data extraction · Data cleaning · CSV, Excel and JSON · Google Sheets · Python · TypeScript · JavaScript · Node.js · SQL · PostgreSQL · REST APIs · API integration · Automation · AI agents and LLM integration · MCP servers · Apify actors · Linux · bash · nginx · Web design · Landing pages · Technical SEO · Technical writing · Data analysis · Testing · Puzzle book design.

## Contact

Data orders and samples: [data@voiddo.com](mailto:data@voiddo.com). Issues and pull requests are welcome in each repository. Anything else: [support@voiddo.com](mailto:support@voiddo.com) or [voiddo.com](https://voiddo.com/?src=gh). Terms and privacy: [voiddo.com/terms](https://voiddo.com/terms/) · [voiddo.com/privacy](https://voiddo.com/privacy/).

The repositories marked archived are hackathon entries from May 2026, kept as a record.
