Repo: https://github.com/HackMichiana/adopt-a-lot-southbend

# Overview

The Adopt-a-Lot South Bend has been around for a while now. It was one of the primary projects of the National Day of Civic Hacking in July 2014 and has been an ongoing point of discussion for Hack Michiana. The basic idea is to create an application to facilitate the organization of volunteers to tend to vacant and abandoned lots in South Bend.

The city of South Bend has many responsibilities, including tending to vacant and abandoned lots, but with limited time, budget and manpower, things obviously need to be prioritized. These untended lots may be an eyesore for their communities, but they are hardly the most pressing issue that SB faces.

This leads to how we can help. Many communities and individuals may be willing help with this problem, but are unsure of what the laws are or how to get started. We have been in contact with the city to understand what citizens legally can and cannot to do. Fortunately for those interested in community betterment, it appears to be within their rights (to an extent) to take matters into their own hands.

This project is an attempt to be a resource for both educating the community and organizing their efforts. There have also been ideas for other issues that can be addressed, but as to whether these ideas fall within this project or should eventually be their own thing is still to be decided.  For the moment, we have a bunch of feature ideas that need to be refined, organized and prioritized before serious effort can be made on a product.

# Proposed Features

Here is a list of features that I (Nathan) can remember that have been brought up. They are listed in no particular order and my hope is that we will break viable ideas into their own sections to be refined. If anyone has an idea that is not on the list, feel free to add it.

* __Legal information__

  Information regarding what volunteers are legally allowed to do.


* __Volunteer Information__

  Information regarding how volunteers should care for a property.

* __Vacant/Abandonded property locations__

  This information is available via [data.southbendin.gov](https://data.southbendin.gov/d/d2un-9vvp?category=Code-Enforcement&view_name=South-Bend-Vacant-and-Abandoned-Properties)


* User registration
  * User model
  * Credential storage (password hashing, etc)
  * External login
    * Facebook
    * Google
    * etc
  * User profile
  * User roles (admin vs volunteer)
* Allow volunteer create a maintenance event for a location
* Allow volunteer to schedule recurring events ("claim a property" for a period of time)
* Email/SMS/Tweet/etc event reminders

* __Event Verification__

  Allow users to upload before and after photos to verify that work was done.


* __User-created content moderation__

  A way to flag and remove the inappropriate content that a user will inevitably create. We may want to implement a publication approval workflow that requires content to be approved by a moderator before it goes public.


* __Organizations__

  There are many community organizations that will be interested in this project. It would be nice if we could get them involved at a higher level than normal volunteers. The idea is that organizations would be vetted and allowed to organize large volunteer events (think a church youth group service project)

  * Registration
  * Approval
  * Members (???)
  * Content moderation capabilities
  * etc


* __Automated data migration__

  The lot list will (should) change over time. We need to decide how to handle the following:
    * Lot removal: do we keep it but mark as removed?
    * New lot
    * Lot info change


* __Expand to needy citizens__

  Allow the "little old ladies" of SB to register themselves to receive assistance. This leads to all kinds of delicate decisions. Can anyone sign up to show up at someone's house? What level of user should be allowed to see these locations? Only approved volunteers? Who approves them? What is the criteria for approval? Likewise for approving "needy" citizens. Are we partially responsible if something goes wrong with the event? Lots of things to figure out.


* __Expand to snow removal__

  When (if) we figure out policies regarding citizen-owned locations another natural service we could organize is shoveling of sidewalks and driveways.


* __Become a resources for service providers__

  Sometimes people are looking for more than occasional volunteers, we could become a resource for local lawncare, snow removal, etc service providers to find interested clients. Viceversa as well, provide a curated list of service providers and volunteer organizations that individuals can contact if they need help.


* Expand to other kinds of maintenance
