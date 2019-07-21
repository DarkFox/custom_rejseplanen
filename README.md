# custom_rejseplanen

This is an improvement upon the [Rejseplanen](https://www.home-assistant.io/components/rejseplanen/) integration for Home Assistant.

## Differences

- Additional transport types added.
- All attributes changed to snake_case.
- Returns later departures as a list of dictionaries containing the same info as the next departure, instead of a string.
- Restricts the search to just the relevant types, when searching for specific types of transport, to return more results.

Obviously, most of these changes are entirely breaking from the built-in component, so don't expect this to be a drop-in replacement.
