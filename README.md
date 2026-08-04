# Sportmonks (sportmonks)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Sportmonks is a Dutch sports data provider (Deventer, Netherlands) delivering developer-friendly REST APIs for football/soccer, cricket, and motorsport (Formula 1). The platform serves 30,000+ active users and 20,000+ developers building livescore portals, fantasy games, betting platforms, sports media products, and analytics tools. Sportmonks emphasizes fast real-time updates (<15 seconds), 99.9% uptime, transparent per-league pricing, and a forever-free tier covering selected leagues. APIs use JSON over REST with API token authentication via either an Authorization header or an `api_token` query parameter, and support fine-grained response shaping through filters, includes, and field selection.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sportmonks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sportmonks/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Cricket
- Data
- Developer-Friendly
- Football
- Formula 1
- Livescores
- Motorsport
- Real-Time
- Soccer
- Sports
- Sports Data
- Statistics

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Sportmonks Football API

REST API for soccer/football data covering 2,500+ leagues worldwide. Provides fixtures, livescores, schedules, standings, statistics, predictions, odds, teams, players, coaches, referees, venues, transfers, topscorers, and news. Supports request optimization via filters, includes, and field selection. Pricing tiers gate the number of leagues accessible, with a forever-free plan covering the Danish Superliga and Scottish Premiership.

- **Human URL:** [https://docs.sportmonks.com/football](https://docs.sportmonks.com/football)
- **Base URL:** `https://api.sportmonks.com/v3/football`

#### Tags

- Football
- Livescores
- Odds
- Predictions
- Real-Time
- Soccer
- Statistics

#### Properties

- [Documentation](https://docs.sportmonks.com/football)
- [Getting Started](https://docs.sportmonks.com/football/welcome/introduction)
- [Authentication](https://docs.sportmonks.com/football/welcome/authentication)
- [API Reference](https://docs.sportmonks.com/football/endpoints-and-entities)
- [Changelog](https://docs.sportmonks.com/football/changelog)
- [OpenAPI](openapi/sportmonks-football-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sportmonks-football.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sportmonks-football.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/sportmonks-fixture-example.json)
- [Example](examples/sportmonks-livescore-example.json)

### Sportmonks Cricket API

REST API for cricket data covering 130+ leagues including IPL, international fixtures, and T20 competitions. Provides ball-by-ball commentary, live scoreboards, fixtures, teams, players, venues, officials, seasons, leagues, and detailed player statistics. A Postman collection is published at cricket-postman.sportmonks.com.

- **Human URL:** [https://docs.sportmonks.com/cricket](https://docs.sportmonks.com/cricket)
- **Base URL:** `https://cricket.sportmonks.com/api/v2.0`

#### Tags

- Ball-By-Ball
- Cricket
- Livescores
- Real-Time
- Sports Data
- Statistics

#### Properties

- [Documentation](https://docs.sportmonks.com/cricket)
- [Getting Started](https://docs.sportmonks.com/cricket/welcome/introduction)
- [Postman Collection](https://cricket-postman.sportmonks.com/) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Postman Collection](collections/sportmonks-football.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sportmonks-football.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sportmonks Motorsport API

REST API for motorsport data including Formula 1 race results, qualifying, driver and constructor standings, lap times, season schedules, and circuit information. Replaces the deprecated Formula One v1 API with a v3 motorsport-wide surface area.

- **Human URL:** [https://docs.sportmonks.com/v3/motorsport-api/](https://docs.sportmonks.com/v3/motorsport-api/)
- **Base URL:** `https://api.sportmonks.com/v3/motorsport`

#### Tags

- Drivers
- Formula 1
- Motorsport
- Race Results
- Real-Time
- Standings

#### Properties

- [Documentation](https://docs.sportmonks.com/v3/motorsport-api/)
- [Getting Started](https://docs.sportmonks.com/v3/motorsport-api/welcome/introduction)
- [Postman Collection](collections/sportmonks-football.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sportmonks-football.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sportmonks Football Widgets

Embeddable JavaScript widgets that render Sportmonks football data as ready-to-use UI components for livescores, league tables, fixtures, and match details. Designed for media sites and football publishers who want to drop in branded visualizations without building front-end components.

- **Human URL:** [https://www.sportmonks.com/football-widgets/](https://www.sportmonks.com/football-widgets/)

#### Tags

- Embeddable
- Football
- Widgets

#### Properties

- [Documentation](https://docs.sportmonks.com/football/widgets)
- [Postman Collection](collections/sportmonks-football.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sportmonks-football.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.sportmonks.com/)
- [Portal](https://my.sportmonks.com)
- [Documentation](https://docs.sportmonks.com/)
- [Getting Started](https://docs.sportmonks.com/football/welcome/introduction)
- [Sign Up](https://my.sportmonks.com/register)
- [Pricing](https://www.sportmonks.com/football-api/)
- [Blog](https://www.sportmonks.com/blogs/)
- [Status Page](https://www.sportmonks.com/api-status/)
- [Support](mailto:support@sportmonks.com)
- [Terms of Service](https://www.sportmonks.com/terms-of-service/)
- [Privacy Policy](https://www.sportmonks.com/privacy-policy/)
- [LinkedIn](https://www.linkedin.com/company/sportmonks/)
- [X Twitter](https://twitter.com/Sportmonks)
- [GitHub Organization](https://github.com/sportmonks)
- [Postman Collection](https://cricket-postman.sportmonks.com/) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [JSON Schema](json-schema/sportmonks-fixture-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sportmonks-team-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sportmonks-player-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sportmonks-livescore-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sportmonks-league-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sportmonks-fixture-structure.json)
- [JSON-LD](json-ld/sportmonks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/sportmonks-rules.yml)
- [Vocabulary](vocabulary/sportmonks-vocabulary.yml)
- [Plans](plans/sportmonks-plans-pricing.yml)
- [Rate Limits](rate-limits/sportmonks-rate-limits.yml)
- [Fin Ops](finops/sportmonks-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
