## CN

Check if value is a WeakSet object.

|参数名|类型|说明|
|-----|----|---|
|val   |*      |Value to check            |
|返回值|boolean|True if value is a WeakSet|

```javascript
isWeakSet(new Set()); // -> false
isWeakSet(new WeakSet()); // -> true
```