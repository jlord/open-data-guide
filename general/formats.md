#Formats

The format that you release data in can affect ease and adoption of use.

##JSON
JSON (JavaScript Object Notation) is a lightweight data serialization format that is incredibly well supported by modern tools and languages. In addition to that, it is incredibly readable by humans.

JSON looks like this:
```json
{
    "firstName": "John",
    "lastName": "Smith",
    "age": 25,
    "address": {
        "streetAddress": "21 2nd Street",
        "city": "New York",
        "state": "NY",
        "postalCode": 10021
    },
    "phoneNumbers": [
        {
            "type": "home",
            "number": "212 555-1234"
        },
        {
            "type": "fax",
            "number": "646 555-4567"
        }
    ]
}
```
Learn more about [JSON](http://en.wikipedia.org/wiki/JSON)

##XML
XML (eXtensible Markup Language) is a data serialization format that is both human and machine readable. It is well supported by modern tools and languages.

XML looks like this:
```xml
<object>
    <firstName>John</firstName>
    <lastName>Smith</lastName>
    <age>25</age>
    <address>
        <streetAddress>21 2nd Street</streetAddress>
        <city>New York</city>
        <state>NY</state>
        <postalCode>10021</postalCode>
    </address>
    <phoneNumbers>
        <phoneNumber>
            <type>home</type>
            <number>212 555-1234</number>
        </phoneNumber>
        <phoneNumber>
            <type>fax</type>
            <number>646 555-4567</number>
        </phoneNumber>
    </phoneNumbers>
</object>
```




##Specialized Formats:
###RSS
RSS is a specialized XML format that is most appropriately used for publishing. It is specifically formatted for articles. If your data follows this format (has an author, is published, etc.) RSS is an incredibly appropriate choice.

###General Geo Formats
####GeoJSON/GeoRSS

####GeoJSON
```
related formats
```
