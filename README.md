# ![LOGO](logo.png) College Football Data **flow**ground Connector

## Description

A generated **flow**ground connector for the College Football Data API (version 1.1.1).

Generated from: https://api.apis.guru/v2/specs/collegefootballdata.com/1.1.1/swagger.json<br/>
Generated at: 2019-05-07T17:40:06+03:00

## API Description

This is an API for accessing all sorts of college football data.  It currently has a wide array of data ranging from play by play to player statistics to game scores and more.

## Authorization

This API does not require authorization.

## Actions

### Get coach records and school history

> Coaching history

*Tags:* `coaches`

#### Input Parameters
* `firstName` - _optional_ - First name filter
* `lastName` - _optional_ - Last name filter
* `team` - _optional_ - Team name filter
* `year` - _optional_ - Year filter
* `minYear` - _optional_ - Minimum year filter (inclusive)
* `maxYear` - _optional_ - Maximum year filter (inclusive)

### Get conference list

> Conferences

*Tags:* `conferences`

### Get drive information

> Drive results

*Tags:* `drives`

#### Input Parameters
* `seasonType` - _optional_ - Season type filter
* `year` - _required_ - Year filter
* `week` - _optional_ - Week filter
* `team` - _optional_ - Team filter
* `offense` - _optional_ - Offensive team filter
* `defense` - _optional_ - Defensive team filter
* `conference` - _optional_ - Conference filter
* `offenseConference` - _optional_ - Offensive conference filter
* `defenseConference` - _optional_ - Defensive conference filter

### Get game information

> Game results

*Tags:* `games`

#### Input Parameters
* `year` - _required_ - Year/season filter for games
* `week` - _optional_ - Week filter
* `seasonType` - _optional_ - Season type filter (regular or postseason)
* `team` - _optional_ - Team
* `home` - _optional_ - Home team filter
* `away` - _optional_ - Away team filter
* `conference` - _optional_ - Conference abbreviation filter

### Get player statistics by game

> Player game stats

*Tags:* `games`

#### Input Parameters
* `year` - _required_ - Year/season filter for games
* `week` - _optional_ - Week filter
* `seasonType` - _optional_ - Season type filter (regular or postseason)
* `team` - _optional_ - Team filter
* `conference` - _optional_ - Conference abbreviation filter
* `category` - _optional_ - Category filter (e.g defensive)
* `gameId` - _optional_ - Game id filter

### Get team statistics by game

> Team game stats

*Tags:* `games`

#### Input Parameters
* `year` - _required_ - Year/season filter for games
* `week` - _optional_ - Week filter
* `seasonType` - _optional_ - Season type filter (regular or postseason)
* `team` - _optional_ - Team filter
* `conference` - _optional_ - Conference abbreviation filter
* `gameId` - _optional_ - Game id filter

### Get play type list

> Types of plays

*Tags:* `plays`

### Get play information

> Play results

*Tags:* `plays`

#### Input Parameters
* `seasonType` - _optional_ - Season type filter
* `year` - _required_ - Year filter
* `week` - _required_ - Week filter
* `team` - _optional_ - Team filter
* `offense` - _optional_ - Offensive team filter
* `defense` - _optional_ - Defensive team filter
* `conference` - _optional_ - Conference filter
* `offenseConference` - _optional_ - Offensive conference filter
* `defenseConference` - _optional_ - Defensive conference filter
* `playType` - _optional_ - Play type filter

### Get historical rankings and polls

> Poll rankings

*Tags:* `rankings`

#### Input Parameters
* `year` - _required_ - Year/season filter for games
* `week` - _optional_ - Week filter
* `seasonType` - _optional_ - Season type filter (regular or postseason)

### Get team roster

> Roster data

*Tags:* `teams`

#### Input Parameters
* `team` - _required_ - Team name

### Get team talent rankings

> Team talent composite

*Tags:* `teams`

#### Input Parameters
* `year` - _optional_ - Year filter

### Get team information

> Team information

*Tags:* `teams`

#### Input Parameters
* `conference` - _optional_ - Conference abbreviation filter

### Get matchup history

> Matchup history

*Tags:* `teams`

#### Input Parameters
* `team1` - _required_ - First team
* `team2` - _required_ - Second team
* `minYear` - _optional_ - Minimum year
* `maxYear` - _optional_ - Maximum year

### Get venue information

> Venues

*Tags:* `venues`

## License

**flow**ground :- Telekom iPaaS / collegefootballdata-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
