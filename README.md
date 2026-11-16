# Amsterdam MCP server and open data

A free, read-only [Model Context Protocol](https://modelcontextprotocol.io) server for Amsterdam, run by [Essentially Amsterdam](https://essentiallyamsterdam.com/), a daily English-language newsletter, events calendar, news, jobs board and business directory for the city.

- Endpoint: `https://essentiallyamsterdam.com/mcp` (streamable HTTP, no key needed)
- MCP Registry name: `com.essentiallyamsterdam/amsterdam`
- Server page: [https://essentiallyamsterdam.com/mcp-server/](https://essentiallyamsterdam.com/mcp-server/)

## Connect

Claude Code:

```
claude mcp add -t http essentially-amsterdam https://essentiallyamsterdam.com/mcp
```

Any client that takes a remote server URL:

```json
{
  "mcpServers": {
    "essentially-amsterdam": {
      "url": "https://essentiallyamsterdam.com/mcp"
    }
  }
}
```

## Tools

All tools are read-only. This list was read from the live server's tools/list response.

| Tool | What it does |
|---|---|
| `whats_on` | Events in Amsterdam on one day, today to six days ahead, optionally by category |
| `jobs` | Newest English-language jobs in the Amsterdam area, optionally by keyword |
| `directory_search` | Search local businesses in the Amsterdam directory by name, type or area |
| `markets_today` | Street and food markets open on a day, with hours |
| `conferences` | Upcoming Amsterdam conferences, by month or field |
| `guide_search` | Find a guide, free tool or best-of list for a question about Amsterdam, in English or Dutch |
| `recent_news` | Newest Amsterdam news, optionally by keyword |
| `net_salary` | Dutch gross-to-net pay for 2026, with or without the 30% ruling |
| `rent_points` | Dutch rent points (WWS) and the maximum legal basic rent |
| `museumkaart` | Whether a Museumkaart pays off for the museums you plan to visit |
| `meet_in_the_middle` | The point halfway between two or three addresses and nearby cafes, restaurants and bars |
| `nearest` | Nearest public toilets or playgrounds to a neighbourhood, postcode or address |
| `bike_theft` | Bicycle and moped thefts per neighbourhood, per 1,000 residents, ranked |

## Open datasets

See [datasets/](datasets/). Each dataset has a page on the site with a map or calculator built on it:

- Bike and moped theft per neighbourhood: [https://essentiallyamsterdam.com/tools/bike-theft-amsterdam-by-neighbourhood/](https://essentiallyamsterdam.com/tools/bike-theft-amsterdam-by-neighbourhood/)
- Public toilets: [https://essentiallyamsterdam.com/tools/public-toilets-amsterdam-map/](https://essentiallyamsterdam.com/tools/public-toilets-amsterdam-map/)
- Playgrounds: [https://essentiallyamsterdam.com/tools/amsterdam-playgrounds-map/](https://essentiallyamsterdam.com/tools/amsterdam-playgrounds-map/)

## Other pages

- [What's on in Amsterdam](https://essentiallyamsterdam.com/whats-on/)
- [English-language jobs](https://essentiallyamsterdam.com/jobs/)
- [Business directory](https://essentiallyamsterdam.com/directory/)
- [All free tools](https://essentiallyamsterdam.com/tools/)

## Licence

Code and documentation in this repository: MIT, see [LICENSE](LICENSE). Each dataset carries its own licence, stated in its folder.
