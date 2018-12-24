# API Project: URL Shortener Microservice for freeCodeCamp

### User Stories

1. I can POST a URL to `[project_url]//new/https://` and I will receive a shortened URL in the JSON response. Example : `{"original_url":"www.google.com","short_url":1}`
2. If I pass an invalid URL that doesn't follow the valid `http(s)://www.example.com(/more/routes)` format, the JSON response will contain an error like `{"error":"invalid URL"}`. *HINT*: to be sure that the submitted url points to a valid site you can use the function `dns.lookup(host, cb)` from the `dns` core module.
3. When I visit the shortened URL, it will redirect me to my original link.


#### Usage:

[this_project_url]/new/https://www.google.com

#### Example output:
* {"original_url":"https://www.google.com","short_url":"https://uttermost-hat.glitch.me/5"}

### How to run the project :

1. Clone the repository :                  
     https://github.com/akshataw/urlShortener.git

2. Navigate to the repository:
     cd urlShortener

3. Install the dependencies :
     npm install     

4. Run the project :
     node server.js
