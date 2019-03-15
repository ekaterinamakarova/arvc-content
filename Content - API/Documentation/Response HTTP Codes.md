# 2XX - Success
### 200 - OK
Standard response for successful HTTP requests.
### 202 - Accepted
The request has been accepted for processing, but the processing has not been completed. The request might or might not be eventually acted upon, and may be disallowed when processing occurs.
# 4XX - Client errors
### 400 Bad Request
The server cannot or will not process the request due to an apparent client error (e.g., malformed request syntax, size too large, invalid request message framing, or deceptive request routing)
### 401 Unauthorized
Similar to 403 Forbidden, but specifically for use when authentication is required and has failed or has not yet been provided.
### 403 Forbidden
The request was valid, but the server is refusing action. The user might not have the necessary permissions for a resource, or may need an account of some sort.
### 404 Not Found
The requested resource could not be found but may be available in the future. Subsequent requests by the client are permissible.
### 409 Conflict
Indicates that the request could not be processed because of conflict in the current state of the resource, such as an edit conflict between multiple simultaneous updates. Resource already exists.
### 440 Login Time-out
The client's session has expired and must log in again.
# 5XX - Server errors
### 500 Internal Server Error
A generic error message, given when an unexpected condition was encountered and no more specific message is suitable.
1234
