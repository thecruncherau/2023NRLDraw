# 2023 NRL Draw
Clean and accessible versions of the 2023 NRL Draw. All data sourced from nrl.com.

## Data Columns and Meanings
- `roundTitle` ~ the round number preceded by the string "Round"
- `venue` ~ the commercial name of the venue
- `venueCity` ~ the broader region of which the game is played
- `matchCentreUrl` ~ the nrl.com URL for the Match Centre of that game
- `homeTeam` ~ the home team 
- `awayTeam` ~ the away team
- `kickOffTime` ~ the Datetime that the game is scheduled to begin, in the **UTC** timezone.
- `nineNetworkBroadcast` ~ a boolean value that represents whether the Nine Network is scheduled to broadcast the game
- `foxBroadcast` ~ a boolean value that represents whether Foxtel and Kayo is scheduled to broadcast the game
