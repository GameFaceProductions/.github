<img align="center" alt="GameFace" src="https://avatars.githubusercontent.com/u/114511820?s=200&v=4">

# Proposal:
GameFace is a social media platform that allows gamers to connect with other gamers in order to enhance their gaming experience. GameFace users are able to create and personalize their profile based on experience level, play style, and platform of choice. Additionally, GameFace users can connect with other users through posts, likes, comments, and highlights. GameFace gives users the ability to find gaming partners based on games played, region, skill, and play style. Ultimately, GameFace is a networking solution that allows users to connect and grow as gamers in a safe and inclusive environment.

# API’s: 
RAWG’s Video Game Database
Youtube (potentially)
GameFace API (our database)
TalkJS API (potentially)


# GameFace Main Stories / Features
#STORIES
#Visitor Story
As a VISITOR I can view the landing page that has a link to register and login (navbar shows basically nothing)

# Login Story
As a USER I can login and be directed to the home page

# Profile Page Story
As a USER I can change my password on profile page
As a USER I can customize my profile 
As a USER I can add an avatar
As a USER I can add gamertags / platform names
As a USER I edit my game list (add, remove)
As a USER I can add info for each game (play style, skill, time played, region)
As a USER I can upload clips / screenshots of my gameplay to the highlights section of my profile


# Post Story
As a USER I can add posts to my profile.
As a USER I can edit my own posts.
As a USER I can delete my own posts.
As a USER I can see my own posts on my profile.
As a USER I can see other user’s posts on their profile.
As a USER I can see all posts on the home feed.
As a USER I can like another user’s posts.
As a USER I can comment on another user’s posts.

# Clip/Screenshot Story
As a USER I can add clips / screenshots to my profile.
As a USER I can edit clip / screenshot captions.
As a USER I can delete clips / screenshots.
As a USER I can see my own clips / screenshots on my profile.
As a USER I can see other user’s clips / screenshots on their profile.
As a USER I can see one featured clip on the home page.
As a USER I can like another user’s clips / screenshots.
As a USER I can comment on another user's clips / screenshots.

# Search Users Story
As a USER I can search for other users and see a list of names.
As a USER I can click a search result and be directed to that users profile.

# Search Games Story
As a USER I can search for games by name and get back matched from RAWG API.
As a USER I can click a search result and be directed to that games info page.
Game Info Page Story
As a USER I can add a game to my profile game list.
As a USER I can remove a game from my profile game list.
As a USER I can click a link to a store page for that game.
As a USER I can see some info about the game (game description).

# Friends Story
As a USER I can add other users as friends through their profile.
As a USER I can report other users.
As a USER I can message other users.

# Admin Story
As an ADMIN I can do anything a user can do.
As an ADMIN I can block  users.
As an ADMIN I can hide / block any posts.
As an ADMIN I can hide / block any comments.




# EXTRAS Story
As a USER I can direct message other users (stretch, own set of user stories)
As a USER if I forget password I can click a link on login page to reset
As a USER my review rank is displayed (happy face + sad face counter)
As a USER a I can review other users I’ve matched with (happy face + sad face counter instead of 5 star rating)
As a USER I can block other users
FEATURES

# Visitor Page Features
Can only see landing page (register option)

# Home Page Features
One randomly selected feature highlight (screenshot / clip )
Feed section showing ALL users posts with like and comment
Profile overview in top left that goes to profile
Dev list game recommendations
Avatar profile link in top right navbar
Search button (users, games)
Logo in top left that goes to about page

# Profile Page Features
Favorite games list with add games button (link to the search games view for adding games based on search)
Edit / change account information button (goes to account details view)
Add, edit, delete posts 
Add, edit delete clips(video) and their captions
Add, edit, delete screenshots and their captions
Edit bio button (modal)
Edit gamertag button (modal)
Add  friend button 
Friends list
Add / edit backdrop button 
DM (talkJS, if too difficult basic inbox dm)
Search button (users, games)
Home button top left links to home page
Avatar button top right links to profile page

# Search Games Features
Add games that are searched for (on the game info view)

# Search Users Features
Type users name and get back result of user profiles
Link to that users profile 

# On Another User’s Profile Features
Like, comment on posts
Follow users
Report

# EXTRAS Features
Marketplace for merch and NFT’s
Multiple gamertags
Group chat
Online status
Matchmaking
Twitch API for pulling users who are content creators (officially recognized by ADMIN role)



# Classes:
Roles
Users [many many user_platforms] [many many user_games]
Posts 
GameClips 
Platform [many many user_platforms]
Games [many many user_games]
Posts_comments
Post_likes
Clips_comments
Clips_likes

# Controllers:
Users
Posts
GameClips
PostsComments & ClipsComments (to respective endpoints)
Views
UserGames

# Repositories: 
Users
Posts
GameClips
PostsComments & ClipsComments (to respective endpoints)
Views
UserGames








