# My interview Experience
This is a space where I document my journey through various job interviews. Here, you'll find detailed accounts of my experiences, including the questions asked, my responses, and key takeaways from each interview.

## Databases
**What is the difference between SQL and NoSQL?**

## Java
**Create a class which cannot be instantiated or extended by another class**
## Technical Interviews

### Amazon Graduate Software Developer Engineer
#### Q1
The developers at Amazon are developing‘a regex matching library for their NLP use cases. A prototype regex matching
has the following requirements:
- The regex expression contains lowercase English letters, '(', ')',
'.' and '*'.
. '.' matches with exactly one lowercase English letter.
. A regular expression followed by '*' matches with zero or more occurrences ofthe regular expression
- If an expression is enclosed in parentheses '( 'and ')', it is treated as one expression and any asterisk '*' applies to the whole expression. It is guaranteed that no expression enclosed within parenthesis contains any '*' but is always followed by '*'. Also, there is no nested brackets sequence in the given regex expression for the prototype. Q
For example,
. Regex "(ab)*d" matches with the strings "d", "ababd", "abd", but not with the strings "abbd", "abab".
- Regex "ab*d" matches with the strings "abbbd', "ad". "abd", but not with strings "ababd".
- Regex "a(b.d)*" matches with the strings "abcdbcd", "abcdbed", "abed". "a" but not with strings "bcd", "abd"‘
- Regex "(.)*" matches with the strings "a", "aa", ""aaa", "b", "bb" and many more but not" "ac", "and", or ‘bcd" for example.

Given an array, arr, of length k containing strings consisting of lowercase English letters only and a string regex of length n, for each of them find whether the given regex matches with the string or not and report an array of strings "YES" or "NO" respectively.


