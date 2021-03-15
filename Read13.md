## local Stoarge: 

Web storage is data stored locally in a user's browser. There are two types of web storage:

• Local storage - data with no expiration date that will persist after the browser window is closed.

• Session storage - data that gets cleared after the browser window is closed.

Previously, cookies were the only option for remembering this type of local, temporary data. Local storage has a significantly higher storage limit (5MB vs 4KB) and doesn't get sent with every HTTP request, so it can be a better option for client-side storage.

### What we really want is:

• a lot of storage space on the client 
that persists beyond a page refresh
and isn’t transmitted to the server.

### What is localStorage in JavaScript?
localStorage is a property that allows JavaScript sites and apps to save key/value pairs in a web browser with no expiration date. This means the data stored in the browser will persist even after the browser window is closed.

For a visual refresher on how to use localStorage in JavaScript, check out the video tutorial below:



### Where is localStorage stored?
In Google Chrome, web storage data is saved in an SQLite file in a subfolder in the user’s profile. The subfolder is located at :`\AppData\Local\Google\Chrome\User Data\Default\Local Storage` on Windows machines and 

`~/Library/Application Support/Google/Chrome/Default/Local Storag`e on macOS


#### Here is an overview of localStorage methods.

![](https://i.ibb.co/VLgbdYN/local-storge.png)
