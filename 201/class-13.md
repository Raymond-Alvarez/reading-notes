## Local Storage and How To Use It On Websites

**1. Why would a developer use local storage for a web application?**

Developers use local storage primarily to **add "state" to the web**, overcoming the fact that HTTP is a stateless protocol where closing an application typically resets its data. Key reasons include:
* **Maintaining Interface State:** It allows a developer to save the state of an interface (like form inputs or widget configurations) so it can be restored when the user returns, without requiring the user to create an account or sign in,.
* **Caching Web Service Data:** It is highly effective for caching data from APIs that take a long time to load or have strict call limits,. By storing this data locally, subsequent visits are much faster, and the application can still display information even if an API call fails,.
* **Superiority Over Cookies:** Local storage is a more modern solution than cookies, which are limited to only 4 KB of data and add to the loading weight of every document accessed on a domain.

**2. What information should not be stored in local storage?**

* **User actions and information should not be recorded without the user's knowledge** due to security and privacy concerns. Because local storage can be exploited for "darker purposes"—such as tracking users even when cookies are turned off—developers must consider the **security perspective** of the features they implement. Sensitive data might eventually require an "opt-in" process similar to geographic location sharing to ensure user safety.

**3. Local storage data types and conversion**

Local storage is restricted in that it **can only store strings**. If you attempt to store an object directly, it will be saved incorrectly as "[object Object]" rather than the actual data. 

To store complex data like objects or arrays, you must **convert them into a string** using the native **`JSON.stringify()`** method before saving them. When you need to retrieve and use that data again, you use **`JSON.parse()`** to convert the string back into its original object format.