# Socket client to test socket API.
This is a simple socket client to test socket API's just like postman for REST API's.


You can use simple http server like [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en) for hosting this page.

How to run?
---


```
$ git clone https://github.com/HarinRamesh/socket-client.git
```

if you are using Web Server for Chrome
1. Add [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en) to chrome.
2. Open the Web Server for Chrome and add the socket-client folder into it.
3. It 


Or 

You can run development server in Python or anything you prefer, example below shows how it is done in Python.
```
$ cd socket-client
$ python3 -m http.server 8887
```

Now open `http://127.0.0.1:8887` in browser.
