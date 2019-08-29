# Search Console Helper

A simple bookmarklet that adds the current browser URL to your clipboard, and opens Search Console in a new window for that property.

All you need to do is paste straight into the URL inspection bar.


## Bookmarklet

Copy and paste the code below into a bookmark.
```javascript
javascript:(function(){var e=document.createElement("textarea");document.body.appendChild(e),e.value=window.location.href,e.select(),document.execCommand("copy"),document.body.removeChild(e),window.open("https://search.google.com/search-console?resource_id="+window.location.origin)})();
```

