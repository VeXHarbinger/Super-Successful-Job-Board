# The Super Successful Job Board

## Purpose

This is a simple exercise in identifying what's wrong with the popular job boards and seeing how easy it is to create an AI coded solution to resolve it.  Maybe it'll get coded all the way to the finish line, maybe not. It'll at least feel good to be a productive and a venue to voice some complaints about the systems in place.  

I feel that the main issue with all of the main boards available today is that they are focused on just listing jobs from any resource and there is little consideration given to its primary purpose, which is to connect applicants to employers.  This focus on quantities of listings and network building hinders more than it helps, it's the wrong paradigm. This system\service should be disposable.  Meaning you interact with it when you need an employer or employee and, once you have that you stop using it. That will resolve the noise and clutter blocking folks from accomplishing these goals.

## Projects Outline & Goals

This is the components that make the application as a whole and the goals it would strive to accomplish.  These aspects of the ReadMe should diminish overtime as they are incorporated and then moved into a typical user story methodology.  
This section is basically our commandments or core building blocks as to what needs to be done to accomplish this efficiently.  This document has been started from the point of view of a developer who is looking for work and needs to evolve into what other roles require to achieve this task efficiently.

## Community

As stated above there should be no community components to it.  It's easy enough to create a channel these days to consume the aggregator of your choice like [BlueSky](https://bsky.app/) or [mastodon](https://mastodon.social/) which is portable.  Folks can even stay in [LinkedIn](https://www.linkedin.com/) for those aspects in they so desire.  It should contain human and corporation profiles and retain them to a degree.  However, the goal should be to solve an employment task and not encourage extended use for other revenue streams.

## Job Postings

This is the primary purpose of this project. To post a JD and get application submissions.  To do that in a paradigm that is focused specifically on doing this task, the following aspects of a posting should be applied.

* A job posting should go stale (be delisted) after 9 days of poster inactivity.  If a poster isn't interacting with applicant submissions in this time well, then they really aren't serious about hiring or already have.
  * The poster can interact with the system and mark applications to be emailed or exported as desired, or whatever the common method maybe, but the goal is to require interaction.
  * It can always re-list it afterwards if needed or none of the interviews resulted in a desired candidate.
* Listings should also track if applicants are actually being interviewed, this type of data can help to reduce ghost jobs which the govt tries to track but doesn't have enough data to do so efficiently.  
* Listings should have preset text components/blocks that the employer can add to the listing such as but not limited to; About us, Job Description and Requirements. This will allow multiple goals to be accomplished in streamlining the process. Here are some reasoning examples;
  * **About Us**, allows for a singular text block to be created as part of the company profile for reusability while keeping it brief.  A lengthier corporate description can be a part of the corporate profile.  This will help keep listings more precise and to the point.
  * **Requirements**, as in knowledge or skills, should be selectable from a normalized list. There are too many variations in naming of an item. (i.e. .Net Core, DotNetCore, .NetCore) which just feed into having to list this items in multiple ways in a CV to avoid AI gateways.
* Listings should display the initial date posted.
* Listings should not display the number of applicants applied, as it serves no purpose.

## Companies\Corporate Profiles

* A Corporate profile is required.  It can display all of the typical associated data, URL, Logo, About Us, Associated Social Links, etc.
* A Corporate profile should be able to identify all domains associated with it outside of the displayed data for allowing granular security.
  * This way a job listing can have multiple authors while final approval\posting remaining in HRs hands.
  
## Users

* A user profile is required.
* A user profile should offer a methodology to verify their identity like LinkedIn does with CLEAR, so that other parties will not ask for PII like a copy of a driver’s license or digits of an SSN.  HR will receive all that data upon hiring.
* A user profile should allow for a methodology of recording professional reference statements by confirmed sources.  Meaning that the professional interaction is confirmed.
  * Confirmed in this context could mean submitted using a corporate email address. This reference story could be followed up by a company upon hiring if desired, the goal here is to eliminate asking for professional references during the application process.
* Things such as citizenship, visa status, disabilities should be recorded as part of the user profile (not displayed) to reduce the redundancy of having to answer this per application request.
  
### User Applications

* During the process the user should be able to indicate if they wish to auto submit related data like Location, Employment status, Disabilities, phone number, email, etc.. on a case-by-case basis or just apply all. This will reduce redundant tasks while still making it their decision as to which PII to utilize.
* During the submission they can indicate which professional reference stories (Selected, All, None) can be visible to the employer.  

## Job Searching Capabilities

* Should offer standard search options such as by City, state, radius, on-site, remote, etc..
* A skill name to be used in a search should be auto suggested as typed to help enforce naming standardizations.
* You should be able to filter out listings by
  * Multiple company names.
  * Visa statuses or requirements
* Offer fields for both positive and negative search prompts. So, you can search by skill or title and remove listings with a different skill. (i.e. Search for "Web Developer" listings but remove listings with Java)
