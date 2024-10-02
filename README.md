# URL_Shortener

Design a URL shortener service that takes in a valid URL and returns a shortened URL, redirecting the user to the previously provided URL.

Also, keep track of total visits/clicks on the URL.

Routes:

POST /URL - Generates a new short URL and returns the shoertened URL in the format example.com/random_id.

GET /:id - REDIRECTS to the original URL and increments the total visits/clicks.

GET /URL/analytics/:id - Returns the total visits/clicks for the shortened URL.