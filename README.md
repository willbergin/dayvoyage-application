# Dayvoyage

[Open Dayvoyage](https://dayvoyage-application.vercel.app/) · [User guide](USER_GUIDE.md)

## What it is

Dayvoyage helps you find somewhere to go for the day. Start from a city or town, choose an interest, set a one-way journey limit and pick a travel mode. Explore the suggestions on a map, check the journey estimate and share a trip.

## Key features

- Search from a city or town, with a choice when several locations match.
- Filter by interest, one-way journey limit and driving or public transport.
- See up to three trips first. Reveal up to three more when available.
- Follow routes on the map and cancel a search while it runs. The loading graphic respects reduced-motion settings.
- Read destination descriptions and, in the v1.4 preview, open **Why visit** for sourced highlights where available.
- Share a trip by email, WhatsApp or copied text.

## Current status

The live site runs v1.3. The v1.4 preview includes wider destination coverage, improved recommendations, sourced activity highlights, English location names where available and SVG controls. Trip search on the live site is currently unavailable while routing is being configured.

## Tech stack

| Area | Technology |
| --- | --- |
| Interface | HTML, CSS, vanilla JavaScript and SVG with Nunito typography |
| Maps | Leaflet and OpenStreetMap |
| Search and routing | Geoapify Geocoding, Places, Route Matrix and Routing APIs |
| Hosting | Vercel static hosting, Node.js Functions and CDN caching |
| Destination data | Curated JavaScript data and Geoapify results |
| Verification | Node.js 22 checks and tests, mocked provider responses and GitHub Actions |

The site runs without a frontend framework, build step, accounts or database.

## Technical decisions and trade-offs

| Decision | What it means for users |
| --- | --- |
| Use routed journey estimates | The trip limit is one way. Road traffic and public transport timetables can change. |
| Rank a shortlist | The app suggests a handful of trips based on the available destination and route data. |
| Reveal more from the same search | Expanding the results keeps the same preferences and updates the map. |
| Source activity details from visitor information | Destinations with published highlights can show more detail. Other cards include a brief description and link. |

## Privacy and sources

Dayvoyage has no accounts or saved-trip history. It uses [Geoapify](https://www.geoapify.com/) for search and routing and [OpenStreetMap](https://www.openstreetmap.org/copyright) for maps. Curated highlights point to visitor operators, tourism authorities and park agencies when available. Apps opened through a share link handle sharing under their own terms.
