---
title: "What protocol should I use for my API?"
layout: default
permalink: {{ site.root }}/general/api_protocols/
---

#Protocols:

By default your web services should communicate via HTTP over SSL.
You should have a pretty good reason for diverging from that.


There are two main options of protocols to use for your API, REST and SOAP.

##REST
A protocol that reuses the HTTP verbs and describes resources by URLs. (Simple, right?)
For more information, check out [wikipedia](http://en.wikipedia.org/wiki/REST).

##SOAP
An XML based protocol often found in enterprise/banking applications.
For more information including a list of [advantages/disadvantages](http://en.wikipedia.org/wiki/SOAP#Technical_critique), check [wikipedia](http://en.wikipedia.org/wiki/SOAP)

Most modern APIs are adhering to a RESTful format, rather than using SOAP. With that in mind, REST may be a more cofortable default protocol.

Both REST and SOAP should be well supported by clients.

