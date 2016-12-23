# hummingbird-heroku
Sample of a repo for a Heroku pipeline

## API Deployment Example 
Connects Intel Edison module to an Android App. 

### Android app PUT request
 
 localhost:8001/edpairs/1?mobileid=xyz456

JSON input:

```
{
   "id": 1,
   "endpointid": "abc123",
   "mobileid": "xyz456",
   "ledstate": "on"
 }
```

### Edison endpoint GET request 

localhost:8001/edpairs?endpointid=abc123

JSON output:

```
{
   "id": 1,
   "endpointid": "abc123",
   "mobileid": "xyz456",
   "ledstate": "on"
 }
```
 
 
 
