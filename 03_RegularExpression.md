[1.Using the Test Method](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/regular-expressions/using-the-test-method)

```js
let myString = "Hello, World!";
let myRegex = /Hello/;
let result = myRegex.test(myString); // Change this line
```

[2.Match Literal Strings : การแมทช์แบบตรงตัว](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/regular-expressions/match-literal-strings)

```js
let waldoIsHiding = "Somewhere Waldo is hiding in this text.";
let waldoRegex = /Waldo/; // Change this line -- ตัวเล็กตัวใหญ่มีผล
let result = waldoRegex.test(waldoIsHiding);
```
[3.Match a Literal String with Different Possibilities](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/regular-expressions/match-a-literal-string-with-different-possibilities)
การใช้ or 
```js
let petString = "James has a pet cat.";
let petRegex = /dog|cat|bird|fish/; // Change this line
let result = petRegex.test(petString);
```
[4.Ignore Case While Matching](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/regular-expressions/ignore-case-while-matching)
แมทช์แบบไม่สนใจตัวเล็กตัวใหญ่ i = ignore case sensitive
```js
let myString = "freeCodeCamp";
let fccRegex = /freecodecamp/i; // Change this line
let result = fccRegex.test(myString);
```

[5.Match Literal Strings](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/regular-expressions/extract-matches)  
- ดึงค่าที่แมทช์ออกมาใช้ต่อโดย .match()
- ใช้สลับกันกับ .test()
- .test() ใช้ regEx.test(string)
- .match() ใช้ string.match(regEx)

```js
'string'.match(/regex/);
/regex/.test('string');
```

```js
let extractStr = "Extract the word 'coding' from this string.";
let codingRegex = /coding/; // Change this line
let result = extractStr.match(codingRegex); // Change this line
```
```js

```
