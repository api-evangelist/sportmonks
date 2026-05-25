# Sportmonks (sportmonks)
Sportmonks is a Dutch sports data provider (Deventer, Netherlands) delivering developer-friendly REST APIs for football/soccer, cricket, and motorsport (Formula 1). The platform serves 30,000+ active users and 20,000+ developers building livescore portals, fantasy games, betting platforms, sports media products, and analytics tools. Sportmonks emphasizes fast real-time updates (<15 seconds), 99.9% uptime, transparent per-league pricing, and a forever-free tier covering selected leagues.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/sportmonks/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Cricket, Data, Developer-Friendly, Football, Formula 1, Livescores, Motorsport, Real-Time, Soccer, Sports, Sports Data, Statistics

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Sportmonks Football API
REST API for soccer/football data covering 2,500+ leagues worldwide. Provides fixtures, livescores, schedules, standings, statistics, predictions, odds, teams, players, coaches, referees, venues, transfers, topscorers, and news. Supports request optimization via filters, includes, and field selection.

**Human URL:** [https://docs.sportmonks.com/football](https://docs.sportmonks.com/football)

**Base URL:** `https://api.sportmonks.com/v3/football`

#### Tags

 - Football, Livescores, Odds, Predictions, Real-Time, Soccer, Statistics

#### Properties

- [Documentation](https://docs.sportmonks.com/football)
- [Getting Started](https://docs.sportmonks.com/football/welcome/introduction)
- [Authentication](https://docs.sportmonks.com/football/welcome/authentication)
- [API Reference](https://docs.sportmonks.com/football/endpoints-and-entities)
- [Changelog](https://docs.sportmonks.com/football/changelog)
- [OpenAPI](openapi/sportmonks-football-openapi.yml)
- [Example — Fixture](examples/sportmonks-fixture-example.json)
- [Example — Livescore](examples/sportmonks-livescore-example.json)
- [Naftiko Capability — Livescores](capabilities/football-livescores.yaml)
- [Naftiko Capability — Fixtures](capabilities/football-fixtures.yaml)
- [Naftiko Capability — Standings](capabilities/football-standings.yaml)
- [Naftiko Capability — Predictions & Odds](capabilities/football-predictions.yaml)

### Sportmonks Cricket API
REST API for cricket data covering 130+ leagues including IPL, international fixtures, and T20 competitions. Provides ball-by-ball commentary, live scoreboards, fixtures, teams, players, venues, officials, seasons, leagues, and detailed player statistics.

**Human URL:** [https://docs.sportmonks.com/cricket](https://docs.sportmonks.com/cricket)

**Base URL:** `https://cricket.sportmonks.com/api/v2.0`

#### Tags

 - Ball-By-Ball, Cricket, Livescores, Real-Time, Sports Data, Statistics

#### Properties

- [Documentation](https://docs.sportmonks.com/cricket)
- [Getting Started](https://docs.sportmonks.com/cricket/welcome/introduction)
- [Postman Collection](https://cricket-postman.sportmonks.com/)
- [Naftiko Capability — Cricket Livescores](capabilities/cricket-livescores.yaml)

### Sportmonks Motorsport API
REST API for motorsport data including Formula 1 race results, qualifying, driver and constructor standings, lap times, season schedules, and circuit information. Replaces the deprecated Formula One v1 API with a v3 motorsport-wide surface area.

**Human URL:** [https://docs.sportmonks.com/v3/motorsport-api/](https://docs.sportmonks.com/v3/motorsport-api/)

**Base URL:** `https://api.sportmonks.com/v3/motorsport`

#### Tags

 - Drivers, Formula 1, Motorsport, Race Results, Real-Time, Standings

#### Properties

- [Documentation](https://docs.sportmonks.com/v3/motorsport-api/)
- [Getting Started](https://docs.sportmonks.com/v3/motorsport-api/welcome/introduction)
- [Naftiko Capability — Motorsport Races](capabilities/motorsport-races.yaml)

### Sportmonks Football Widgets
Embeddable JavaScript widgets that render Sportmonks football data as ready-to-use UI components for livescores, league tables, fixtures, and match details.

**Human URL:** [https://www.sportmonks.com/football-widgets/](https://www.sportmonks.com/football-widgets/)

#### Tags

 - Embeddable, Football, Widgets

#### Properties

- [Documentation](https://docs.sportmonks.com/football/widgets)

## Common Properties

- [Website](https://www.sportmonks.com/)
- [Portal](https://my.sportmonks.com)
- [Documentation](https://docs.sportmonks.com/)
- [Sign Up](https://my.sportmonks.com/register)
- [Pricing](https://www.sportmonks.com/football-api/)
- [Blog](https://www.sportmonks.com/blogs/)
- [Status Page](https://www.sportmonks.com/api-status/)
- [Support](mailto:support@sportmonks.com)
- [Terms of Service](https://www.sportmonks.com/terms-of-service/)
- [Privacy Policy](https://www.sportmonks.com/privacy-policy/)
- [LinkedIn](https://www.linkedin.com/company/sportmonks/)
- [X / Twitter](https://twitter.com/Sportmonks)
- [GitHub Organization](https://github.com/sportmonks)
- [Postman Collection](https://cricket-postman.sportmonks.com/)

## Features

| Name | Description |
|------|-------------|
| Real-Time Livescores | Sub-15-second push of score and match-event updates across covered competitions. |
| Filters, Includes, Field Selection | Per-request response shaping to keep payloads small and queries expressive. |
| Forever-Free Tier | Permanent free access to selected leagues (Danish Superliga, Scottish Premiership). |
| Per-League Pricing | Plans gate league count rather than charging per-call, making cost predictable. |
| 99.9% Uptime SLA | Published reliability target backed by a public status page. |
| Human Data Verification | 24/7 human-in-the-loop data processing layered on top of automated feeds. |
| Postman & Widgets | First-party Postman collections and embeddable football widgets. |

## Use Cases

| Name | Description |
|------|-------------|
| Livescore Portals | Public livescore sites consuming fixtures, livescores, and event feeds. |
| Fantasy Football | Fantasy game backends consuming player stats, lineups, and event data. |
| Sports Betting | Sportsbook and trading platforms consuming pre-match and in-play odds. |
| Sports Media | Editorial sites embedding widgets and pulling structured match data. |
| Football Clubs & Scouting | Clubs and analysts pulling player and team statistics. |
| iGaming | Fantasy, prediction, and casual gaming products powered by live sports state. |

## Integrations

| Name | Description |
|------|-------------|
| Postman | Official Sportmonks Cricket Postman collection at cricket-postman.sportmonks.com. |
| Community SDKs | 20+ community-maintained client libraries on GitHub across Python, PHP/Laravel, TypeScript, Go, Java, R, and Ruby. |

## Solutions

| Name | Description |
|------|-------------|
| Football API | Core soccer data API covering 2,300+ leagues with tiered league-count pricing. |
| Cricket API | Cricket data API with ball-by-ball detail across 130+ leagues. |
| Motorsport API | F1 and broader motorsport data API. |
| Football Widgets | Drop-in embeddable widgets for media and publisher sites. |

## Artifacts

### OpenAPI

- [Sportmonks Football API](openapi/sportmonks-football-openapi.yml)

### JSON Schema

- [Fixture](json-schema/sportmonks-fixture-schema.json)
- [Livescore](json-schema/sportmonks-livescore-schema.json)
- [League](json-schema/sportmonks-league-schema.json)
- [Team](json-schema/sportmonks-team-schema.json)
- [Player](json-schema/sportmonks-player-schema.json)

### JSON Structure

- [Fixture Structure](json-structure/sportmonks-fixture-structure.json)

### JSON-LD

- [Sportmonks Context](json-ld/sportmonks-context.jsonld)

### Examples

- [Fixture Example](examples/sportmonks-fixture-example.json)
- [Livescore Example](examples/sportmonks-livescore-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Sportmonks Football API](capabilities/shared/sportmonks-football.yaml) — 15 operations covering livescores, fixtures, leagues, teams, players, standings, predictions, and odds.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Football Livescores](capabilities/football-livescores.yaml) | Football | 2 | Livescore Portal Developer |
| [Football Fixtures](capabilities/football-fixtures.yaml) | Football | 3 | Livescore Portal Developer |
| [Football Standings](capabilities/football-standings.yaml) | Football | 1 | Sports Media Editor |
| [Football Predictions & Odds](capabilities/football-predictions.yaml) | Football | 3 | Sportsbook Trader |
| [Cricket Livescores](capabilities/cricket-livescores.yaml) | Cricket | 2 | Livescore Portal Developer |
| [Motorsport Races](capabilities/motorsport-races.yaml) | Motorsport | 2 | Sports Media Editor |

## Vocabulary

- [Sportmonks Vocabulary](vocabulary/sportmonks-vocabulary.yml) — Unified taxonomy mapping 16 resources, 8 actions, 6 workflows, and 6 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Sportmonks Rules](rules/sportmonks-rules.yml) — 9 Spectral rules across 4 categories enforcing Sportmonks API conventions.

## Plans, Rate Limits, & FinOps

- [Plans & Pricing](plans/sportmonks-plans-pricing.yml) — Free + Starter (€29/mo) + Growth (€99/mo) + Pro (€249/mo) + Enterprise + 14-day trial.
- [Rate Limits](rate-limits/sportmonks-rate-limits.yml) — Per-entity hourly buckets scaling from 180/hr (Free) to 5,000/hr (Enterprise).
- [FinOps](finops/sportmonks-finops.yml) — FOCUS 1.3-aligned per-league subscription cost model in EUR.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
