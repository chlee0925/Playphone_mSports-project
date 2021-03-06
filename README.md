# Playphone mSports Project
This repository (and Github page) is to illustrate my work during my one-year internship at Playphone, Inc. The original git repository where I contributed actual codes is private and inaccessible. Hence I attempt to highlight my work using this separate repository.

# What is mSports?
<img src="https://raw.githubusercontent.com/chlee0925/Playphone_mSports-project/master/msports-main.png" width="60%">

#### mSports is a mobile competitive gaming platform. 
Try [here](https://msports.games).
It was inspired by competitive gaming sports in PC and it aims to offer delightful challenges to mobile gamers.

# Technology used
* Micro-service Backend: Java (with Spring Framework), Cassandra, MySQL, RabbitMQ, Apache Solr
* Frontend: Javascript/TypeScript (Angular Framework 1/2), HTML, CSS

# What did I do?
I mainly worked on backend services of the platform and I made some small contributions to the frontend Angular app as well. Because the project was in a very early stage when I joined, I started from database schema design for most of tasks. I had much fun with all the technology stack. 

# My contribution highlights
1. Tournament Management
2. Video Advertisement, Offerwall
3. User Redemption
4. User Engagement

### Tournament Management
<img src="https://raw.githubusercontent.com/chlee0925/Playphone_mSports-project/master/msports-gameplay.png" width="30%"> <img src="https://raw.githubusercontent.com/chlee0925/Playphone_mSports-project/master/matchmaking-leaderboard.png" width="30%"> <img src="https://raw.githubusercontent.com/chlee0925/Playphone_mSports-project/master/se-tournament.png" width="30%">

I jointly worked on backend tournament management features that include:
- Posting game scores
- Match-making (seeding) round leaderboard
- Player seeding (based on relative strength and randomness)
- Single-elimination tournament management (round progression)
- Bot features

### Video Advertisement and Offerwall
<img src="https://raw.githubusercontent.com/chlee0925/Playphone_mSports-project/master/video-ad.png" width="70%">

I integrated a third-party video advertisement network / offerwall service into the platform. More specifically:
- Fetching VAST-formatted video ad data
- Integrating VAST-compliant video player
- Schema design and Collecting ad performance data for future analysis
- Fetching offerwall items and handling completion callbacks

### User Redemption
<img src="https://raw.githubusercontent.com/chlee0925/Playphone_mSports-project/master/user-redemption.png" width="70%">

I worked on backend user redemption features including:
- Designing database models to record all relevant data for financial accountability and transparency. It also helped to deal with any network/system discruption.
- Integrating a third-party redemption service with the platform.
- Building a frontend admin dashboard (in AngularJS) to view, approve or reject user redemption requests.

### User engagement
I integrated a third-party user engagement service for user tracking, analysis, and engagement. This allowed the internal team to identify users who needed attention and to conduct email campaigns to boost the user retention.
