# 1xx – Informational (Rarely seen by users)
100 Continue – The server acknowledges the request and tells the client to proceed.

101 Switching Protocols – The server is switching to a different protocol (like WebSockets).

# 2xx – Success ✅
200 OK – Everything worked! The requested page or resource is delivered.

201 Created – Used when a new resource is successfully created (e.g., after a form submission).

204 No Content – The request was successful, but there’s no content to send back (used in APIs).

# 3xx – Redirection 🔄
301 Moved Permanently – The resource has moved to a new URL permanently (used for SEO and domain changes).

302 Found (or 307 Temporary Redirect) – The resource is temporarily moved to another location.

304 Not Modified – The browser can use a cached version instead of downloading the page again.

# 4xx – Client Errors ❌
400 Bad Request – The request was malformed or had invalid syntax.

401 Unauthorized – Authentication is required (e.g., logging into a website).

403 Forbidden – Access to the resource is denied (even with authentication).

404 Not Found – The page or resource does not exist.

405 Method Not Allowed – The requested HTTP method (e.g., POST on a GET-only resource) is not allowed.

# 5xx – Server Errors 🛑
500 Internal Server Error – The server encountered an unexpected issue.

502 Bad Gateway – The server received an invalid response from another server.

503 Service Unavailable – The server is temporarily overloaded or under maintenance.

504 Gateway Timeout – The server didn’t respond in time.

