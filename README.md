# apirest-javascript

Plugin en proceso full javascript

```javascript
var 
rest = new Api('http://echo.jsontest.com/key/value');
rest.get(function(s)
{
      document.getElementById("r").innerHTML = JSON.stringify(s);
});
```
