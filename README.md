# JSUNFuckIt

---

Encodes or Decodes Javascript using JSFuck 0.4.0

*__see__* https://github.com/aemkei/jsfuck

*\*note this differs slightly from the JSFuck served at http://www.jsfuck.com/*

##### usage
```shell
usage:
	'python jsunfuck.py <option> <flags> <file>'
 	options:
    	decode -- decodes jsfuck\'d Javascript
        encode -- encodes vanilla Javascript
            flags:
                -e | --eval: wrap in eval
                -p | --parent: run in parent scope
 ```

##### output

```js
$ python jsunfuck.py decode tests/encoded.js
alert('hello, world!');
```
