# Jake Spencer

Full-stack developer building AI and data tools for fisheries, ocean science and conservation. CTO and co-founder of [Pelagos](https://pelagosinc.com). Based in St. Petersburg, FL.

[Portfolio](https://spencerinv.com) · [LinkedIn](https://www.linkedin.com/in/jacob-spencer-7b6481237) · jake@spencerinv.com

> **About my repositories:** most of my code is private because it belongs to clients, to the companies I work with, or to products people use every day. The projects below are real, and most of them are live. I'm happy to walk through the code for any of them on a screen share.

**Stack I use most:** JavaScript and TypeScript, React, Node.js and Express, Python (FastAPI, Flask, pandas, xarray), PostgreSQL, the Claude and OpenAI APIs, MCP servers, Render, GitHub Actions.

---

## Pelagos product suite

I lead technology at Pelagos, Inc.: platform architecture, data pipelines and the AI layer shared across these products.

- **[Fisheries Intelligence Platform](https://fisheriesintel.com)**: one searchable record of U.S. fisheries management (council actions, regulations, stock assessments, vessel history and case law), with 700,000+ documents from 200+ sources. More than 110 scheduled ingestion jobs feed an AI chat that cites its sources and shows how far each one can be trusted. It also ships as a browser extension and an MCP server.
  *Node.js, Express, PostgreSQL, React, Claude API*
- **[SpeciesID Pro](https://speciesidpro.com)**: pulls species records out of PDFs and scanned field guides, then checks every name live against 10 taxonomic databases, including WoRMS, GBIF and OBIS. Each record carries a confidence score and a verbatim quote from the source. Exports to Darwin Core for GBIF and OBIS. It started as a parsing tool that cut manual species-list work by 95%.
  *Python, Flask, PostgreSQL, Claude API*
- **[NEPANav](https://nepanav.com)**: guided NEPA and Clean Water Act drafting for fisheries and marine agency staff. An AI drafting assistant works section by section, grounded in federal filings, case law and the user's own files.
  *TypeScript, Python, Claude API*
- **[WhenFree](https://whenfree.io)**: availability polls with no sign-up, calendar sync (Google, Outlook, Apple), booking pages and a live feed of public agency meetings. Available in English and Spanish.
  *React, Node.js, PostgreSQL*
- **[Environmental Policy Navigator](https://epn.pelagosinc.com)**: an AI research workspace over federal, state and municipal environmental policy. Eight source adapters feed about 180,000 records, and every answer links to the filed document. *In development.*
  *React, Node.js, PostgreSQL, Claude API*
- **[TideFrame](https://tideframe.pelagosinc.com)**: year-by-year coastal change timelines from satellite and aerial imagery, with shoreline-change rates corrected for the tide. *Early development.*
  *React, Node.js, PostgreSQL, Mapbox*
- **[Reel Boards](https://reelboards.com)**: live leaderboards for fishing tournaments, entered from the weigh station. It runs a seven-event offshore billfish series.
  *Python, FastAPI*
- **Pelagos Admin Console**: an internal console for managing access, plans, usage and errors across every tool.
  *Node.js, PostgreSQL*

## Research tools

- **[Loopwatch](https://spencerinv.com/tools/loopwatch)**: measures how close the Gulf's Loop Current comes to the West Florida Shelf every day since 1993, then tests what the shelf does afterward. The analysis plan was pre-registered before any results were opened, and the data refreshes daily.
  *Python (xarray, statsmodels), FastAPI, React*
- **[Siphon](https://spencerinv.com/tools/siphon)**: a planner for Florida seagrass and shellfish restoration. It estimates how much water planted clams, scallops or oysters filter each month, with every parameter cited to published research.
  *React, TypeScript*

## Conservation and advocacy tools (Akorn Environmental)

- **Menhaden petition platform**: a full-stack petition site supporting a menhaden conservation executive order. It collected 150,000+ signatures and drew national media coverage. I've also built petition platforms for state and city campaigns.
- **Menhaden Action**: a supporter enters a ZIP code and gets routed to their own elected officials and the Secretary of Commerce, with the letter already written. Every action is counted.
- **Marine conservation policy database**: the first comprehensive database of U.S. marine conservation policy, from federal to municipal level, built with web scraping and AI analysis for a Pew Charitable Trusts project.
- **TideGrant**: a grant management platform for Sea Grant programs.
  *React, Node.js, PostgreSQL*
- **Stakeholder interview system**: coordinates interview outreach for a fishery management review, covering scheduling, automated emails, reply parsing and dashboards on top of the Google Workspace APIs.
  *Node.js, React, PostgreSQL*
- **Knauss Konnect**: an alumni network and job board for Knauss marine policy fellows.

## Products and side projects

- **ArbitrageIQ**: watches sportsbooks and prediction markets (Kalshi, Polymarket, PredictIt) for arbitrage and mispriced markets, with a live dashboard and Telegram alerts.
  *Python, SQLite, APScheduler, React, WebSockets*
- **PatentScan**: point Claude Code at a codebase and get an IP report covering risk, opportunity, prior art and freedom to operate. Uses Google Patents on BigQuery and the USPTO API.
  *Claude Code, BigQuery, JavaScript*
- **[PickSport Plus](https://picksportplus.onrender.com)**: a weekly confidence pick'em pool for NFL and college football. Each week's slate is built from the games with the closest point spreads.
  *Python, FastAPI, PostgreSQL*
- **POP**: a pickleball tournament platform with rotating-partner schedules, live scoring, automatic rankings and a big-screen leaderboard.
  *Next.js, TypeScript, Prisma, PostgreSQL*
- **AutoYape+**: a Peruvian membership app where members join a fund and enter notarized weekly draws for new vehicles.
  *Next.js, Prisma*
- **[Topset](https://spencerinv.com/tools/topset)**: an offline-first lifting log with rep maxes and video of every set.

## Websites and games

I also run [Spencer Innovations](https://spencerinv.com), a small web and AI studio in Tampa Bay. Client sites include [billsullivanart.com](https://billsullivanart.com), [spencersautostyling.com](https://spencersautostyling.com) and [spencersplusrealty.com](https://spencersplusrealty.com).

Games you can play on the site: [The Perfect Season](https://spencerinv.com/games/perfect-season), [BallIQ](https://spencerinv.com/games/ball-iq) and [Where's Sylvester and Paul?](https://spencerinv.com/games/wsp)
