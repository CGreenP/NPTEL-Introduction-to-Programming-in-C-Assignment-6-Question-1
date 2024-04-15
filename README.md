# NPTEL-Introduction-to-Programming-in-C-Assignment-6-Question-1
NPTEL Introduction to Programming in C Assignment 6 Question 1

# Question 1
We say that a string 's' is an anagram of another string 't' if the letters in 's' can be rearranged to form 't'.

For example, "butterfly" is an anagram of "flutterby", since a rearrangement of the first word results in the second.

We say that a position 'i' in 's' and 't' match, if 's' is an anagram of 't', and s[i]==t[i].

In this question, you will be given two words, 's' and 't'. You have to output the number of matching positions if s is an anagram of t, and -1 if s is not an anagram of t.

Input
-----
The input consists of two lines. The first line contains the first string, with length <= 100 characters. The second line contains the second string, with length <= 100 characters.

Output
------
If the first string is an anagram of the second string, then output the number of matching positions. Otherwise, print -1.

Sample Input 1
--------------
```sh
butterfly
flutterby
```

Sample Output 1
---------------
```sh
2
```

Sample Input 2
--------------
```sh
home
come
```

Sample Output 2
---------------
```sh
-1
```

# Sample Input 3
```sh
anarchy
anerchy
```

# Sample Output 3
```sh
-1
```

# Sample Input 4
```sh
cyclonepic
enolcyccpi
```

# Sample Output 4
```sh
1
```

# Sample Input 5
```sh
turingmachine
turingmachime
```

# Sample Output 5
```sh
-1
```

# Sample Input 6
```sh
abacbstuvab
baabctsuavb
```

# Sample Output 6
```sh
3
```
