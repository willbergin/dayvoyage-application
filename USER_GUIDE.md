# Dayvoyage user guide

[Open Dayvoyage](https://dayvoyage-application.vercel.app/) · [Project overview](README.md)

Dayvoyage helps you find places to visit for the day. Tell it where you're starting, what interests you and how far you want to travel. Dayvoyage suggests up to six trips.

## Find a day trip

1. Enter a city or town in the search box.
2. Choose an **Interest**. **Surprise me** offers a mix. Pick **Nature and outdoors** for parks, beaches and scenic places, **Towns and cities** for settlements, or **History and culture** for places such as castles, museums and heritage sites.
3. Set **Max journey (one way)** using the slider. It starts at 90 minutes and moves from 30 to 120 minutes in 15-minute steps.
4. Leave **Travel mode** on **Driving**, or switch to **Public transport**.
5. Select **Find trips**.

To try another interest or journey limit, change it and select **Find trips** again. Your starting location and preferences stay in the form while the page is open. A car or train graphic appears during the search and stays still if reduced motion is enabled. Select **Cancel search** to stop waiting and try a different search.

You can search for a place such as **Manchester, England, United Kingdom**. Adding the region or country can help if several places have the same name.

If Dayvoyage isn't sure which city you meant, it will show a list of matching locations. Choose the correct one to continue. In the v1.4 preview, search choices and trip cards prefer English place names where available. You can enter a local name such as München. The base map can still show local names.

Results are based on the destinations and route data available for that area. You might see a city, a historic town, a national park or an attraction. The total can be below six if only a few destinations match your interest and have a route within your limit.

## Explore the results

The map starts with your starting point and up to three destinations. If more trips qualify, choose **Show 3 more trips** or the button showing the available number. Choose **Show fewer trips** to return to the first three. The map updates as you show or hide trips. The results panel shows a short description and estimated journey time and distance. In the v1.4 preview, cards also show the trip’s interest category. Open **Why visit** for sourced highlights when available.

- Select a map marker to see the destination details.
- Close the results panel using **X** if you want more room on the map.
- Select **Show results** to bring the panel back.
- Use the official website or destination link to check opening hours, tickets and access. Some trips link to a Wikipedia search for more information.

For driving, the map may briefly show dashed guide lines before the detailed routes load. Public transport routes are drawn from the journey information returned with the search, when route geometry is available.

## Understand the journey times

Dayvoyage uses Geoapify to estimate journeys. The calculation depends on which travel mode you choose.

**Driving** uses mapped roads and a routing model. It does not account for live traffic, roadworks or your chosen departure time.

**Public transport** checks individual routes. Destinations without a usable route may be left out, and coverage varies by area. Journey times aren't a live timetable, so you should check available services and connections before leaving.

For large areas such as national parks, Dayvoyage may route you to a representative access point rather than a particular car park, entrance or trail.

The slider sets a limit for the outward journey. Always check the return trip, opening hours and any tickets you need.

## Share a trip

Select **Share trip** on a destination to choose how to send it:

- **Email** opens an email with the trip summary.
- **WhatsApp** opens a message with the details.
- **Copy summary** copies the suggestion so you can paste it somewhere else.

You don't need to create an account. Sharing sends the suggestion but doesn't save it in Dayvoyage.

## If a search doesn't work

If you can't find a location, try adding the country or searching for a nearby larger town.

A search can take longer when Dayvoyage is checking a new area. Repeated searches may be quicker because results are cached. Driving results may appear before the detailed map routes have loaded.

If you get no results, try a longer journey limit or choose **Surprise me**. Public transport coverage varies by area, so switching to **Driving** may also show more options.

If the site reports a location or routing service error, try again later. If the problem continues, the service may have limited coverage or be temporarily unavailable.

## A few things to know

Dayvoyage is a trip-finding tool, not a booking service. It doesn't provide live traffic, confirmed train or bus times, ticket prices, current attraction opening hours or reservations.

There is no login, saved-trip history or personal trip collection. You can share a suggestion or copy the details before leaving the page.

For more about Dayvoyage and its sources, see the [project overview](README.md).
