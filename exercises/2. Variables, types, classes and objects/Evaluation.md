## Purpose
Use the "Console.WriteLine()" method to train your comprehension of how expressions evaluate and in which order operators have priority.  

## Setup
Open your console app if you already have one or start a new from the template in Visual Studio. In the exercises on the following pages, several expressions will be listed. First try to figure out the result of the expression. Then either replace the previous expression in your Console.WriteLine() method or add a new line and method. Run the app and check the actual result. There are three pages of expressions. Wait a while between each set of exercises. Do something else in this period. 

## Reference
The expressions use a couple of types:
Text are of type string. 
Numbers are of type int.
The either or value false and true is of type bool.

Operators evaluates in the following order:
| Sign | Name |
|---|---|
| Statements within () | Parentheses |
| *, /, %  		|		Multiplication / Division / Modulus
| +, -  	|			Addition / Subtraction
| ==, !=, <, >, >=, <=  |		Comparisons
| &&, \|\|  	|			AND / OR
| ? :  			|	Ternary Operators
| =  			|	Assignment Operators

List of comparisons
| Sign   | Name  |
|---|---|
| 1 == 1 	|		EQUAL TO
| 1 != 2 	|		NOT EQUAL TO
| 1 < 2 	|		LESS THAN
| 1 <= 2 and 1 <= 1 |	LESS THAN OR EQUAL TO
| 2 > 1 	|		GREATER THAN
| 2 >= 1 and 1 >= 1 |	GREATER THAN OR EQUAL TO
| true && true |		AND, joins two comparisons, true if both are true
| true \|\| false 	|	OR, joins two comparisons, true if either is true
|true ^ false 	|	XOR, joins two comparisons, true if one is true, but not both

## Exercise 1

```
"Hello" + " " + "World!"
2 + 4
"2" + "4"
2 + "4"
"2" + 4 + 7
3 + 5 + "=" + 3 + 5
6 + 2 + "3"
"Two" + "Three"
1 + 2 + "Three"
4 > 2
34 < 32 + 4
33 != 33
34 - 2 == 36
34 + 2 != 36
34 + 2 >= 36
34 - 2 > 36
4 == 4 ? "One" :  "Two"
```

## Exercise 2


```
1 + " " + "="
3 + 6 * 2
"2" + 3 * 2
2 + 3 + "4" + 4 / 2
"2" + 7 - 4 
7 / 3
2 * ( 4 + 2)
3 + ( 5 + "G")
1+ 4 / 3
3 == 3 && 4 != 6
3==4 || 4 != 4
4 > 9 ? "Lucene" : 4 + 89
```

## Exercise 3


```
"No" + " " + "way"
4 + 6
"3" + "9"
1123 + "23"
"43" + 2 + 5
100 + " " + "+"
56 + 5 * 6
"1" + 1 * 1
1 + 11 + "1" + 11 / 11
"34" + 2 - 1 
13 / 2
4 * ( 5 - 3)
9 + ( 2 + "OH")
12 + 12 / 4
9 == 9 && 893 != 891 + 2
8 == 4 / 2 || 4 != 4 / 2
2 + 8 + "=" + 2 + 8
45 - 40 == 50 ? 3 + 6 : 6 + "3"
```