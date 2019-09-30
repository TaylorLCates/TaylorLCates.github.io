Our homework for this weekend was to explore a little bit of JSON and XML. Tim wanted the following info formatted in both ways: 

First Name : Tim

Last Name : Rayburn

Address Line 1 : 5445 Legacy Drive

Address Line 2 : Suite 100

City : Plano

State : TX

Zip : 75024 


So, after a bit of googling, we have the following in JSON: 

```  {"Element": "First Name", "Name": "Tim"},
    {"Element": "Last Name", "Name": "Rayburn"},
    {"Element": "Address Line 1", "Name": "5445 Legacy Drive"},
    {"Element": "Address Line 2", "Name": "Suite 100"},
    {"Element": "City", "Name": "Plano"},
    {"Element": "State", "Name": "Zip"},
    {"Element": "Zip", "Name": "75024"}
    
    XML
<root>
    <row><Element>First Name</Element><Name>Tim</Name></row>
    <row><Element>Last Name</Element><Name>Rayburn</Name></row>
    <row><Element>Address Line 1</Element><Name>5445 Legacy Drive</Name></row>
    <row><Element>Address Line 2</Element><Name>Suite 100</Name></row>
    <row><Element>City</Element><Name>Plano</Name></row>
    <row><Element>State</Element><Name>Zip</Name></row>
    <row><Element>Zip</Element><Name>75024</Name></row>
</root>
