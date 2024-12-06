## Alphabets
Non empty sets of symbols (letters) are called Alphabets.
- Alphabet is represented by Σ.
**Example:** Σ={a,b}
   - Here Σ={a,b} is called Alphabet.
   - a, b are called symbols

---

## Strings
It's concatenation of finite strings.
**Example:** For Σ = {a,b}, following will be strings= a, abab, aaabb, ababababababababab

> **String with no symbol:** Sometimes a string with no symbol at all is used, denoted by (Small Greek letter Lambda) λ or (Capital Greek letter Lambda) Λ, is called an empty string or null string.

---

## Words
Words are strings belonging to some language.
**Example:** L={x^n : n=1,2,3,.....} or L={x,xx,xxx,....} then x,xx,... are the words of L.

> All words are strings but not all the strings are words.

---

## Valid/In-Valid Alphabets
For Valid Alphabet, it must be assured that the Alphabet should contain only those letters that we receive after tokenizing the string.
**Example: -** 
Alphabet = Σ = {B, Ba, bab, d}, string = BababB
No. of ways of getting tokenization of the given string:
1. (Ba), (bab), (B)
2. (B), (abab), (B)
But 1st one is valid while the 2nd is invalid.
*Reason: -*
   - In 1st, all tokens are present as symbol in the given Alphabet/language. 
   - In 2nd, one of the tokens "abab" isn't present in the given Alphabet.

> To avoid ambiguity, make sure If any letter is present in the Alphabet then It shouldn't be at the begining of another letter present in the same Alphabet.
   Σ1= {B, aB, bab, d}, Σ2= {B, Ba, bab, d}
   Σ1 is a valid alphabet while Σ2 is an in-valid alphabet.

---

### Length of String
Length of string s, denoted by |s|, is the no. of letters in the string.
**Example: -**
Σ={a,b}
s=ababa
|s|=5

---

## Reverse of String
The reverse of a string s denoted by Rev(s) or ${s^r}$, is obtained by writing the letters of s in reverse order.
**Procedure of reversing**
Let Σ= {B, aB, bab, d} and s = BaBbabBd
- Original tokens of string s = (B), (aB), (bab), (B), (d)
- Reverse their order = (d), (B), (bab), (aB), (B)
- Now, reverse character inside each token:
    - (d) = d
    - (B) = B
    - (bab) = bab
    - (aB) = Ba
    - (B) =  B
- Putting it all together, we get Rev(s) = dBbabaBB

---

## Descriptive definition of language
The language is defined, describing the conditions imposed on its words.
**Example: -**
The language L of strings of odd length, defined over Σ={a}, can be written as L={a, aaa, aaaaa,.....}

---

## PALINDROME
The language consisting of Λ and the strings s defined over Σ such that Rev(s)=s.
> *Means, If you reverse each letter of palindrome, you're going to get the same result.*

**Example: -**
For Σ={a,b},
PALINDROME={Λ , a, b, aa, bb, aaa, aba, bab, bbb, ...}

