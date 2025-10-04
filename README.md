# HTTP Status Codes Cheatsheet

A quick reference for beginners and experienced developers to understand the most common HTTP status codes.

---

## ✅ 2xx – Success
- **200 OK** → Request succeeded, and data is returned (e.g., GET).
- **201 Created** → A new resource was created successfully (e.g., POST).
- **202 Accepted** → Request accepted but not completed yet (often used for async processing).
- **204 No Content** → Request succeeded but no data to send back (e.g., DELETE, PUT).

---

## 🔄 3xx – Redirection
- **301 Moved Permanently** → The resource has a new permanent URL.
- **302 Found** → Temporary redirect to another URL.
- **304 Not Modified** → The cached version is still valid, no need to re-fetch.

---

## ⚠️ 4xx – Client Errors
- **400 Bad Request** → Invalid request (e.g., malformed JSON, missing parameters).
- **401 Unauthorized** → Authentication required or invalid credentials.
- **403 Forbidden** → Authenticated but not allowed (no permission).
- **404 Not Found** → The requested resource doesn’t exist.
- **409 Conflict** → Conflict with the current state (e.g., duplicate record).
- **422 Unprocessable Entity** → Validation failed (e.g., wrong data format).

---

## ❌ 5xx – Server Errors
- **500 Internal Server Error** → Generic server error (bug, crash, etc.).
- **502 Bad Gateway** → Server received an invalid response from upstream.
- **503 Service Unavailable** → Server is down or overloaded.
- **504 Gateway Timeout** → Server didn’t respond in time.

---

### Summary Table

| **Category** | **Range** | **Meaning**                   | **Example**                             |
|--------------|-----------|-------------------------------|-----------------------------------------|
| **1xx**      | 100–199   | Informational                 | 100 Continue                            |
| **2xx**      | 200–299   | Success                       | 200 OK, 201 Created                     |
| **3xx**      | 300–399   | Redirection                   | 301 Moved Permanently, 304 Not Modified |
| **4xx**      | 400–499   | Client Errors                 | 400 Bad Request, 404 Not Found          |
| **5xx**      | 500–599   | Server Errors                 | 500 Internal Server Error, 503 Service Unavailable |

---

### Why this matters
Knowing these codes helps you debug faster, write clearer APIs, and communicate effectively between frontend and backend. Keep this cheatsheet handy while building or troubleshooting your applications.
