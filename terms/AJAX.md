---
term: AJAX
description: Asynchronous JavaScript and XML allows the client to send &amp; retrieve data from the server without reloading the page. 
---

AJAX is not a single piece of technology but rather a group of related technologies that are used to create dynamic and interactive web applications. Most often XML is replaced with HTML or JSON as the data format.

```
var r = new XMLHttpRequest();
r.open("POST", "path/to/api", true);
r.onreadystatechange = function () {
  if (r.readyState != 4 || r.status != 200) return;
  alert("Success: " + r.responseText);
};
r.send("Non Stop!");
```
