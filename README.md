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

- [Profile command updating](https://github.com/Screemm/Renshuu/issues/1) - Currently only uses my API key. Update this to use the person who executes the command. - Status: Backlog
- [key remove not working](https://github.com/Screemm/Renshuu/issues/2) - The buttons for this command return "This interaction failed!". Proposed change: change this to a modal and require the user to type "confirm" or "cancel". - Status: Up Next
