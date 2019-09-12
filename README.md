# notes
notes for ilts

```
  <!-- KIE SERVER WAR IS LOOKING FOR THESE PROPERTIES -->
  <property name="org.kie.server.controller" value="http://localhost:8080/business-central/rest/controller"/>
  <property name="org.kie.server.controller.user" value="adminUser"/>
        <property name="org.kie.server.controller.pwd" value="r3dh4t1!"/>
        <property name="org.kie.server.user" value="adminUser"/>

        <!-- BUSINESS CENTRAL IS LOOKING FOR THESE -->
        <property name="org.kie.server.location" value="http://localhost:8080/kie-server/services/rest/server"/>
        <property name="org.kie.server.pwd" value="r3dh4t1!"/>
        <property name="org.kie.server.id" value="local-diego"/>
```

# This is an example for custom object request

```
{
"flightBooking":{
"org.acme.kie-server-lab-kjar.fligh-booking-process.Booking":{
"applicant": {
"emailAddress": "john.doe@server.net",
"name": "John Doe",
"numberOfTravelers": 4
}
},
"flight": {
"carrier": "United",
"flightNr": "UA1345",
"ratePerPerson": 345,
"startCity": "Los Angeles",
"targetCity": "New York",
"travelClass": "B",
"travelDate": "01-25-2019"
}
}
}
```
