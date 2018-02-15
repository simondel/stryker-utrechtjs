```js
function isOldEnough(user) {
    // return user.age >= 18;
    return user.age > 18;
}
```

```js
var user = { name: 'Simon', age: 24 };
assert.equal(isOldEnough(user), true);
```