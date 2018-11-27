# API Project: URL Shortener Microservice for freeCodeCamp


### User Stories

1. I can POST a URL to `[project_url]/api/shorturl/new` and I will receive a shortened URL in the JSON response. Example : `{"original_url":"www.google.com","short_url":1}`
2. If I pass an invalid URL that doesn't follow the valid `http(s)://www.example.com(/more/routes)` format, the JSON response will contain an error like `{"error":"invalid URL"}`. *HINT*: to be sure that the submitted url points to a valid site you can use the function `dns.lookup(host, cb)` from the `dns` core module.
3. When I visit the shortened URL, it will redirect me to my original link.


#### Creation Example:

<code><a href="https://thirsty-macaw.glitch.me/https://www.google.ca" target="_blank">https://thirsty-macaw.glitch.me/https://www.google.ca</a></code>

#### Usage:

<code>{ "url": "https://thirsty-macaw.glitch.me/https://www.google.ca", "short-url": "https://thirsty-macaw.glitch.me/blahblah" }</code>

#### Will redirect to:

<code><a href="https://www.google.ca" target="_blank">https://www.google.ca</a></code>
# shorturlapp
