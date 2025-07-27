# Module 5: Execution: Introduction to Node.js

## Introduction

In this module, you’ll explore the origins of web servers and how they have evolved. You’ll learn about Node.js and the benefits it provides to web developers. You’ll also learn about the benefits of using Node.js as a runtime environment and how using Node Package Manager (NPM) can make Node.js more efficient. Lastly, you will discover some of the similarities and differences between frameworks and libraries and how developers use both depending on the needs of their websites.

---

## Learning Objectives

After completing this module, you should be able to:

* Explain the functions and evolution of web servers
* Describe Node.js
* Identify how Node.js functions for web requests and fulfills them
* Identify the benefits of Node.js and the importance of Node Package Manager (NPM)
* Compare and contrast frameworks and libraries

---

## The Power of Web Servers

* Early web servers were basic, only serving simple pages.
* Modern web servers (like airports vs. open fields) are multifunctional: delivering, storing, managing, and maintaining web pages and data.
* Web servers are essential for serving content to users across the web.
* Evolution has led to tools like **Node.js**, a JavaScript-based runtime that supports scalable and efficient server-side operations.

---

## What is Node.js?

* **Node.js** is a **JavaScript runtime environment** that allows JavaScript to run outside a browser, primarily on servers.
* It is **open source**, allowing free use and modification.
* **Server-side use**:

  1. User types a URL in a browser (client-side activity).
  2. DNS translates the URL to an IP address.
  3. Request is routed to a server (possibly running Node.js).
  4. Node.js "listens" and responds with the requested web page (server-side activity).

Key Takeaways:

* Web browsers (clients) send requests.
* Web servers (using Node.js) listen and fulfill those requests.
* Servers are always active to receive incoming data.

---

## Detecting a Request

* Servers respond only to specific protocols (HTTP/HTTPS) and open ports (80/443).
* Analogy: Sending a request like texting a friend, not just shouting in a room.
* Servers ignore requests that don’t follow the expected format.

---

## Fulfilling a Request

* A single web request may require delivering multiple components (text, images, scripts).
* Node.js can send JavaScript to the client to collect more data, prompting more requests (multiple round trips).
* Analogy: Asking a friend for chips, then asking for a napkin.

---

## Benefits of Node.js

### 1. Written in JavaScript

* Enables full-stack development using one language.

### 2. Efficient with Server Resources

* **Non-blocking**: Doesn’t pause while waiting for background tasks.
* Offloads time-consuming work to other apps/processes.

### 3. Open Source

* Freely available and modifiable.
* Has a huge ecosystem of libraries and tools.

---

## Node.js and the Node Package Manager (NPM)

* **NPM** is like a massive digital library with ready-to-use tools.
* Capabilities:

  * Install packages and libraries quickly
  * Share code with others
  * Manage versions and dependencies
  * Collaborate with virtual teams
  * Maintain and update projects easily

To use NPM:

* Install Node.js (NPM comes with it)
* Use the command line to install and manage packages

---

## Frameworks and Libraries

### Similarities:

* Both contain reusable JavaScript code
* Enhance website functionality
* Are distributed as open source
* Installed and managed using NPM

### Differences:

| Aspect     | Library                 | Framework                    |
| ---------- | ----------------------- | ---------------------------- |
| Scope      | Narrow (specific tasks) | Broad (structure entire app) |
| Dependency | Independent             | May use libraries            |
| Usage      | Called when needed      | Integrated throughout app    |

### Examples:

* **Libraries**: jQuery (DOM manipulation)
* **Frameworks**: React, Vue.js, Angular (full app architecture)

---

## Summary

* Node.js brings JavaScript to server-side development.
* Web servers running Node.js can handle many requests efficiently.
* NPM enhances development with ready-to-use open-source packages.
* Libraries and frameworks offer flexibility depending on project needs.
* Node.js enables efficient, scalable, and collaborative web development.
