# Get client's location
```
  var geojs = JSON.parse(httpGet("https://get.geojs.io/v1/ip/country.json"))

  var code = geojs.country.toLowerCase()
  
  var geoen = JSON.parse(httpGet(`https://get.geojs.io/v1/ip/geo/${geojs.ip}.json`))
  
  var region = geoen.continent_code
```
# Example
```
https://gympluscoffee.de/
```
