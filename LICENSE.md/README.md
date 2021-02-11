
HTTP Status Code	Description

200 OK	Successful.

201 Created	Created.

400 Bad Request	Bad input parameter. Error message should indicate which one and why.

401 Unauthorized	The client passed in the invalid Auth token. Client should refresh the token and then try again.

403 Forbidden	* Customer doesn’t exist. * Application not registered. * Application try to access to properties not belong to an App. * Application try to trash/purge root node. * Application try to update contentProperties. * Operation is blocked (for third-party apps). * Customer account over quota.

404 Not Found	Resource not found.

405 Method Not Allowed	The resource doesn't support the specified HTTP verb.

409 Conflict	Conflict.

411 Length Required	The Content-Length header was not specified.

412 Precondition Failed	Precondition failed.

429 Too Many Requests	Too many request for rate limiting.

500 Internal Server Error	Servers are not working as expected. The request is probably valid but needs to be requested again later.

503 Service Unavailable	Service Unavailable.
