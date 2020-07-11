# Basics of JavaScript

## Questions

1. Write a function to render the following pattern in the console:
<br/>
* * * * *<br/>
* * * *<br/>
* * *<br/>
* * <br/>
*<br/>

The function needs to take a number as a parameter which represents how many asterisks are rendered on the first row.

2. Censor Words Longer Than Four Characters
Create a function that takes a string and censors words over four characters with `*`.
<br/>
<br/>
<b>Examples</b>
<br/>
<code>
censor("The code is fourty") ➞ "The code is ******"<br/>
censor("Two plus three is five") ➞ "Two plus ***** is five"<br/>
censor("aaaa aaaaa 1234 12345") ➞ "aaaa ***** 1234 *****"<br/>
</code>
<br/>
<b>Note</b>
- Don't censor words with exactly four characters.
- If all words have four characters or less, return the original string.
- The amount of `*` is the same as the length of the word.

3. Converting Objects to Arrays
Write a function that converts an object into an array, where each element represents a key-value pair.
<br/>
<br/>
<b>Examples</b>
<br/>
<code>
toArray({ a: 1, b: 2 }) ➞ [["a", 1], ["b", 2]]
<br/>
toArray({ shrimp: 15, tots: 12 }) ➞ [["shrimp", 15], ["tots", 12]]<br/>
toArray({}) ➞ []<br/>
</code>
<br/>
<b>Note</b>
- Return an empty array if the object is empty.

4. Filter Repeating Character Strings
Create a function that keeps only strings with repeating identical characters (in other words, it has a set size of 1).
<br/>
<br/>
<b>Examples</b>
<br/>
<code>
toArray({ a: 1, b: 2 }) ➞ [["a", 1], ["b", 2]]
<br/>
identicalFilter(["88", "999", "22", "545", "133"]) 
➞ ["88", "999", "22"]<br/>
identicalFilter(["xxxxo", "oxo", "xox", "ooxxoo", "oxo"]) 
➞ []<br/>
</code>
<br/>
<b>Note</b>
- A string with a single character is trivially counted as a string with repeating identical characters.
- If there are no strings with repeating identical characters, return an empty array (see example #3).

4. Return the Objects Keys and Values
Create a function that takes an object and returns the keys and values as separate arrays.
<br/>
<br/>
<b>Examples</b>
<br/>
<code>
keysAndValues({ a: "Apple", b: "Microsoft", c: "Google" })
➞ [["a", "b", "c"], ["Apple", "Microsoft", "Google"]]
<br/>
keysAndValues({ a: 1, b: 2, c: 3 })
➞ [["a", "b", "c"], [1, 2, 3]]<br/>
keysAndValues({ key1: true, key2: false, key3: undefined })
➞ [["key1", "key2", "key3"], [true, false, undefined]]
<br/>
</code>
<br/>
<b>Notes</b>
- Remember to sort the keys.
