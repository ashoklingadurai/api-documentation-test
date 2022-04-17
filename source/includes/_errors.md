# Errors

<aside class="notice">
The following are some of the error codes you may encounter when you work with Shipment APIs.
</aside>

Error Code | Meaning | Description
---------- | ------- | -------
400 | Bad Request | Your request is invalid.
401 | Unauthorized | Your API key is wrong.
403 | Forbidden | The requested data is hidden or can be accessed by administrators only.
404 | Not Found | The specified data could not be found.
405 | Method Not Allowed | You tried to access data with an invalid method.
406 | Not Acceptable | You requested a format that isn't json.
410 | Gone | The requested data has been removed from our servers.
429 | Too Many Requests | 
500 | Internal Server Error | We had a problem with our server. Try again later.
503 | Service Unavailable | We're temporarily offline for maintenance. Please try again later.
