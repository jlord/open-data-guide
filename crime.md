---
title: "crime"
layout: default
permalink: /crime/
group: "navigation"
---

# Engage the Community

Crime in the community immediately raises a wide number of local civic concerns. Police agencies frequently meet with communities to address these concerns directly.  Feedback and questions from these events can be used to help determine what data is most in demand by the community.

The community may ask:
* Is my neighborhood safe?
* Where are the trouble spots in my city?
* Has my city been effective at fighting crime?
* How are limited public safety resources allocated in my city?
* Are public safety resources distributed fairly across communities or neighborhoods?

# Find your data

The most detailed information about individual crimes in the community comes from police reports that are created by public safety agencies.  A police report is a description of facts surrounding a crime. The report is used to report who, what, when, where, why and/or how a crime took place. The term "police report" can be used to describe a report filed by a victim or witness of a crime or the preliminary report filed by an officer investigating a crime. These reports are often passed on to other policemen, who may use them as a factual basis for investigating the crime. 

After collecting police reports, law enforcement agencies use electronic standards to aggregate and share data.  Two standards that are in use in the United States are Uniform Crime Reporting (UCR) and the Law Enforcement National Data Exchange (N-Dex).  These two standards are written for different purposes.  UCR has been created for creating a national view of crime.  For the most part, agencies submit crime reports monthly to a centralized crime records facility within their state. N-Dex is intended to be used as a real time intra-agency collaboration platform, and is subject to strict data use requirements. 

UCR data by its nature is much more accessible, and can be used to address concerns over long-term trends in crime. Aggregate UCR data may be accessible through each locality.  Historical data for city and county level crime counts is also available [online](http://www.bjs.gov/ucrdata/). 

There are legitimate concerns that may require access to individual police records.  Someone who is evaluating nursing homes, for example, may find state inspection reports are missing information about crimes that have occurred in the facility.  One approach to making this information available is through the Freedom of Information Act. The Freedom of Information Act does not preclude the release of any information, but local jurisdictions may prevent the release of police report data.  Agencies that receive FOIA requests may provide feedback on long-term data-sets that would be of public value that are currently only captured in police reports.

Computer aided dispatch systems (http://en.wikipedia.org/wiki/Computer-aided_dispatch) are increasingly common, and collect valuable sources of public safety information.  CAD typically consists of a suite of software packages used to initiate public safety calls for service, dispatch, and to maintain the status of responding resources in the field. If computer aided dispatch systems are used in your city, they are perhaps the most easily available, well-formatted, and timely data available.  However, these will not have the same context, analysis, or validation from police reports or UCR, and should be carefully used.

To address neighborhood concerns, your city may be interested in providing more finer-grained reporting than is available through city-wide monthly UCR reporting.  The first step to providing this information is making sure that geolocation (with latitude and longitude) and timestamps are captured by police agencies, along with incident information.  Even if you have a CAD system, it may be difficult to relate information from these two sources.   If your city has clearly identified neighborhoods, neighborhood boundary shapefiles can be used to categorize UCR data for neighborhood distribution.

# Decide how to format your data

Police reports are often only in paper format, and will be.

Good data formats should have structure that allows programmers to easily find, extract, and transform data, and should be legible by humans.  Raw CAD formats are very close to this ideal.
Here is a typical CAD printout:
-----------------------------------
LOCATION - 1400 Madison
RP       - Doe, John, 555-5555, 1404 Madison
INCIDENT - BURGLARY (in progress)
SYNOPSIS - "Caller reports a possible burglary in progress based on seeing individuals 
inside the residence/Caller advises 2 persons inside the location and call advises 
the current residents are on vacation."
-----------------------------------

Along with a timestamp, your city may capture CAD data for daily aggregation to meet community concrns.  Agencies that are under resource constraints often look for commercial partners that will format crime data for public consumption.  The pitfall of this approach is that these companies will not make the crime data available outside of their consumer application.  Even in this scenario, programmers may provide feedback on how agencies may make this data accessible.  http://www.mattmacdonald.com/2011/05/11/getting-access-to-police-incident-logs-from-a-computer-aided-dispatch-system/  Without open source interface to CAD systems, the best advice is to work closely with your city's technical community to get a solution that is tailored for your city's needs.

#3 How to publish

The community questions about public safety that you want to answer will help you determine the best way to publish your data. If you are interested in providing a longer term view of crime trends, making a multi year data set available is important.  If you are interested in providing a view of neighborhood issues, an API that can be queried by parameters including geography and time of incident is important.  CAD data could easily be transformed into real-time alerts, although many cities have some reluctance to do this, to avoid interference with police operations.

Cities such as Boston, Chicago, and New York make crime incident reports available through data portals.  If data portals are part of your city's strategy, consider how to include crime data, as they are some of the most requested datasets wherever they are made available.




