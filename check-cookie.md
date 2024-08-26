```
pm.test("Cookie isLoggedIn is present", () => {
  pm.expect(pm.cookies.has('isLoggedIn')).to.be.true;
});
pm.test("Cookie isLoggedIn has value 1", () => {
  pm.expect(pm.cookies.get('isLoggedIn')).to.eql('1');
});
```