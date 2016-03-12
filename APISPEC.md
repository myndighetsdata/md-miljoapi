# Format för anrop mot datakällor
# miljorapport.myndighetsdata.se

Varje API anropas med en HTTP POST eller GET och följande argument skickas in:

```
pno=	123456-1234
firstname=Kalle
lastname=Bertilsson
city=Uppsala
zipcode=75320
street=Dragarbrunnsgatan 54
countrycode=se
scbid=180
wgs84lat=59.178947981234
wgs84lon=18.123871289313
```

Datakällan skall svara med JSON på följande sätt:

```
[
  { "priority": "normal", "text": "" },
  { "priority": "low", "text": "" }
]
```