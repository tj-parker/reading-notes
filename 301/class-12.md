# Class 12 Reading Notes

## Status Codes Based on REST Methods

100-199 are informational status codes, telling the client that the header part of the request has been received

200-299 are success codes, telling the client the request was accepted.

300-399 are redirection codes, telling the client that the resources requested aren't available at the expected location

400-499 are error codes sent wehn the request is invalid

500-599 are server error, indicating problems with overwhelmed or unreachable servers

A 202 code is an asychronous processing request, the request was valid but its processign will finish sometime in the future

A 308 code is a permanent redirect, telling the client to use another URL to access the resource and not to use the current URL anymore

If an update didn't return data to a client, use 204

If a resource used to exist but no longer does, use 410

403 is the forbidden status code

## Build A REST API with Node.js, Express, & MongoDB