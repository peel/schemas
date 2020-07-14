You will need following `resolver.json`:
```
https://g{"schema":"iglu:com.snowplowanalytics.iglu/resolver-config/jsonschema/1-0-1","data":{"cacheSize":0,"repositories":[{"name": "Iglu Central","priority": 0,"vendorPrefixes": [ "com.snowplowanalytics" ],"connection": {"http":{"uri":"http://iglucentral.com"}}},{"name":"Priv","priority":0,"vendorPrefixes":["com.snowplowanalytics"],"connection":{"http":{"uri":"https://raw.githubusercontent.com/peel/schemas/master"}}}]}}ist.githubusercontent.com/peel/15f551129f8e69577eb18a60aa12e030/raw/46978a0a53d9ee7aeb9f04ca059b1106d8a8f1ea/resolver.json
```
