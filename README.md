# ncaa-2022-data
## Schemas
### Teams
file: teams_yyyy-mm-dd.json (added at beginning of season)

{
  "team_id": 77,
  "url": "https://www.espn.com/mens-college-basketball/team/_/id/77/northwestern-wildcats",
  "location": "Northwestern",
  "nickname": "Wildcats",
  "conference": "Big Ten",
  "img_url": "https://a.espncdn.com/i/teamlogos/ncaa/500/77.png",
  "season": 2022
}

### Players
file: players_yyyy-mm-dd.json (added at beginning of season)

{
  "player_id": 4279625,
  "metadata": {
    "url": "https://www.espn.com/mens-college-basketball/player/_/id/4279625/jahlil-jenkins",
    "team_id": 2619,
    "first": "Jahlil",
    "last": "Jenkins",
    "school": "Stony Brook Seawolves",
    "number": "#1",
    "position": "Guard",
    "class": "Senior",
    "size": "6' 0\", 160 lbs",
    "home": "Ranson, WV",
    "img_url": "https://a.espncdn.com/combiner/i?img=/i/headshots/mens-college-basketball/players/full/4279625.png&w=350&h=254",
    "height_in": 72,
    "height": "6-0",
    "weight": 160
  },
  "season": 2022
}

### Daily Feed
file: pbp_yyyy-mm-dd.json (new files added daily)

#### Lines - summary of an individual player in a single game
{"type": "line", "game_id": 401365208, "player_id": 4397697, "season": 2022, "metadata": {"href": "https://www.espn.com/mens-college-basketball/player/_/id/4397697/jackson-stormo", "minutes": 32, "fg": 3, "fga": 10, "fg3": 0, "fg3a": 1, "ft": 0, "fta": 0, "oreb": 2, "dreb": 4, "reb": 6, "ast": 1, "stl": 0, "blk": 2, "tov": 0, "pf": 3, "pts": 6, "starter": true, "home": false, "opponent": "St. Bonaventure"}}

#### Recaps - game summaries from ESPN
{"type": "recap", "headline": "No. 23 Bonnies shrug off slow start in 75-47 win over Siena", "recap": ["<p>OLEAN, N.Y. -- — <a href=\"http://www.espn.com/mens-college-basketball/player/_/id/4397220/kyle-lofton\">Kyle Lofton</a> and <a href=\"http://www.espn.com/mens-college-basketball/player/_/id/4701016/jaren-holmes\">Jaren Holmes</a> scored 17 points apiece and No. 23 St. Bonaventure overcame a sluggish opening 20 minutes for a 75-47 victory over Siena on Tuesday night in the season opener for both schools.</p>", "<p>Aside from being ranked for the first time since January 1971, the Bonnies kicked off their season by unveiling an Atlantic 10 Conference regular season and tournament championship banner — the first time they’ve won both in the same year — and an eighth NCAA Tournament banner.</p>", "<p><a href=\"http://www.espn.com/mens-college-basketball/player/_/id/4397224/osun-osunniyi\">Osun Osunniyi</a>, who entered the game second among active players averaging 2.67 blocks, had seven blocks, with nine points and six rebounds for the Bonnies. Osunniyi was unable to finish the game, leaving with a nagging back injury.</p>", "<p>Pitt transfer <a href=\"http://www.espn.com/mens-college-basketball/player/_/id/4432889/abdoul-karim-coulibaly\">Abdoul Karim Coulibaly</a> scored 12 points off the bench for a St. Bonaventure team returning five starters — all seniors — and accounted for 89% of their offense from last season.</p>", "<p>Aiden Carpenter and <a href=\"https://www.espn.com/mens-college-basketball/player/_/id/4397552/jayce-johnson\">Jayce Johnson</a> each scored 10 for the Saints.</p>", "<p>The Bonnies missed nine of their first 11 attempts and trailed 18-8 with 12:12 left before closing the half up 36-32 after Holmes hit a 3 with 10 seconds left. St. Bonaventure then rewarded its first home crowd since the coronavirus pandemic began in March 2020 with an 12-2 run over a three-minute stretch to build a 58-42 lead with 8:20 left on Holmes’ 3-point basket.</p>", "<p>Coach Mark Schmidt chalked up the slow start to first-game jitters coupled with the pre-game ceremonies.</p>", "<p>“We needed to come back and refocus, and I didn’t think we did a great job at the beginning of the game,” Schmidt said. “But I thought, once we get down 17-7, I don’t think we rushed things. I thought we were composed.\"</p>", "<p>Siena is retooling after losing its top three scorers from the team that shared the Metro Atlantic Athletic Conference regular-season title last year.</p>", "<p>“If you watch the first 18 minutes, I think you are pretty encouraged, but need to be able to do it for 40 minutes,” Siena coach Carmen Maciariello said. “I wanted to play this team on the road to start our season, to show how hard we have to play, and what we have to do to get to where we want to get to.”</p>", "<p>Siena, which lost its five games last season by a combined margin of 13 points, endured its most lopsided loss since an 82-42 loss at St. Bonaventure on Dec. 5, 2018.</p>", "<p>The Bonnies seniors put it on themselves to play better in the second half.</p>", "<p>“I think that was a testament to having a veteran team,” Holmes said.</p>", "<p>“We know we can’t have those type of slow starts if we’re going to beat good teams and we want to be the best team,” he added. “I think those jitters are out and I think were ready to play next game already.”</p>", "<p>HIGHLIGHT REEL</p>", "<p>After a turnover in the Saints end, Osunniyi sprinted downcourt in time to block Michael Baer’s shot on a transition break.</p>", "<p>“He shouldn’t have turned it over,” Schmidt said with a laugh. “He’s a the difference-maker from a defensive standpoint, makes up for a lot of mistakes that these guys make.”</p>", "<p>BIG PICTURE</p>", "<p>Siena: It might not take as long as anticipated for the Saints to find their identity despite entering the season with an essentially new lineup which returned just three scholarship players. Siena was strong on defense in getting bodies on the perimeter to disrupt the Bonnies’ outside shooting attack before running into foul trouble in the second alf.</p>", "<p>St. Bonaventure: First-game jitters aside, shooting 13 of 31 from the field in the first half was an indication St. Bonaventure needs to do a better job of handling a 3-2 defense. On the plus side, the Bonnies bench came through with Coulibaly spelling Osunniyi and Wake Forest transfer Quardy Adams getting credit for his defensive play.</p>", "<p>SUSPENDED</p>", "<p>Bonnies starting guard <a href=\"http://www.espn.com/mens-college-basketball/player/_/id/4279431/jalen-adaway\">Jalen Adaway</a> served a one-game suspension due to what the school called a “minor NCAA rules infraction.” St. Bonaventure did not reveal the nature of the infraction, while noting Adaway will be eligible to play the remainder of the season.</p>", "<p>UP NEXT</p>", "<p>Siena: Play home opener against Delaware of the Colonial Athletic Association on Saturday.</p>", "<p>St. Bonaventure: Play second straight MAAC opponent in hosting regional rival Canisius on Sunday.</p>", "<p>------</p>"], "game_id": 401365208, "season": 2022, "date": "2021-11-09"}

#### Plays - individual game events (the vast majority of data)
{"type": "play", "game_id": 401365208, "play_id": 0, "clock": "00:19:41", "period": 1, "play": "Dominick Welch missed Three Point Jumper.", "team": 179, "visitor": 0, "home": 0, "metadata": {"player": "Dominick Welch", "result": "missed", "event": "Three Point Jumper"}, "season": 2022}


