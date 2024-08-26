```
pm.test("Status code name has string", () => {
  let status ="Created";
  pm.response.to.have.status(status );
});
```