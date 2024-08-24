```
// verify status code of one request
pm.test("check the response status code", function () {
    var status = 200;//this is status that you want to check
    pm.response.to.have.status(status);
});
```
