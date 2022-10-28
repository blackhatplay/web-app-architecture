# Web App Architecture

## 1. What is a Web App?

A web application is a program that runs remotely and can be accessed through any web browser. It is a combination of client-side and server-side scripts that handle how data is stored, retrieved, and displayed to the user.

People often confuse web applications and websites as being the same but actually, the two are quite different.

A website focuses more on just displaying the content – usually the same content to all users. A web app, on the other hand, does more than just display the content; it also allows users to perform actions by interacting through web pages with the server.

![web app](./web-app.png 'web app')

### Types of web applications

The two main types of web applications are:

-   Dynamic: Require server-side processing to input your data and show you the relevant information.
-   Static: Do not require any server-side processing.

### Examples

Some of the more popular examples of web applications include things like Google Docs, DropBox, and Spotify.

### 2. Web Server versus Application Server

A **web server** accepts and fulfills requests from clients for static content (i.e., HTML pages, files, images, and videos) from a website. Web servers handle HTTP requests and responses only.

An **application server** exposes business logic to the clients, which generates dynamic content. It is a software framework that transforms data to provide the specialized functionality offered by a business, service, or application. For example, application servers, like the Apache Tomcat, power the interactive parts of a website that can appear differently depending on the context of the request.

The illustration below highlights the difference in their architecture:

![web server versus application server](./web-server-vs-application-server.png 'web server versus application server')

The columns below summarize the key differences between the two types of servers:

| Web Server                                                   | Application Server                                                                        |
| ------------------------------------------------------------ | ----------------------------------------------------------------------------------------- |
| Deliver static content.                                      | Delivers dynamic content.                                                                 |
| Content is delivered using the HTTP protocol only.           | Provides business logic to application programs using several protocols (including HTTP). |
| Serves only web-based applications.                          | Can serve web and enterprise-based applications.                                          |
| No support for multi-threading.                              | Uses multithreading to support multiple requests in parallel.                             |
| Facilitates web traffic that is not very resource intensive. | Facilitates longer running processes that are very resource-intensive​.                   |

## 3. HTTP

Read this article on Mozilla Developer Network.
[https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)

## 4. Choosing a HTTP Response Code

1. [Use this flowchart to decide what status code to use and when](https://www.codetinkerer.com/2015/12/04/choosing-an-http-status-code.html)
2. [Commonly used Response Codes with Discussion](https://www.bigbinary.com/conversation)
