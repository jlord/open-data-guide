---
title: "election information"
layout: default
permalink: /open-data-guide/election-information/
group: "navigation"
---

# Engage the Community  

What are the existing requests for data and information?
Your county or state board of elections might be able to tell you what kinds of questions they receive in the run up to the election.  Often these questions center around the location of a polling place, filing an absentee ballot request, registering to vote, and information about who is on the ballot.

Solicit feedback from the community.
There are a number of civic companies that ingest information about elections and serve it up to users through different platforms.  You may want to reach out to TurboVote, the Federal Voter Assistance Project, or Rock the Vote.

# Find your Data
You should locate the office or department that is responsible for running elections in your jurisdiction. Most often this is the county clerk's office; although, in some states the elections are run by the Secretary of State's office. At the very least, the Secretary of State's office can tell you who owns the data you need. 
## Review your data for accuracy
You really don't want to publish inaccurate election information.  People get angry.  Make sure you have the connonical source of the election data you want to publish.  Think about how you will keep this data up-to-date.  Who will be responsible for generating data exports and publishing them when data changes.  
## Review your data for coverage/completeness
It's possible to publish election related data without complete coverage, but it makes the data less useful and will reduce the willingness of the community to work with it.  If you choose to publish incomplete data, make sure you identify the gaps and help the community understand where those gaps exist.
  
# Decide how to format your Data
## Is there a Standard?
### Yes! There are a few standards
*[The Election Markup Language (EML)](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=election) - EML is a data standard designed to facilitate the structured interchange of data among hardware, software and service vendors who provide election systems and services.  While it’s very flexible, and is global, it has seen little adoption in the United States. 

*[The Voting Information Project (VIP)] (https://votinginfoproject.org/) - VIP is designed for US jurisdictions and 30 states have adpoted VIP as of November 2012.  
### Which standard should I use?
This might be another great opportunity to engage your community.  Do the developers you're interested in supporting prefer one standard over the other?  Of the many different ways this data can be surfaced to users, which are the most popular and what standard do they ingest.  Often tools and platforms will be able to ingest more than one data standard especially if there is more than one popular standard.  If you're a US jurisdiction, you most likely should use the VIP format.  If you're an international jurisdiction, EML is probably your best option.
### Is there a valadator?
Most open data projects with funding to support them have written symantic and syntactic checkers.  Before publishing your data, you might want to check to make sure you've successfully transformed it into the data standard you are attempting to publish.

#Decide how to deliver your Data

##File downloads
 This delivery method is good for data that does not change often or is historical data bundled into discrete snapshots. This might be an appropriate method for publishing historical election results, however polling place and election results information changes so often, another delivery method might be the most appropriate. Options include:  
 * 3rd party 'data commons' sites
 * FTP (and variants)
 * BitTorrent

## API
 This is best for real-time data.  The Voting Information Project will ingest your flat data and return it for you saving you the trouble of building your own API.

## Data Portal
 Can wrap either an API, a set of file downloads, or both.

#Publish your Data
If you would like specific organizations to ingest your data into their own APIs, you should let them know where you've placed your data.  The Google Civic Information API returns election information published in the VIP format.  You can notify them of your published data at https://votinginfoproject.org/contact.

# Eating your own dogfood.

Once an api has been opened, that API should be used internally for all access to that information. 

* find the flaws in the API design
* align values of the consumer and producer of the data
* ensure that the API itself is maintained and supported

One easiy way of consuming the election data you publish is by making sure any internal polling place locator, ballot information locator or election results displays are built using the data you publish.

# Engage your Community
Make sure you provide a way for developers and community members to submit feedback and error reports to you.  This can be as simple as creting and publicizing an email address.