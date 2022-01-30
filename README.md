# Project Proposal
A webapp where you go to review games, talk about nerfs, buffs, updates, and all things gameplay.

### Project Title
Ranked

### What and Why?
**Why:** 
- Big game studios keep pumping out the same games with a different name (Call of Duty, anything EA sports, etc.), we should directly be able to keep them accountable 
- It is already difficult for some players to get their opinions heard by studios, but now that they're getting bought up and centralized (as evidenced by the Activision-Blizzard acquisition) we need somewhere to aggregate our thoughts
- Reddit is slowly going downhill since it announced its IPO, what other forum site is there that you can discuss and get a (somewhat) census on how people feel about balance changes/updates?
- This reason is a maybe, but I think it's cool: If you are serious about competitive gameplay, the current resources to help you in climbing ranks are lackluster. Ranked could essentially be a public, free, user-supplied resource to help you improve
 
**What:**

In blunt terms, my proposal is to create a forum site similar to Reddit except it is entirely centered around games. We would manually create megathreads for every game we see fit, then would do some sentiment analysis on each post to guesstimate how happy people are with the game and post that at the top of the megathread.
However there is also a serious question of survivor-bias, since only people who are unhappy with the current state of the meta are likely to speak up. That is an issue I don't know how to solve yet. Reddit is an echo chamber, hopefully this would not be the same.
In each megathread, there would probably also be a way to segment Balance Change Updates from Discussion posts from Angry reviews from any type of post. Probably a tag system.
We would also try to stay on top of important game update news and display it in an organized way on top of each megathread.
Finally, I think the network effect would be much more powerful on Ranked than other social media platforms since it could end up being bad for new games if they don't have a megathread on our site for people to talk about them, which would give us a path to profitability without selling out. 

### For Whom?
The software would be for anybody that plays games (Valorant, Call of Duty, League, whatever game is on our site). I hope this isn't too vague, but I guess if we needed to niche down in the beginning, it would be to target more invested players or those who watch esports.

### How?
I think I might've explained this section in the **"What"** section above, but to continue it- if I was the user, I'd be able to:
- Find my favorite games and see what people are saying/thinking about them
- Post angry updates when my favorite character gets nerfed 
- Comment on people's posts telling them buffing the strongest character is stupid
- Post map ideas or balance change ideas that I think can improve the game
- Post memes or something funny about it
- *maybe- this might be too hard* Post a clip of my gameplay and ask pros/people that are actually good what I could've done better in that clip

Another cool idea could be that our system compiles individual megathread ratings over the course of a month, then sends an automated email to the game company/studio saying "Hey, my users like your game 10% less this month, whatever you did be careful, it's not looking good" or something.

### Scope
At the end of the day, this is a forum web app. We're making:
- A user auth system (if we can use existing api's this should be ok)
- Megathreads (just where all posts related to 1 game are housed), Posts, Users, Comments, Tags, probably Likes and Dislikes
- Posts need to be able to support images
- For added difficulty we could incorporate video handling in Posts as well
- For more added difficulty, we could try to see if famous games have API's where we could sign in and get their account info. Thus enabling us to "verify" users as being Top 500 or whatever rank they say they are.