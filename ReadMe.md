# Assignment 01

You will be solving the given problems below.

### Problem 01
We need you to make ___ amount of copies of a given string.
A string will be given and a non-negative number.
We need you to make the given number of copies of the original string.

Return a larger string that has n copies of the given string.

Example:
```java
stringCopies("Hi", 2) --> "HiHi"
stringCopies("Hi", 3) --> "HiHiHi"
stringCopies("Hi", 1) --> "Hi"
```

### Problem 02
Does the given string contain a first instance of "x" immediately followed by another "x"?

Evaulate the given string and return true if the first seen "x" is followed right by another "x".

Example:
```java
followedX("axxbb") --> true
followedX("axaxax") --> false
followedX("xxxxx") --> true
```
### Problem 03
Provided a given string, take note of how many times you see a substring length 2 occur.

Return the count of the number of times that a substring length 2 appears in the given string.
Also, the last 2 characters of the string, such as "hixxxhi" would yield 1; don't count the end substring.

Example:
```java
subTwo("hixxhi") --> 1
subTwo("xaxxaxaxx") --> 1
sub2("axxxaaxx") --> 2
```
### Problem 04
The new elementary school teacher wants to make a fun interactive way of learning the basic numbers.
She wants to start with learning 1,2,3, but she is providing sets of numbers for the kids to find 1, 2, 3 out of.
The sets of numbers will be given in a array for you to decided if they contain the sequence 1,2,3 anywhere within the
array.

Return true if the sequence of numbers 1, 2, 3 appears in the array anywhere.

Example:
```java
basicNumbers123([1, 1, 2, 3, 1]) --> true
basicNumbers123([1, 1, 2, 4, 1]) --> false
basicNumbers123([1, 1, 2, 1, 2, 3]) --> true
```
### Problem 05
Lets play a game of scramble the letters of any given word.
A string will be given to you, and we need you to create a new string where we will only ask for specific letters
out of the string.

Return a new string made of characters at indexes 0, 1, 4, 5, 8, 9.

So "kittens" will yield "kien".

Example:
```java
scrambleOfLetters("kitten") --> "kien"
scrambleOfLetters("Chocolate") --> "Chole"
scrambleOfLetters("CodingHorror") --> "Congrr"
```
### Problem 06
For this special case, were going to say that during a game of basketball a "triple" is when someone scores the same
point value 3 times in a row. Such as, scoring 2 points three times in a row.
We are keeping track of players point values in an array, but we don't want you to accept any player who has "triples".

Evaluate the given array and return true if the array does not contain any triples.

Example:
```java
dontAcceptTriples([1, 1, 2, 2, 1]) --> true
dontAcceptTriples([1, 1, 2, 2, 2, 1]) --> false
dontAcceptTriples([1, 1, 1, 2, 2, 2, 1]) --> false
```

### Problem 07
Provided a string, we need you to make x amount of copies of the front of a string.
The front of a string is considered to be the first 3 characters or whatever is there less than the 3 characters.

Return a new string of x copies of the front of the given string.

Example:
```java
frontCopies("Chocolate", 2) --> "ChoCho"
frontCopies("Chocolate", 3) --> "ChoChoCho"
frontCopies("Abc", 3) --> "AbcAbcAbc"
```
### Problem 08
Lets break apart the given words and make new bits. Using those new bits we will put them together to create a new string.

Return a new string made of every other character, but start with the first character.

So "Hello" yields "Hllo"

Example:
```java
everyOtherBit("Hello") --> "Hllo"
everyOtherBit("Hi") --> "H"
everyOtherBit("Heeololeo") --> "Hello"
```
### Problem 09
Sam's favorite number is 9. She wants you to count how many occurences of her favorite number that you see within
a given set of numbers.

The sets of number will be provided in an array, return the number of 9's seen in the array.

Example:
```java
favoriteNine([1, 2, 9]) --> 1
favoriteNine([1, 9, 9]) --> 2
favoriteNine([1, 9, 9, 3, 9]) --> 3
```
### Problem 10
You will be provided two strings to compare against each other.
We need you to compare to see if you see a substring in one string, that you see in the same spot in the next string.

So "xxcaazz" and "xxbaaz" yields 3, as you can see "xx", "aa", and "az" substrings appear in the same place in both.

Return the number of the positions where they contain the same length 2 substring.

Example:
```java
amIAMatch("xxcaazz", "xxbaaz") --> 3
amIAMatch("abc", "abc") --> 2
amIAMatch("abc", "axc") --> 0
```
### Problem 11
Arnold is all about having goodluck stored around him. He is a pretty lucky guy, and he wants to remain that way.
Arnold heard that the word "yak" is very unlucky. He has a group of pharses he wants to store in his "book of good pharses".

Arnold wants you to look at the given pharses and remove all the "yak", but the "a" can be any character and the "yak"
strings will not overlap.

Return a new string where all the "yak" are removed to keep him a lucky man.

Example:
```java
unluckyYak("yakpak") --> "pak"
unluckyYak("pakyak") --> "pak"
unluckyYak("yak123ya") --> "123ya"
```
### Problem 12
Given an array of numbers, we need you took look to see if it contains a 2, 7, 1 pattern.

Return true if it contains a 2, 7, 1 pattern:
a value,
followed by the value plus 5,
followed by the value minus 1.

Additionally, the 271 counts even if the "1" differs by 2 or less from the correct value.

Example:
```java
pattern271([1, 2, 7, 1]) --> true
pattern271([1, 2, 8, 1]) --> false
pattern271([2, 7, 1]) --> true
```

