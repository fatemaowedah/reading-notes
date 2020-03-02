## The past, present & future of local storage for web applications.
*local storage is one of the areas where native client applications have held an advantage over web applications*
* operating system typically provides an abstraction layer for storing: in registry, INI files.
* Historically : cookies can be used for presistent local storage for small amount 4 KB of data, slowing down your web app, sending data unecrypted over the internet.
* before Html userData allows web page to store up to 64KB of data per domain.
* for each year devloper can to increaase the size of store data.
### Introducing HTML5 Storage.
* Local storage or DOM storage.
* store named key/value locally whitin the client web browser, this data is never transmitted to the remote web server, it is implemented natively in web browsers.
* you can access HTML5 storage from javascript through `localStorage`
### Using HTML5 store 
* is based on named key/value
* You store data based on a named key, then you can retrieve that data with the same key.
* store us a string :use parseInt(), parseFloat()
* getItem(named key):overwrite the previous value .
* remove the value given named key and clear storage area use removeItem.
* Tracking changes to the HTML5 storage area
setItem(),removeItem(),clear().
### Storageevent object
* key: string, oldValue:any, newValue:any, url:string.
### HTML5 storage in action
* use localStorage object 

