Happy National Day of Civic Hacking 2015! The official national website for today is http://hackforchange.org/ and keep up on Twitter at [#hackforchange](https://twitter.com/hashtag/hackforchange).

# Challenges

## Introduction to OpenStreetMap

National Challenge: http://hackforchange.org/challenges/introduction-to-openstreetmap/

> By following LearnOSM, the step-by-step guide to contributing and using OpenStreetMap, you can empower your community to start being an active contributor to how we get places on the map.

This is a challenge that the non-technical among us can take on. You'll learn how to contribute to OSM and about how online mapping works in this day & age. Please be prepared to share what you learned in the final session and put any notes that others may find useful (resource links, tips, etc) in this wiki.


## City SDK Data Solutions Challenge

National Challenge: http://hackforchange.org/challenges/citysdk/

> Can you create an application leveraging the U.S. Census Bureau’s City SDK that addresses an integrated sustainability problem in your city? Integrated sustainability problems may include a mix of economic, environmental, social, cultural, and housing themes.

Mash up census data with local data from the [South Bend Data Portal](https://data.southbendin.gov/) to solve some problem. Use what you find to power a visualization, application, etc and be prepared to share your experiences with the group. Collaborate with others to make sense of what you're seeing.


## Two Factor Frenzy

National Challenge: http://hackforchange.org/challenges/two-factor-frenzy/

> This challenge calls for a tool (e.g., website, app, game) designed to show users which sites currently offer multi-factor authentication (MFA), with information tailored to them based on their online habits.

Collaborate with others to create some app/site/game/infographic/etc that teaches people about MFA, which services offer it & which are lagging behind. Even if you just have plans at the end of the day, be prepared to share your ideas. Who knows, there may be others who will want to pursue this after the event!


## Trees in City Parks

Local Challenge: https://github.com/HackMichiana/tree-hugger-server

> Work on an application that will allow the crowd-sourcing of trees in our city parks. This information will help the Parks Department with the management of the City of South Bend's mature trees.

This is a local project currently in progress. Help us crank out version 1.0 of the webapp & server-side components. At the end of the day we hope to put this in the "Win" column with a plan to expand features over time!


## Art Finder

Local Redeployment: http://www.codeforamerica.org/apps/public-art-finder/

> Public Art Finder helps users find public art through a mobile, map-based UI allowing them to view additional background information on individual artworks.
 
This is an existing application currently deployed in 5 cities. We would like to bring it to South Bend. We have been in contact with the original developers and they have informed us that there is some work to be done to bring it up to date with the latest versions of CouchDB. Here is some information to point us in the right direction:

> Technical version: I've recently run into problems getting the current Art Finder code up an running. It appears that the one geo-spatial query in the app doesn't work on the current version of Iriscouch. Honestly, I've been out of the couchdb/iriscouch world for the last couple of years, so I'm not 100% sure what's going on there.
>
> Non-technical version: The Art Finder project, when I stopped paying attention to it, was a decent front end on top of a CouchDB powered backend. This decision was made because there was a free CouchDB hosting service (Iriscouch) which made launching new instances of Art Finder really easy.  In the time since then, CouchDB has evolved into a slightly different beast (one to which I am only a novice) and it's broken a piece of the app.
>
> What does this all mean? In order to deploy Art Finder, someone needs to figure out 1) how bounding-box geospatial queries are handled on the version of geocouch that Iriscouch runs & 2) update this line of code with the answer to #1.  Another option would be to modify the app so it calls a different url to get the pieces of art that should be on the map.

At the end of the day we need the following questions answered:

* How to fix the CouchDB compatibility issues & contribute the code back?
* What are the hosting requirements?
* How can data be entered & maintained?
* How can we apply local branding to the front-end?
* A starting list of local public art to put in the app.

If all these questions can be answered at the end of the day, that would be a great start. Even better would be to have the issues fixed and a working version for South Bend that is ready to be hosted and populated with local data.


## Code for Kids

Local Challenge

> How teachers, parents, and educators can work together to introduce simple and complex computer-programming skills into school curricula.


## Clean Communities

Local Challenge

> How to be part of creating a resource network that matches volunteers willing to shovel snow and mow grass with elderly and disabled residents.
