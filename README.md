# qConvert-javascript-library
Some popular convert methods.

<b>Size: </b> 3,64KB.<br/>
<b>Total methods: </b> 28.

<p><i>Notice: </i>this library may be helpful for enyone who often works with diffrents transform methods via JavaScript. <br/>
In the future archieve will be periodically supplemented by new functions.

<p>See description for each method below.</p>

<h2> allOverlap </h2>
Return found matches.
```javascript
qConvert.allOverlap(4, [3,43,'a',4], 2); 
```

<b>Output:</b> {"index": 3, "value": 4}
*************

<h2> capitalizeFirst </h2>
First char at each word in UpperCase.
```javascript
qConvert.capitalizeFirst("hello world!"); 
```

<b>Output:</b> Hello World!
*************

<h2> checkArrayAvailability </h2>
Add values into collection and return "Full" if filled.
```javascript
var arr = [],
    values = ["a", "b", "c"];
qConvert.checkArrayAvailability(arr, "b", values);
qConvert.checkArrayAvailability(arr, "b", values); 
qConvert.checkArrayAvailability(arr, "c", values);
qConvert.checkArrayAvailability(arr, "a", values);
qConvert.checkArrayAvailability(arr, "a", values);    
```

<b>Output:</b> ["b"]<br/>
<b>Output:</b> ["b"]<br/>
<b>Output:</b> ["b", "c"]<br/>
<b>Output:</b> Full<br/>
<b>Output:</b> Full
*************

<h2> cloneArray </h2>
Clone assigned array into temporary memorary for safe use.
```javascript
qConvert.cloneArray([1,2,3]);
```

<b>Output:</b> [1,2,3]
*************

<h2> cloneDate </h2>
Clone assigned Date into temporary memorary for safe use.
```javascript
qConvert.cloneDate(new Date());
```

<b>Output:</b> -
*************

<h2> cloneObj </h2>
Clone assigned object into temporary memorary for safe use.
```javascript
qConvert.cloneObj({a:1, b:2});
```

<b>Output:</b> {a:1, b:2}
*************

<h2> findDuplicates </h2>
Finds duplicates in array.
```javascript
qConvert.findDuplicates(['a', 'b', 'A', 'A', 'c']);
```

<b>Output:</b> [{Value: 'a', Matches: 1}, {Value: 'b', Matches: 1}, {Value: 'A', Matches: 2}, {Value: 'c', Matches: 1}]
*************

<h2> findMax </h2>
Finds maximal significance.
```javascript
qConvert.findMax([-1,2,35,6,4]);
```

<b>Output:</b> 35
*************

<h2> findMin </h2>
Finds minimal significance.
```javascript
qConvert.findMin([-1,2,35,6,4, 0, -30, 31]);
```

<b>Output:</b> -30
*************

<h2> getUnique </h2>
Returns unique values from array. If number repeats more than 2 times, will be repeated itself.
```javascript
qConvert.getUnique([2,3,2,5,4,3,5,5,4]);
```

<b>Output:</b> [2,3,5,4]
*************

<h2> isBigger </h2>
Compare two numbers.
```javascript
qConvert.isBigger(3,7);
```

<b>Output:</b> false
*************

<h2> isLess </h2>
Compare two numbers.
```javascript
qConvert.isLess(4,5);
```

<b>Output:</b> true
*************

<h2> isNegative </h2>
Return boolean capacity after check number property.
```javascript
qConvert.isNegative(4);
```

<b>Output:</b> false
*************

<h2> isNegative </h2>
Defines that collection truly contains numerable only and returns Boolean.
```javascript
qConvert.isNumerable([1,2,3, 'a']);
qConvert.isNumerable([1,2,"3"]);
```

<b>Output:</b> false<br/>
<b>Output:</b> true
*************

<h2> isNotEmptyArray </h2>
Return true if array isn't empty.
```javascript
qConvert.isNotEmptyArray([1,2,3, 'a']);
```

<b>Output:</b> true
*************

<h2> isPositive </h2>
Return boolean capacity after check number property.
```javascript
qConvert.isPositive(4);
```

<b>Output:</b> true
*************

<h2> merge </h2>
Concat assigned objects into main.
```javascript
qConvert.merge({a:1}, {b:2});
qConvert.merge({a:1}, {a:3});
qConvert.merge({a:1}, 5);
```

<b>Output:</b> {a:1, b:2}<br/>
<b>Output:</b> {a:3}<br/>
<b>Output:</b> {a:1}
*************

<h2> mult </h2>
Multiples the numbers or array of numbers if necessary.
```javascript
qConvert.mult(1,2,3);
qConvert.mult("1",[4], 2);
qConvert.mult("1",[4], 2, [1.25]);
```

<b>Output:</b> 6<br/>
<b>Output:</b> 8<br/>
<b>Output:</b> 10
*************

<h2> pushIfNotExists </h2>
Insert assigned value into array if not exists.
```javascript
qConvert.pushIfNotExists([1,2,4], 3);
```

<b>Output:</b> [1,2,3,4]
*************

<h2> remove </h2>
Delete assigned values from array.
```javascript
qConvert.remove([1,2,3,4,5], 3);
```

<b>Output:</b> [1,2,4,5]
*************

<h2> reverse </h2>
Reverse existing string.
```javascript
qConvert.reverse("hello");
```

<b>Output:</b> olleh
*************

<h2> runFuncFromVariable </h2>
Run function from string if exists.
```javascript
qConvert.runFuncFromVariable("greeting");
```

<b>Output:</b> greeting()
*************

<h2> sortArrayObjects </h2>
Produce sorting with elements within array of objects.
```javascript
qConvert.sortArrayObjects([{name: "Dilan"}, {name: "Bob"}, {name: "Daniel"}], "name");
```

<b>Output:</b> [{name: "Bob"}, {name: "Daniel"}, {name: "Dilan"}]
*************

<h2> subtract </h2>
Reverse number significance, all strings equal to 0, then add elements.
```javascript
qConvert.subtract(5, "h", 3);
```

<b>Output:</b> -8
*************

<h2> sum </h2>
Add the numbers, all strings equal to 0.
```javascript
qConvert.sum([1,2,3], [4]);
qConvert.sum(1,2,3);
```

<b>Output:</b> 10<br/>
<b>Output:</b> 6
*************

<h2> toCamelCase </h2>
Converts into Camel Case .
```javascript
qConvert.toCamelCase('Hello world');
```

<b>Output:</b> helloWorld
*************

<h2> toNumber </h2>
Converts string into number.
```javascript
qConvert.toNumber("3.5");
```

<b>Output:</b> 3.5
*************

<h2> toThousand </h2>
Transform number into thousand format via filter.
```javascript
qConvert.toThousand("1233.5");
```

<b>Output:</b> 1,233.5
*************

<h2> toggleIntoArray </h2>
Add value into array if not exists or remove it. Works with Numbers, String and Objects. Object type have to receive 2 additional parameters.
```javascript
qConvert.toggleIntoArray([1,2], 2);
qConvert.toggleIntoArray(["a", "b"], "c");
qConvert.toggleIntoArray(arr, {a: 2, b:4}, "a", 2);
qConvert.toggleIntoArray(arr, {a: 3, b:4}, "a", 3);
qConvert.toggleIntoArray(arr, {a: 2, b:4}, "a", 2);
```

<b>Output:</b> [1] <br/>
<b>Output:</b> ["a", "b", "c"] <br/>
<b>Output:</b> [{a:2, b:4}] <br/>
<b>Output:</b> [{a:2, b:4}, {a:3, b:4}] <br/>
<b>Output:</b> [{a:3, b:4}]
*************

</tbody>
</table>
