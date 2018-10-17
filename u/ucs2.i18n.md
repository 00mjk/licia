## CN

UCS-2 编解码。

### encode

通过码点序列创建字符串。

|参数名|类型|说明|
|-----|----|---|
|arr|array|码点序列|
|返回值|string|编码后的字符串|

### decode

通过字符串创建码点序列。

|参数名|类型|说明|
|-----|----|---|
|str|string|字符串|
|返回值|array|码点序列|

```javascript
ucs2.encode([0x61, 0x62, 0x63]); // -> 'abc'
ucs2.decode('abc'); // -> [0x61, 0x62, 0x63]
'𝌆'.length; // -> 2
ucs2.decode('𝌆').length; // -> 1
```