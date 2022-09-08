# Class 13

## Local Storage and how to use it on websites

*Why would a developer use local storage for a web application?*

Local storage allows developers to store and retrieve data in the browser. As a developer you need to store information so you can use it at a later date. Javascript allows you to save key value pairs in the local storage. This means that the data will be stored in the browser even after you close the browser window.

*What information should not be stored in local storage?*

You should never store sensitive information such as passwords, personal information or bank details etc. Some people out there in the world will abuse this for darker purposes. There was a scary demo called 'evercookie' which shows how to exploit all kinds of local storage, even when cookies are turned off it will store and save data.

*Local storage can store what type of data? How would you convert it to that type before storing?*

Local storage can only store strings which is one downfall. In turn, this means that when you have an object, it won't be stored in the correct way. To get around this, you need to use the native methods which are: 

`JSON.stringify()` and `JSON.parse()`




