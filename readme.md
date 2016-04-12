#Rec Softball

##User Personas

####Brett Davis
- Level: Played baseball in high school
- Works in sales for a tech startup
- Has a family
- Has an iPhone, iPad, and MacBook Pro
- Other apps on his phone: Slack, Duolingo, BBC News, Flappy Bird
- Reads Fast Company, Techcrunch, and Venture Beat
- Works long hours, wants to be able to manage team efficiently and mobily. Sends out updates during lunch and often checking latest league/team updates at stoplights on the way to practices/games.
- Competitive and cares deeply about individual and team stats. Needs way to track his team's ranking against others.

###Ashley Nolan
- Level: Novice having fun
- Works as a waitress at a local restaurant
- Single and living with roomates
- Has an Android phone
- Other apps on her phone: Spotify, Snapchat, Tumblr, Tracksmart Scheduling
- Last website visited was Pitchfork
- Works weekends, but can check phone on breaks. Needs to know as soon as possible about changes and then quickly pass updates to team members. Leaving for games from work in most cases.
- Doesn't fully understand how to track stats yet, needs easy way to learn

###Jane Perkins
- Level: Enthusiast with few other hobbies
- Works as a nurse
- Living with girlfriend
- Has an iPhone and HP ultrabook
- Other apps on her phone: NPR, Apple Music, Facebook
- Reads NPR, Vice, Nautilus
- Has a rookie team and wants to teach them more about the sport. Wants to be able to share tips and tricks to team members.
- Wants to receive confirmation when team has received updates

##User Story: Finding Schedule Changes and Notifying Team

1. User opens app
2. User sees schedule change
3. User notifies team

###1. User opens app
The user opens the app because of a push notification on their phone alerting them to league schedule changes (rain outs, etc). Tapping the notification takes the user directly to where the scheduling info appears in the app.

###2. User sees schedule change
The app displays the information about the schedule change (ie whether the game will be played in a different location or at a different time) and allows users to confirm they have seen the update and also contact the league commissioners. The CTA will direct them to notify their team members.

###3. User notifies team
Following the CTA takes users to a default message containing the most important details of the update. The user can then add more information if desired or just tap send and be done. The team member's information is stored in a directory in the app, so the message is sent as texts or emails to them.

##User Scenario: Flow
Brett Davis is sitting at a stoplight on his way back from lunch. He's going straight to a meeting with his boss, and he's already running late. The meeting will last up until he leaves for his game tonight, and he won't be able to check his phone during the meeting. He gets a notification that there is a league update. He taps the notification and is taken directly to a page with the information that the game is canceled due to a sinkhole around home plate. Brett notifies team with the default message and is done with the app before the light has turned green.
- notification
- info
- send update to team

**3 taps and he's done using the app**

##User Scenario: Feature
Jane Perkins wants to schedule a new practice, but she only wants pitchers and catchers to be there (they need some work). She needs to be able to notify only some of the team, specifically the pitchers and catchers. The app has a feature which allows users to create groups in from their player directory and select those groups to receive updates.

Jane Perkins wants to share a video she found on pitching. The app has a wall/feed/channel for this and Jane can alert ONLY pitchers by selecting their groups to receive the notification from the channel (Slack style).

##Inspiration Apps

###Snapchat 
[app page](https://itunes.apple.com/us/app/snapchat/id447188370?mt=8)
**The Good**
- Easy
    + There aren't many options
    + The options you want are there immediately and happen fast
    + The thumb stays in the easy flow zone
    + slide in and out of main screens
- Sharing is fast and user-friendly
    + If the user has an update to share, they can choose whether to add text, filters, and draw on the photo, but they are never far removed from simply sharing it, and the other options don't get in the way
    + Easy to select groups and single other users to share to

**The Bad**
- This app basically does one thing really well, so for a multi-functional app like mine, it's not totally analogous.

###GameChanger
[app page](https://itunes.apple.com/us/app/gamechanger-baseball-softball/id318906314?mt=8)
**The Good**
- Uses prompts super well
- The user is given a list of options that have them merely asking questions instead of having to know what's going in terms of the scorebook
- Separates stats display into Batting, Pitching, and Fielding
- Allows users to play a demo game without signing up

**The Bad**
- There's too much going on for it to be how I'll track stats with my app. It's a stats app for baseball, not a team management app with stats built in.

###Team Snap
[app page](https://itunes.apple.com/us/app/teamsnap-sports-team-management/id393048976?mt=8)
**The Good**
- Gives users prompts and feedback at every interaction
- Movement makes sense (left to right)
- The main page is a comprehensive menu -- it's easy to find where you need to be to do what you want to with the app. Nothing goes very deep.

**The Bad**
- Requires you to confirm email before you can use app
- Email prompts you to set everything up from web app
- Tons of questions to get started















