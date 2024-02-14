# WhiteSpace

What is _whitespace_ in coding? What is whitespace in a text file?
Well, we are told that _whitespace_ doesn't matter in Java.

Yes. a _space_ character is _whitespace_ (like in this string, between the double quotes, `" "` there is One space)

There is a few test data files in the top level of this repo.
Write a method in class `Whitespace` called `countBoth(String input)` that prints out the number of whitespace 
characters found, and the number of non-whitespace characters found. Your output should match the answers below.

You are __not_ allowed to use the `Character.isWhitespace()` method in your solution. 
(But you should read about it, so you know what you're trying to write.)

If the input string is `"This is a string."` your `countBoth` should print

```
3, 14
```
Notice the comma!

If the data file contains 

```
Zip Code Wilmington
creates
Great Coders.
```

Output should be....

```
5, 34
```

(Yes, really)

when you read in the testdata files, your program should print

```
5, 36
52, 276
234, 1089
```

as output. first line is testdata1, then 2, then 3.

