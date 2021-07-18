# SampleRestAPI

This is a very simple rest api for testing. It can be run on standalone machine or docker image

# Pre-reqs

**Node JS** must be installed.

# Steps to run:

1. Go to downloaded folder
2. Run **npm i** to install all dependencies
3. Run **npm run start**

# Test

## GET /

````curl -i http://localhost:3000
HTTP/1.1 200 OK
X-Powered-By: Express
Content-Type: application/json; charset=utf-8
Content-Length: 24
ETag: W/"18-M3ijksUyZiG/Ji/MRujNy9rS6to"
Date: Sun, 18 Jul 2021 09:09:01 GMT
Connection: keep-alive
Keep-Alive: timeout=5

{"data":"Hello World!!"}```
````
