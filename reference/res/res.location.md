# res.location()
Sets the "Location" response header to the specified URL expression (`url`).

### Usage
res.location(url);

### Example
```javascript
res.location('/foo/bar');
res.location('foo/bar');
res.location('http://example.com');
res.location('../login');
res.location('back');
```

### Notes
>+ You can use the same kind of URL expressions as in res.redirect().










<docmeta name="uniqueID" value="reslocation779137">
<docmeta name="displayName" value="res.location()">

