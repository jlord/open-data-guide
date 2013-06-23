---
title: "transit"
layout: default
group: "navigation"
---

#1 Engage the community

Engage the community to determine why and how to open your transit data.

Find out what the people want to know - this can help figure out where to start
Examples of things people want to know with transit data:

* When is the next bus/train? 
* Where is the closest stop/station? 
* How do I get from here to there using transit? 

Get to know the development community, and determine example uses of the data/api.

* Do they need shape files?
* Do they need real time bus/train info?

#2 Find the data
##Where should I look?
The best place to start would probably be with your transportation board.

##Do they not have it?
It may be that the data you want to open is actually housed with a non-government agency. You may want to: 

* look into potential partnerships
* see if they already have an api that you can mirror/integrate


#3 Decide how to format your data.
If you use a standard format, you benefit from all the work that others have done integrating and tooling that standard. This can lead to cost savings in developing documentation, reduced support issues and increased adoption. In general, if there is a standard, the default should be to develop to it.

## Is there a standard for transit data?
    
*Yes!*
In fact, there are probably several... 
_(the following is shamlessly cribbed from [smarter people](http://transportation-camp-dc-2013.wikispaces.com/Transit+Data+Standards))_

- [GTFS](https://developers.google.com/transit/gtfs) - The General Transit Feed Specification, originally developed by Google, contains static schedule information for transit agencies including: stop locations, route geometries and stop times;
- [GTFS-realtime](https://developers.google.com/transit/gtfs-realtime/) - GTFS-realtime contains real-time information related to vehicle positions, service alerts and trip updates (delays, cancellations, etc.);
- [SIRI](http://www.kizoom.com/standards/siri/) - The Service Interface for Real Time Information is a real-time data standard predominant in Europe, but making significant inroads into the US market, notably at MTA in New York. Recent change proposals to the SIRI standard include the definition of a structure for SIRI web services;
- [TCIP](http://www.aptatcip.com/) - The Transit Communications Interface Protocol is an APTA standard, sponsored by the US DOT. It has components which deal with passenger information and scheduling, as well as a whole host of other business divisions in transit;
- [NextBus](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) - A number of transit agencies employ the NextBus XML API to deliver real-time arrival information. While this standard is not as extensive as others, it still deserves mention on this list.

##Which one should I use?
Anecdotally, in the US in particular, GTFS seems to be the standard for all things not realtime. For realtime updates there is a split with many using GTFS realtime, some using NextBus and some using SIRI. TCIP does not seem to be represented in any well used open transit data example.

Transforming your data to these standards can be done using various methods of [ETL]({{ site.root }}/general/etl/).

Outside of these standards there is often the ability to serialize to several [formats]({{ site.root }}/general/formats/). Check [here]({{ site.root }}/general/formats/) for more discussion on choosing a serialized format.


#3 Decide how to deliver your Data

* API
A great default would be to try to release the data as an API.
In particular, if you will be offering any real-time data that would have to happen over an API and not any kind of bulk file-based release. 

* File Download
This solution will not work for anything realtime. However, it is a much simpler release of non-realtime GTFS data. If you aren't releasing real time data at this time, this will be easier than developing a full API for the GTFS data.

More information on the [delivery methods]({{ site.root }}/general/delivery) and [api protocols]({{ site.root }}/general/api_protocols/). 



#5 Release it!
Release the data/api. 
Make sure that it is [properly documented]({{ site.root }}/general/documentation/) to that people can use it. 
Talk to the community to make sure that they understand what has been release and that they know that it is actually out.

Celebrate!

#next steps:
##Reengage the community!
##consume your own data/api
It should always be a goal to use the api/data internally. More info on why is [here]({{ site.root }}/general/dogfood/)

----------

#is this becoming hugely painful?
##Can't find the data?
This is probably a good time to reevaluate what the costs/benefits are and make sure that:

* it's _possible_ to get the data
* it's _feasible_ to get the data
* it's _cost-effective_ to get the data



