# HW - Palindrome Detector

## I. Overview

- A *palindrome* [(wikipedia)](https://en.wikipedia.org/wiki/Palindrome) is a word, number, phrase, or other sequence of characters which reads the same backward as forward, such as madam or racecar or the number 10801. Sentence-length palindromes may be written when allowances are made for adjustments to capital letters, punctuation, and word dividers, such as "A man, a plan, a canal, Panama!", "Was it a car or a cat I saw?" or "No 'x' in Nixon".
- Composing literature in palindromes is an example of *constrained writing*.

**Below is the required functionality:**

**A. Not a palindrome!**

- the text is red, and there is an *error message*

![screenshot](_images/HW-palindrome-1.png)

<hr>

**B. Found a palindrome!**

- the text is green, and there is a *success message*

![screenshot](_images/HW-palindrome-2.png)

<hr>

**C. Not required, but here's an enhanced version that lets you keep track of your palindromes**

![screenshot](_images/HW-palindrome-3.png)

<hr>


## II. Hints

- use [this *load-text-input.html* start code](text-1.md#I-A) 
- the code snippets we used in our demo will help with stripping out spaces and punctuation, so that our palindrome detector will catch examples like *Madam, in Eden, I'm Adam.*
- make sure that you convert the string to all lowercase letters before you do the string reversal and comparison
