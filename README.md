# Code Test

## Develop a simple API using Laravel 5.* framework
1. Build a consumer to get data from the testing API (Guzzle as the client is preferred)
..* URL: http://dev-mw.oneaffiniti.com/api/contact/search
..* Method: POST
..* Content-Type: application/json
..* Payload: {"search_terms":{}}

2. Build an API to return the contact data
..* URL: app_url/api/contact
..* Method: POST
..* Allow pass parameters ("limit" and "order_by") in JSON. Example: {"limit": 5, "order_by": "first_name"}
..* Returns JSON data based on the "limit" and "order_by" parameters in similar format as the testing API from point 1.
