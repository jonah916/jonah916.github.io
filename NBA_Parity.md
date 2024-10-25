---
layout: inner
title: "The NBA's Parity Renaissance"
permalink: /nba-parity-renaissance-is-here
---
# The NBA's Parity Renaissance Is Here

<br>

<html>
<head>
    <style>
        * {
            margin: 0;
            padding: 0;
        }
        .imgbox {
            display: grid;
            height: 100%;
        }
        .center-fit {
            max-width: 100%;
            max-height: 100vh;
            margin: auto;
        }
    </style>
</head>
<body>
<div class="imgbox">
    <img class="center-fit" src='/img/posts/NBA-Parity/Jokic%20FMVP.webp'>
</div>
</body>
</html>

<!-- <p align="center">  <img src="/img/posts/NBA-Parity/Jokic%20FMVP.webp" width="710" height="400" /> </p> -->
<p align="center"> <em>Source: Kyle Terada/USA TODAY Sports/Reuters</em> </p>

<br>

When the Denver Nuggets won Game 5 of the 2023 Finals to clinch the NBA championship, it didn’t take long for folks on the internet to try putting an asterisk on the achievement. The most common critique was that the Nuggets had an easy run to the title by drawing weak playoff opponents, including a Conference Finals matchup with the 7th-seed Lakers and a date in the Finals with the 8th-seed Miami Heat, only the second 8th-seed to ever make the Finals. One Reddit user [pointed out](https://www.reddit.com/r/nba/comments/165fk8w/the_denver_nuggets_were_the_first_team_since_the/) that Denver is the first team since 1976 to win a championship without beating a single 50-win team.

<br>

Never mind that Denver’s championship came on the shoulders of a [historic playoff run](https://www.si.com/nba/2023/06/13/nikola-jokic-2023-nba-finals-mvp-nuggets-heat#:~:text=Additionally%2C%C2%A0Joki%C4%87%E2%80%99s%C2%A0feats%20in%20the%20Finals%2C%20which%20included%20the%C2%A0first%2Dever%2030/20/10%20performance%2C%20capped%20a%20tear%20where%20he%20also%C2%A0set%20the%20record%20for%20the%C2%A0most%20playoff%20triple%2Ddoubles%C2%A0(10).%20The%202023%20MVP%20runner%2Dup%20finished%20the%20playoffs%20averaging%2030%20PPG%2C%2013.5%20RPG%20and%209.5%20APG.) by Nikola Jokic—he recorded a triple-double in half of his team’s 20 playoff games—or that the runner-up Miami Heat were no joke, having knocked off the 1- and 2-seed in the East to get to the Finals. The haters’ analysis overlooks a key detail, which is that the NBA is in the middle of an era of competitive balance, where the gap between the best teams and the middle of the pack (and between the middle of the pack and the basement-dwellers) is small in historical terms. It’s been a few seasons since we’ve seen any eye-popping team [records](https://www.reddit.com/r/nba/comments/12f88le/no_team_will_hit_60_wins_for_the_first_82game_nba/). Betting markets have had flatter championship [odds](https://www.sportsoddshistory.com/nba-champs/#Finals) in recent years, and a different team has won the title in each of the last five seasons, the first time that’s happened [since 1977-81](https://twitter.com/SportsCenter/status/1668646095864381440).

<br>

The recent trend towards parity places last season’s Nuggets team in an unusual context. There were only six teams in 2022-23, including Denver, that won 50 games, which is tied for the sixth fewest 50-win teams in a season when accounting for the number of teams in the league.

<br>
<p align="center">  <img src="/img/posts/NBA-Parity/nba-seasons-with-the-fewest-50-win-teams-datawrapper.png" width="550"/> </p>
<p align="center"> <em>Figure 1</em> </p>
<br>

The Nuggets didn’t draw any 50-win teams in the playoffs because there weren’t many 50-win teams to draw in the first place. Rather than using this as a reason to dunk on them, I think it’s worth trying to understand this dynamic so we can appreciate what it means for the past, present, and future of the NBA. How has the level of competitive parity changed throughout NBA history? Why do these changes occur? And what do the answers portend for the future of basketball?

<br>

## Measuring Parity
<br>
Before we can talk about parity, we need a way to measure it. There is clearly a different dynamic at play in a season like 2022-23, when only six teams across the whole league surpassed 50 wins, than a season like 2009-2010, when there were eight 50-win teams in the Western Conference alone. Is it possible to sum up these different dynamics in one number?

<br>

One metric that works fairly well is the standard deviation (SD) of team win percentage. In broad terms, the difference between balanced and imbalanced seasons is the spread of team quality: Are the good teams much better than the bad teams? Or are teams more clustered around the middle of the pack? Taking the SD of team win percentage shows us how close the average team in a given season is to winning 50% of its games. A low SD indicates more parity, as more teams hover around that 50% benchmark, while a high SD reflects more teams rising to the top or sinking to the bottom.

<br>

When we plot this metric over time, three periods of high parity, i.e. low SD, stand out.

<br>

<p align="center">  <img src="/img/posts/NBA-Parity/parity_by_season.png" width="700" /> </p> <p align="center"> <em>Figure 2</em> </p>

<br>

Between 1975-1979, 2001-2007, and 2020-present, the NBA saw higher levels of competitive balance, with fewer teams dominating the standings and more teams sitting in a band of about 30 to 50 wins. Zooming in on each of these time spans reveals something interesting about the dynamics of competitive balance in the NBA and helps answer our second question: what causes changes in parity over time?

<br>

But first a word about this metric, the SD of win percentage. There are a few clear drawbacks to framing parity this way. For one, it says nothing about *individual* team strength in a given season. It’s not guaranteed that the “best” team will have the best record, due to injuries, schedule strength, or just getting unlucky in close games. Further complicating this point is that wins are zero-sum. In a high-parity season, the “best” teams won’t have very high win totals since the wins are more spread out around the league. This is something forgotten by those in the “Nuggets are fake champions for getting weak opponents” camp.

<br>

This metric also can’t differentiate between two situations where parity might arise: 1) on average, teams are really good (or really bad) and they balance each other’s records out, or 2) the average team is mediocre. If both situations result in standings with lots of teams clustered around a 50% win rate, our metric can’t explain which dynamic is at play.

<br>

However, if the goal is to identify and understand the changing dynamics of league parity over time, SD of win percentage serves that purpose. It captures situations where the top teams win many games *and* the bottom teams win very few games. These situations are obviously correlated, but not perfectly so. It’s also an interpretable proxy for other potential metrics of parity. If we reproduce the above figure with win percentage replaced by Simple Rating System, a slightly more complicated metric based on margin of victory, the trend is pretty much identical.

<br>

## The Two Paths to Parity
<br>
The 1975-1979 seasons were a transformative period for the NBA. The 1975 merger between the NBA and ABA leveled the playing field as two vastly [different](https://en.wikipedia.org/wiki/ABA%E2%80%93NBA_merger#ABA_contributions_to_NBA_play) playing styles came into contact, likely contributing to the first era of NBA parity. Why did this era come to an abrupt end in the 1979-80 season? Was it the adoption of the three-point line? The signing of the NBA’s [first](https://en.wikipedia.org/wiki/1979%E2%80%9380_NBA_season#:~:text=This%20was%20the%20first%20season%20the%20NBA%20had%20a%20cable%20television%20partner.%20The%20USA%20Network%20signed%20a%20three%2Dyear%2C%201.5%20million%20dollar%20deal.) cable TV deal?

<br>

The demise of the first era of parity—and the birth of the modern NBA—can be boiled down to two things: Magic and Bird. Both drafted in 1979, Magic Johnson and Larry Bird each made their teams instant championship contenders and irreversibly transformed the NBA into a star-powered league. Every year from 1980 to 1989, at least one of the Magic-led Lakers and Bird-led Celtics made the Finals, winning eight of the ten championships in that span. During this decade alone, the two teams’ rosters would also include Hall of Famers Kareem Abdul-Jabar, Ralph Sampson, Robert Parish, Tiny Archibald, and Kevin McHale.

<br>

Other teams were forced to recruit more talented players in order to keep up, forming the first superteams of the modern NBA. In 1982, the Philadelphia 76ers traded for reigning MVP Moses Malone, giving them a second superstar to pair with Julius Erving. The league became top-heavy as a small number of teams entered into a superstar arms race.

<br>

Only a handful of the 48 seasons since the NBA-ABA merger have not been shaped by the superteam dynamic. Those few seasons align almost perfectly with the valleys in Figure 2, leading to our first conclusion about the source of competitive balance: *parity arises in the absence of superteams*.

<br>

It might seem trivial at first, but the entire history of the NBA, as well as the come and go of parity, can be framed in terms of the ebb and flow of superteams. The Lakers and Celtics dynasties of the ‘80s gave way to the Jordan Bulls of the ‘90s. Jordan’s retirement and the decline of the Kobe-Shaq Lakers paved the way for the second era of parity from 2001 to 2007. Although there were teams like the Spurs and Mavericks that saw consistent success in that period, no teams recorded gaudy win totals season after season like the superteams of the two decades prior.

<br>

The league’s competitive balance was short-lived, though, overtaken by the formation of the superteam Celtics, Heat, and, most recently, Warriors. Since Kevin Durant’s 2019 departure from the Warriors and the beginning of the end for that dynasty, we’ve been in the third and current era of NBA parity.

<br>

There’s more to the story of this era than just the absence of superteams. The league has recently been undergoing an offensive revolution, with scoring numbers soaring to all-time highs at ever more efficient rates.
<br>
<p align="center">  <img src="https://www.sportico.com/wp-content/uploads/2023/12/Screenshot-2023-12-20-at-1.37.25-PM.png" width="350"/> </p> 
<p align="center"> <em>Source: Lev Avakabs/Sportico</em> </p>
<br>

In the 2022-23 season, the average team scored 114.8 points per 100 possessions, up from 103.6 in 2003 and 105.9 in 2013. December 2023 saw the [highest league-wide offensive rating](https://open.spotify.com/episode/282938bN1UyyCmGCtai08G?si=a24fd2e724da4207) ever recorded in a calendar month. It’s not just a few high-scoring teams driving the surge. The median offensive team in 2023 would have led the entire league just five years earlier. The worst offense in 2023 would have been average in 2018. It seems that a rising tide has been lifting all boats.

<br>

What’s behind the scoring explosion? It’s true that NBA referees have changed how they enforce [rules](https://www.youtube.com/watch?v=6IPXSqOhykg) over time, making it harder for defenders to defend and easier for scorers to score. It’s also true that teams’ investments in [analytics](https://www.simonandschuster.com/books/Betaball/Erik-Malinowski/9781501158209) have unlocked new heights of offensive potential.

<br>

Officiating and smarter tactics definitely matter, but in this case the best explanation might be the simplest one: the level of offensive talent in the league is likely at an all-time high, both at the player and team level. There are seemingly dozens of players who can score from anywhere on the court, forcing defenses to overcommit to the ball handler and give open looks to other offensive players.
<p align="center">  <img src="/img/posts/NBA-Parity/Pacers_offense.gif" width="600"/> </p> 
<p align="center"> <em>Source: NBA Stats</em> </p>

<br>

Sophisticated [offensive systems](https://www.youtube.com/watch?v=dvyiAiF6L9c), replete with screens and off-ball movement, now leverage their shooters to make defenses pay for the slightest mistakes. The result is a surge in the number of players scoring on both high efficiency and high volume, particularly on threes.
<br>
<p align="center">  <img src="/img/posts/NBA-Parity/shooters_by_season.png" width="700" /> </p> <p align="center"> <em>Figure 3</em> </p>
<br>

This suggests that there’s another source of competitive balance: *parity emerges when the league’s average offensive ability increases*. There isn’t as much historical precedent for this idea, since there has never been such a dramatic rise in scoring in the modern NBA before. But the current trend of league parity is in part characterized by a wider range of possible outcomes to games, with teams more often getting into high-volume shootouts that either side could win depending on how the ball happens to fall on any given night.

<br>

The [Kings](https://kingsherald.com/commentary/the-kings-are-living-and-dying-by-the-three/), for example, shoot a lot of threes. In wins, they shoot an outstanding 40% on three-pointers and score 125.7 points. In losses, those figures sink to 33% and 108.7 points. Even this year’s Pistons, possibly the worst team of all time, have managed to win eight games by shooting nearly 44% from three, up from 36% on average.

<br>

The point is that any team with at least a few highly skilled shooters, which these days is *basically every team*, has a fighting chance to get hot and shoot their way to victory.

<br>

## Is Parity Here to Stay?
<br>
When the 2014-15 season began, the Warriors were considered B-tier championship contenders, well [outside](https://www.sportsoddshistory.com/nba-main/?y=2014-2015&sa=nba&a=finals&o=r) the ranks of the top teams. Golden State ended up winning the championship that year, propelled by Steph Curry’s leap from mere All-Star to all-time great superstar. Nobody saw Steph’s leap coming, nor could anyone have predicted Kevin Durant’s decision to join forces with Curry two seasons later and dominate the NBA for the rest of the decade. As idiosyncratic as they are, these things happen and they have the power to reshape the league for years.

<br>

To whatever extent we can predict the future, the NBA seems poised to stay competitive for the time being. As of this writing in February 2024, a relatively modest eight teams are on pace for 50 or more wins. The championship race is still wide open. In addition, the offensive explosion shows no signs of slowing down, with a ridiculous six teams on pace to break the all-time best offensive rating of 119.4 set just last season. Only time will tell, but the trends that have driven parity the last few years have either held steady or accelerated so far this season.

<br>

Teams that consider themselves contenders should go all in and take advantage of this opportunity. Last season’s Nuggets did exactly that, using trades and free agency to add key [role](https://www.nba.com/news/nuggets-acquire-kentavious-caldwell-pope-in-trade-with-wizards) [players](https://milehighsports.com/denver-nuggets-sign-wing-bruce-brown-to-two-year-contract-nba-free-agency/) while also developing young [talent](https://www.theringer.com/nba-finals/2023/5/31/23742962/michael-porter-jr-denver-nuggets) that came up big in the playoffs. Teams should also invest heavily in defensive development. If offensive firepower is a driver of parity, it stands to reason that the first teams to solve the puzzle of how to curtail these high-octane offenses will gain a huge advantage over the rest of the league.

<br>

As for the fans, I think we shouldn’t take for granted just how unusual and exciting a place the league is in right now. Historically speaking, parity is the exception to the rule. Keeping this in mind makes it easier to appreciate teams like the Nuggets that are able to compete without accruing superstars and utterly dominating the NBA, while bickering about which teams’ accomplishments are “real” obscures the high quality of play we’ve been treated to these last few years.

<br>

Parity will very likely subside some day, once another superteam forms, team defense improves, or rule enforcement changes. But until the winds of competitive balance shift again, I’ll enjoy watching the near-nightly scoring outbursts, with absolutely no idea who among the many deserving teams will eventually be the one to win it all.
