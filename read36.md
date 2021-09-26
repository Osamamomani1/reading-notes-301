# Application State with Redux

1. What are the advantages of storing tokens in “Cookies” vs “Local Storage”



* Local Storage

Pros: It's convenient.

It's pure JavaScript and it's convenient. If you don't have a back-end and you're relying on a third-party API, you can't always ask them to set a specific cookie for your site.
Works with APIs that require you to put your access token in the header like this: Authorization Bearer ${access_token}.

* Cookies

Pros: The cookie is not accessible via JavaScript; hence, it is not as vulnerable to XSS attacks as localStorage.

If you're using httpOnly and secure cookies, that means your cookies cannot be accessed using JavaScript. This means, even if an attacker can run JS on your site, they can't read your access token from the cookie.
It's automatically sent in every HTTP request to your server.


2. Explain 3rd party cookies

Third-party cookies are created by domains that are not the website (or domain) that you are visiting. These are usually used for online-advertising purposes and placed on a website through adding scripts or tags. A third-party cookie is accessible on any website that loads the third-party server’s code.

Online advertising is the most common use of third-party cookies. By adding their tags to a page, which may or may not display adverts, advertisers can track a user (or their device) across many of the websites they visit.

3. How do pixel tags work?

A tracking pixel, also known as a marketing pixel, is a 1×1 pixel graphic used to track user behavior, site conversions, web traffic, and other metrics similar to a cookie. The tiny pixel-sided image is usually hidden and embedded in everything from banner ads to emails.

***

## Vocabulary Terms

* **cookies**

Cookies are text files with small pieces of data — like a username and password — that are used to identify your computer as you use a computer network. ... Data stored in a cookie is created by the server upon your connection. This data is labeled with an ID unique to you and your computer.

* **Authorization**

Authorization is a security mechanism to determine access levels or user/client privileges related to system resources including files, services, computer programs, data and application features.

* **access control**

Access control is a security technique that regulates who or what can view or use resources in a computing environment. ... Physical access control limits access to campuses, buildings, rooms and physical IT assets. Logical access control limits connections to computer networks, system files and data.

* **Conditional rendering**

Conditional rendering is a term to describe the ability to render different user interface (UI) markup if a condition is true or false. 

***