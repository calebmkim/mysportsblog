+++
title = "Comparing NBA Players to Programming Languages"
date = 2024-05-02
+++

Colin Cowherd makes some pretty weird sports analogies.
For example, he did one segment where he compared NFL quarterbacks to [thanksgiving foods](https://www.youtube.com/watch?v=d4UWDXjnoDM), and another where he compared them to [Hollywood actors](https://www.youtube.com/watch?v=KLvBnxTwOE4).
I find these videos incredibly entertaining: they're funny and for some reason his comparisons usually seem pretty spot-on to me.
In this blog post, I'll take my shot at comparing NBA players to programming languages.

Please don't take these too seriously. I'm just having fun.

## Kevin Durant: Python [^1]

Kevin Durant is considered the most "malleable" superstar in the NBA by both [fans](https://www.reddit.com/r/nba/comments/11ynutt/kd_is_definitely_the_most_plug_and_play_superstar/) and [media](https://www.theringer.com/nba/2023/4/25/23696667/kevin-durant-phoenix-suns-basketball-nomad).
This means you can instantly plug him in to any team, and he will mesh well with that team.

I think the main reason for is that he doesn't dominate the ball compared to similar superstars.
Let's compare him with arguably two very similar superstars, at least height and position-wise: Luka Dončić and Lebron James.
I [calculated](https://www.nba.com/stats/players/touches?PerMode=PerGame&Season=2020-21&dir=D&sort=TOUCHES) each player's "Touch %": the percentage of time that player spends touching the ball while they are on court.[^2]
There are 10 players on the court at a time, so the "average" NBA player would be about 10%.
I also compared their points per 48 minutes.
If we estimate the average NBA team scores about 110 points per game, then you would expect the "average" player to score about 22 points per 48 minutes.
The following numbers are for the 2020-2021 season:

| Player       | Touch%           | Points Per 48 Minutes             |
|--------------|------------------|----------------------------|
| Kevin Durant | **10.8%**        | **39**                         |
| Luka Doncic  | 26.1%            | 38.8                       |
| Lebron James | 19.1%            | 35.9                       |

KD was able to score more points than Lebron or Luka while touching the ball for significantly less time.
This isn't all that surprising to anyone who's watched these three play: you rarely see Kevin Durant taking a million dribbles to size up his defender: he usually gets the ball, makes a quick move, and then either passes or shoots it.
His game just doesn't require him to have the ball as much as other superstars.

He's also a excellent shooter, so he doesn't mess with your spacing (compared to Giannis Antetekounpo, whose lack of shooting has forced his 7'1'' teammate Brook Lopez to become a 3 point shooter).
And he's also good enough defender, so his teams don't have to shift defensive assignments to cover for his deficiencies (which the Warriors arguably have to do for Steph Curry).

When your team has Kevin Durant, you don't have to give him the ball all the time, he doesn't mess up your spacing, and you don't have to shift around your defensive assignments: you can insert him anywhere and he'll score at a near league-leading rate.

Python has some similar qualities:
1. Its syntax is similar to natural language, making it more intuitive to people without programming experience.
So, just like you can drop Kevin Durant into any situation and he can immediately help your team, it is pretty easy to learn Python and immediately start coding (even if you don't have coding experience).
2. Furthermore, there are a bunch of libraries in Python libraries (and resources for learning the language) that can help you accomplish whatever task you're working on.
This is one of the reasons I personally have found it easier to quickly hack something up in Python and get things working compared to other languages.
3. There's also a sense in which certain constructs in the language itself are malleable.
Just like Kevin Durant can be an elite scorer when dropped into different situations, Python's dynamic typing means the same variable can be used effectively when dropped into different situations (for example, as an operand to floating point addition and then later being concatenated to a string).

Also, when Kevin Durant left OKC for Golden State, there were lots of memes about him being a [snake](https://www.youtube.com/watch?v=CfgHeIpMfMc) for betraying OKC.
Kevin the Snake being compared to the *Python* programming language?
That's is the cherry on top.

## Some Other Comparisons

### Kobe Bryant: C
Kobe Bryant was known for a few things:
1. His competitiveness and work ethic. There are a couple of stories from Netflix's [Redeem Team Documentary](https://www.netflix.com/title/81452996)

2.

#### Steph Curry: Rust

[^1]: This is my favorite comparison, and the main inspiration for this blog post.

[^2]: You can calculate this by doing [(number of touches per game times seconds per touch)/minutes per game].
