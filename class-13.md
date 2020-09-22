
# About Local Storage

### Introducing HTML5 Storage
- HTML5 storage, commonly known as web storage, is originally a part of the HTML5 specification proper, but it was split inti its own specification. It is also referred to as local storage or DOM storage. Regardless of the name, to be put simply HTML5 storage is a way for web pages to store named key/value pairs locally within the client web browser.
- For example, this snippet of code:

```
var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);
…could be rewritten to use square bracket syntax instead:

var foo = localStorage["bar"];
// ...
localStorage["bar"] = foo;
```

![](https://i0.wp.com/blogs.itpro.es/eduardocloud/files/2014/05/localstorage.png)

- All the browsers support the HTML5 web storage.

- From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object.


## TRACKING CHANGES TO THE HTML5 STORAGE AREA
- when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will not fire, because nothing actually changed in the storage area.


- example 

```

if (window.addEventListener) {
  window.addEventListener("storage", handle_storage, false);
} else {
  window.attachEvent("onstorage", handle_storage);
};

```
- You can also delete the stored item using another method.
- You can you enentlistener to track the changes that happen in the storage.

## Tracking changes
To track changes you can trap the storage event; whenever the setItem(), removeItem() or clear() are called and actually change something the storage event is fired. The storage event is supported everywhere the localStorage object is supported, therefore, to hook the storage event, you’ll need to check which event mechanism the browser supports. The handle_storage callback function will be called with a StorageEvent object, at this point, the variable will be a StorageEvent object.

## StorageEvent object properties
![](https://dl.dropboxusercontent.com/s/wdhv1o5r2apurm6/storageh.png)

---------------------------------------------------------------------


[Table Of Content](https://omarxzain.github.io/reading-notes/)

