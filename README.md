You will need following `resolver.json`:
```
{"schema":"iglu:com.snowplowanalytics.iglu/resolver-config/jsonschema/1-0-1","data":{"cacheSize":0,"repositories":[{"name": "Iglu Central","priority": 0,"vendorPrefixes": [ "com.snowplowanalytics" ],"connection": {"http":{"uri":"http://iglucentral.com"}}},{"name":"Priv","priority":0,"vendorPrefixes":["com.snowplowanalytics"],"connection":{"http":{"uri":"https://raw.githubusercontent.com/peel/schemas/master"}}}]}}
```
