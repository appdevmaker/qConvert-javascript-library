# qConvert-javascript-library
Some popular convert methods.

<b>Size: </b> 3,07KB.<br/>
<b>Total methods: </b> 26.

<p><i>Notice: </i>this library may be helpful for enyone who often works with diffrents transform methods via JavaScript. <br/>
In the future archieve will be periodically supplemented by new functions.

<p>See description for each method below.</p>

<table width="100%">
<thead>
<tr align="center">
<td> <b>Input Parameter</b> </td>
<td> <b>Method</b> </td>
<td> <b>Description</b> </td>
<td> <b>Example</b> </td>
</tr>
</thead>
<tbody>

<tr align="center">
<td> Number </td>
<td> <b>allOverlap</b> </td>
<td> Returns matches found </td>
<td> <b>qConvert.allOverlap</b>(4, [3,43,'a',4], 2); <hr/> <p><i> {"index": 3, "value": 4} </i></p> </td>
</tr>

<tr align="center">
<td> String </td>
<td> <b>capitalizeFirst</b> </td>
<td> First char at each word in UpperCase </td>
<td> <b>qConvert.capitalizeFirst</b>("hello world!"); <hr/> <p><i> Hello World! </i></p> </td>
</tr>

<tr align="center">
<td> Object </td>
<td> <b>cloneObj</b> </td>
<td> Clones assigned object into temporary memorary for safe use</td>
<td> <b>qConvert.cloneObj</b>({a:1, b:2}); <hr/> <p><i> {a:1, b:2} </i></p> </td>
</tr>

<tr align="center">
<td> Array </td>
<td> <b>cloneArray</b> </td>
<td> Clones assigned array into temporary memorary for safe use</td>
<td> <b>qConvert.cloneArray</b>([1,2,3]); <hr/> - </td>
</tr>

<tr align="center">
<td> Date </td>
<td> <b>cloneDate</b> </td>
<td> Clones assigned Date into temporary memorary for safe use</td>
<td> <b>qConvert.cloneDate</b>(new Date()); <hr/> - </td>
</tr>

<tr align="center">
<td> Number </td>
<td> <b>isBigger</b> </td>
<td> Compares two numbers </td>
<td> <b>qConvert.isBigger</b>(3,7); <hr/> false </td>
</tr>

<tr align="center">
<td> Number </td>
<td> <b>isLess</b> </td>
<td> Compares two numbers </td>
<td> <b>qConvert.isLess</b>(4,5); <hr/> true </td>
</tr>

<tr align="center">
<td> Number </td>
<td> <b>isNegative</b> </td>
<td> Returns "true" or "false" </td>
<td> <b>qConvert.isNegative</b>(4); <hr/> false </td>
</tr>

<tr align="center">
<td> Array </td>
<td> <b>isNumerable</b> </td>
<td> Defines that collection truly contains numerable only and returns Boolean </td>
<td> 1. <b>qConvert.isNumerable</b>([1,2,3, 'a']); <br/> 2. <b>qConvert.isNumerable</b>([1,2,"3"]); <hr/> 1. false<br/> 2. true </td>
</tr>

<tr align="center">
<td> Number </td>
<td> <b>isPositive</b> </td>
<td> Returns "true" or "false" </td>
<td> <b>qConvert.isPositive</b>(4); <hr/> true </td>
</tr>

<tr align="center">
<td> Array </td>
<td> <b>findDuplicates</b> </td>
<td> Finds duplicates in array </td>
<td> <b>qConvert.findDuplicates</b>(['a', 'b', 'A', 'A', 'c']); <hr/> [{Value: 'a', Matches: 1}, {Value: 'b', Matches: 1}, {Value: 'A', Matches: 2}, {Value: 'c', Matches: 1}] </td>
</tr>

<tr align="center">
<td> Array </td>
<td> <b>findMax</b> </td>
<td> Finds maximal significance </td>
<td> <b>qConvert.findMax</b>([-1,2,35,6,4]); <hr/> 35 </td>
</tr>

<tr align="center">
<td> Array </td>
<td> <b>findMin</b> </td>
<td> Finds minimal significance </td>
<td> <b>qConvert.findMin</b>([-1,2,35,6,4, 0, -30, 31]); <hr/> -30 </td>
</tr>

<tr align="center">
<td> Array </td>
<td> <b>getUnique</b> </td>
<td> Returns unique values from array. If number repeats more than 2 times, will be repeated itself. </td>
<td> <b>qConvert.getUnique</b>([2,3,2,5,4,3,5,5,4]); <hr/> [2,3,5,4] </td>
</tr>

<tr align="center">
<td> Object </td>
<td> <b>merge</b> </td>
<td> Concat assigned objects into main </td>
<td> 1. <b>qConvert.merge</b>({a:1}, {b:2}); <br/> 2. <b>qConvert.merge</b>({a:1}, {a:3}); <br/> 3. <b>qConvert.merge</b>({a:1}, 5); <hr/> 1. {a:1, b:2} <br/> 2. {a:3} <br/> 3. {a:1}  </td>
</tr>

<tr align="center">
<td> Array </td>
<td> <b>mult</b> </td>
<td> Multiples the numbers </td>
<td> 1. <b>qConvert.mult</b>(1,2,3);<br/> 2. <b>qConvert.mult</b>("1",[4], 2); <br/> 3. <b>qConvert.mult</b>("1",[4], 2, [1.25]); <hr/> 1. 6<br/> 2. 8<br/> 3. 10 </td>
</tr>

<tr align="center">
<td> Array </td>
<td> <b>pushIfNotExists</b> </td>
<td> Insert assigned value into array if not exists </td>
<td> <b>qConvert.pushIfNotExists</b>([1,2,4], 3); <hr/> [1,2,3,4] </td>
</tr>

<tr align="center">
<td> Array </td>
<td> <b>remove</b> </td>
<td> Delete assigned values from array </td>
<td> <b>qConvert.remove</b>([1,2,3,4,5], 3); <hr/> [1,2,4,5] </td>
</tr>

<tr align="center">
<td> String </td>
<td> <b>reverse</b> </td>
<td> Reverse existing string </td>
<td> <b>qConvert.reverse</b>("hello"); <hr/> olleh </td>
</tr>

<tr align="center">
<td> String </td>
<td> <b>runFuncFromVariable</b> </td>
<td> Run function from string if exists </td>
<td> <b>qConvert.runFuncFromVariable</b>("greeting"); <hr/> greeting() </td>
</tr>

<tr align="center">
<td> Array </td>
<td> <b>subtract</b> </td>
<td> Subtracts the numbers </td>
<td> <b>qConvert.subtract</b>("hello"); <hr/> - </td>
</tr>

<tr align="center">
<td> Array </td>
<td> <b>sum</b> </td>
<td> Add the numbers </td>
<td> 1. <b>qConvert.sum</b>([1,2,3], [4]); <br/> 2. <b>qConvert.sum</b>(1,2,3); <hr/> 1. 10 <br/> 2. 6</td>
</tr>

<tr align="center">
<td> String </td>
<td> <b>toCamelCase</b> </td>
<td> Converts into Camel Case </td>
<td> <b>qConvert.toCamelCase</b>('Hello world'); <hr/> helloWorld </td>
</tr>

<tr align="center">
<td> String </td>
<td> <b>toNumber</b> </td>
<td> Converts string into number </td>
<td> <b>qConvert.toNumber</b>("3.5"); <hr/> 3.5 </td>
</tr>

<tr align="center">
<td> Number </td>
<td> <b>toThousand</b> </td>
<td> Transform number into thousand format via filter </td>
<td> <b>qConvert.toThousand</b>(1233.5"); <hr/> 1,233.5 </td>
</tr>

</tbody>
</table>