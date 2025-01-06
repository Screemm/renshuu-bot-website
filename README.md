# renshuu-bot-website

UNDER CONSTRUCTION

## Commands

**General**

- profile - Displays a profile with your Renshuu data in it.

**Key management**

- key
  - register - Allows users to register their Renshuu API key.
  - remove - Allows users to remove their Renshuu API key from the database.
  - update - Allows users to update their Renshuu API key.

**Known issues**

| # | Title | Description | Status |
| --- | --- | --- | --- |
| [1](https://github.com/Screemm/Renshuu/issues/1) | Profile command updating | Currently only uses my API key. Update this to use the person who executes the command. | Backlog |
| [2](https://github.com/Screemm/Renshuu/issues/2) | key remove not working | he buttons for this command return "This interaction failed!". Proposed change: change this to a modal and require the user to type "confirm" or "cancel". | Up Next |

## Getting your API key

1. Log into Renshuu.
2. Navigate to Resources > renshuu API
3. When prompted, copy and paste your read-only (top) key into the modal field.
