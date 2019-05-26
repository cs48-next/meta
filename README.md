# Project summary
## One-sentence description
Crowd-controlled venue DJ system where users can suggest, vote for, or skip songs.
## Project overview
A voting-based system to determine the next song(s) to play enables
the crowd to control what they listen to; the most popular song (desired
by the most people) will always be played. Additionally, a skip feature can
enable users to vote to skip the current song being played. Some venues
may want to limit the type of music being played, e.g. a middle school
dance would likely only want non-explicit songs to be played. Users of
the app, not only enterprise/business partners can host their own ad-hoc
"venues" where other users can connect and vote on the next few songs.
Hosts can choose the threshold for number of votes required to skip the
current song and/or queue the next song. In certain cases, the host can
grant permission to only a handful of specific users to vote or select the
next song. A scoring system will reward users for consistently suggesting
songs that have been selected by voters or punish users for selecting songs
that are frequently skipped, in the form of cosmetic flairs. A scoreboard
will serve as a means of comparing user contributions and keep users engaged and motivated in the service. Per-venue statistics exposed to the
host after an event will allow the host to get insightful data about the music played and the engagement of the audience.
# Components
## [facilitator](https://github.com/cs48-next/facilitator)
Facilitates interaction between clients and venues.
## [frontend](https://github.com/cs48-next/frontend)
Connects with music player API to enumerate songs and sends vote/skip requests to facilitator.
# Installation
See installation details in each of the above repositories.
# License
[Apache License 2.0](LICENSE)
<!---
Add a README.md file. It must have the following headings that you will fill in as you develop your project: 
"Project summary" with subsections "One-sentence description" and "Project overview" with 1-2 paragraphs of project specifics 
"Installation" with subsections "Prerequisites" and "Installation Steps" 
"Functionality and Known Issues" 
"License" -- add details here on your choice of license and a link to your LICENSE file.
-->
