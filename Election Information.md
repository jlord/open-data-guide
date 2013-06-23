#Engage the Community  

What are the existing requests for data and information?
Your county or state board of elections might be able to tell you what kinds of questions they receive in the run up to the election.  Often these questions center around the location of a polling place, filing an absentee ballot request, registering to vote, and information about who is on the ballot.

Solicit feedback from the community.
There are a number of civic companies that ingest information about elections and serve it up to users through different platforms.  You may want to reach out to TurboVote, the Federal Voter Assistance Project, or Rock the Vote.

#Find your Data
You should locate the office or department that is responsible for running elections in your jurisdiction. Most often this is the county clerk's office; although, in some states the elections are run by the Secretary of State's office. At the very least, the Secretary of State's office can tell you who owns the data you need. 
##Review your data for accuracy
You really don't want to publish inaccurate election information.  People get angry.  Make sure you have the connonical source of the election data you want to publish.  Think about how you will keep this data up-to-date.  Who will be responsible for generating data exports and publishing them when data changes.  
##Review your data for coverage/completeness
It's possible to publish election related data without complete coverage, but it makes the data less useful and will reduce the willingness of the community to work with it.  If you choose to publish incomplete data, make sure you identify the gaps and help the community understand where those gaps exist.
  
#Decide how to format your Data
##Is there a Standard?
### Yes! There are a few standards
*[The Election Markup Language (EML)](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=election) - EML is a data standard designed to facilitate the structured interchange of data among hardware, software and service vendors who provide election systems and services.  While it’s very flexible, and is global, it has seen little adoption in the United States. 

*[The Voting Information Project (VIP)] (https://votinginfoproject.org/) - VIP is designed for US jurisdictions and 30 states have adpoted VIP as of November 2012.  
### Which standard should I use?
This might be another great opportunity to engage your community.  Do the developers you're interested in supporting prefer one standard over the other?  Of the many different ways this data can be surfaced to users, which are the most popular and what standard do they ingest.  Often tools and platforms will be able to ingest more than one data standard especially if there is more than one popular standard.  If you're a US jurisdiction, you most likely should use the VIP format.  If you're an international jurisdiction, EML is probably your best option.
### Is there a valadator?
Most open data projects with funding to support them have written symantic and syntactic checkers.  Before publishing your data, you might want to check to make sure you've successfully transformed it into the data standard you are attempting to publish.

#Decide how to deliver your Data
## Insert Dylan's API ect.

#Publish your Data
If you would like specific organizations to ingest your data into their own APIs, you should let them know where you've placed your data.  The Google Civic Information API returns election information published in the VIP format.  You can notify them of your published data at https://votinginfoproject.org/contact.


#Engage your Community

