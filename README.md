# jquery-fetch
A queue for jquery ajax, it avoid multiple HTTP requests at the same time 

```
var testurl = 'http://localhost';
var testObj = {
    type: "GET",
    url: testurl,
    complete: function (xhr, status, et) {
        console.info('!!!joooo!!!');
    }
};

for(var i=0;i<103;i++) $.fetch.ajax(testObj);
```

### App
Now apply yacebao.com.
