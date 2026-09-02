🌐 **HTTP in Detail**

🔗 [TryHackMe — HTTP in Detail](https://tryhackme.com/room/httpindetail)

🧠 **Notes**

🔹 **HTTP**

HTTP is a protocol used for communication between web browsers and web servers.

It is used to transfer resources such as webpages, images, videos and other data.


🔐 **HTTPS**

HTTPS is the secure version of HTTP.

It uses encryption to protect data exchanged between the browser and web server.


🌍 **URL**

A URL is an address used to locate and access a resource on the internet.

Main components include:

Scheme → User → Host → Port → Path → Query String → Fragment


📨 **HTTP Requests**

An HTTP request is sent by a client to request or interact with a resource on a web server.

Requests can contain methods, headers and other information.


📥 **HTTP Responses**

An HTTP response is sent by the server after processing a client request.

It contains a status code, headers and sometimes response data.


🛠️ **HTTP Methods**

HTTP methods indicate the intended action of a request.

Common methods are used to retrieve, create, update and delete resources.


📊 **HTTP Status Codes**

HTTP status codes indicate the result of an HTTP request.

1xx → Informational  
2xx → Success  
3xx → Redirection  
4xx → Client Error  
5xx → Server Error


📋 **HTTP Headers**

Headers provide additional information about HTTP requests and responses.

They can describe the browser, requested website, returned data, caching and other details.


🍪 **Cookies**

Cookies are small pieces of data stored by the browser.

They can be used to maintain sessions, remember preferences and identify users.


🔄 **HTTP Request Flow**

Client → Request → Web Server → Response → Client


❓ **Questions & Answers**

📌 **Task 1**

**Q1:** What does HTTP stand for?

**A:** HyperText Transfer Protocol

**Q2:** What does the S in HTTPS stand for?

**A:** Secure

**Q3:** On the mock webpage on the right there is an issue, once you've found it, click on it. What is the challenge flag?

**A:** THM{INVALID_HTTP_CERT}


📌 **Task 2**

**Q1:** What HTTP protocol is being used in the above example?

**A:** HTTP/1.1

**Q2:** What response header tells the browser how much data to expect?

**A:** Content-Length


📌 **Task 3**

**Q1:** What method would be used to create a new user account?

**A:** POST

**Q2:** What method would be used to update your email address?

**A:** put

**Q3:** What method would be used to remove a picture you've uploaded to your account?

**A:** delete

**Q4:** What method would be used to view a news article?

**A:** get


📌 **Task 4**

**Q1:** What response code might you receive if you've created a new user or blog post article?

**A:** 201

**Q2:** What response code might you receive if you've tried to access a page that doesn't exist?

**A:** 404

**Q3:** What response code might you receive if the web server cannot access its database and the application crashes?

**A:** 503

**Q4:** What response code might you receive if you try to edit your profile without logging in first?

**A:** 401


📌 **Task 5**

**Q1:** What header tells the web server what browser is being used?

**A:** User-Agent

**Q2:** What header tells the browser what type of data is being returned?

**A:** Content-Type

**Q3:** What header tells the web server which website is being requested?

**A:** host


📌 **Task 6**

**Q1:** Which header is used to save cookies to your computer?

**A:** Set-Cookie


📌 **Task 7**

**Q1:** Make a GET request to /room page

**A:** THM{YOU'RE_IN_THE_ROOM}

**Q2:** Make a GET request to /blog page and set the id parameter to 1

**A:** THM{YOU_FOUND_THE_BLOG}

**Q3:** Make a DELETE request to /user/1 page

**A:** THM{USER_IS_DELETED}

**Q4:** Make a PUT request to /user/2 page with the username parameter set to admin

**A:** THM{USER_HAS_UPDATED}

**Q5:** Make a POST request to /login page with the username of thm and a password of letmein

**A:** THM{HTTP_REQUEST_MASTER}


🛡️ **Security Insight**

Understanding HTTP requests, responses, methods, headers, cookies and status codes is essential for web application security and penetration testing.

💡 **Remember**

HTTP communication follows a request-and-response model between clients and web servers.
