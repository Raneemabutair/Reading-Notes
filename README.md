
# **Local Storage**


* Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data.

* Cookies has three big disadvantages:

  * Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over

  * Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)

  * Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful 


* user Data allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. (Trusted domains, such as intranet sites, can store 10 times that amount.

* In 2002 they invented Flash that gives each domain 100 KB of storage “for free.” Beyond that, it prompts the user for each order of magnitude increase in data storage (1 Mb, 10 Mb, and so on).

* in 2007, Google launched Gears that provides an API to an embedded SQL database based on SQLite. After obtaining permission from the user once, Gears can store unlimited amounts of data per domain in SQL database tables.

* HTML5 Storage it’s a way for web pages to store named key/value pairs locally, within the client web browser.

* HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key.

* You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string.


**STORAGEEVENT OBJECT**

<img src ="https://www.programmersought.com/images/35/8fc50290594cf12a3769afd0b4b40cd3.png ">

* A new API has been standardized and implemented across all major browsers, platforms, and devices.

* We have another competing vision for advanced, persistent, local storage for web applications: the Indexed Database API, formerly known as “WebSimpleDB,” now affectionately known as “IndexedDB.”
