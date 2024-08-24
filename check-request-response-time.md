```
pm.test("Response time is less than 600ms", function () {
    let time_expect =600;
    pm.expect(pm.response.responseTime).to.be.below(time_expect);
});
pm.test("Response time is great than 600ms", function () {
    let time_expect =600;
    pm.expect(pm.response.responseTime).to.be.above(time_expect);
});
pm.test("Response time is equal 600ms", function () {
    let time_expect =600;
    pm.expect(pm.response.responseTime).to.be.equal(time_expect);
});
```