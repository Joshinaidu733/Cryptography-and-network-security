1. Write a C program for Caesar cipher involves replacing each letter of the alphabet with the letter 
standing k places further down the alphabet, for k in the range 1 through 25.
2. Write a C program for monoalphabetic substitution cipher maps a plaintext alphabet to a ciphertext 
alphabet, so that each letter of the plaintext alphabet maps to a single unique letter of the ciphertext 
alphabet.
3. Write a C program for Playfair algorithm is based on the use of a 5 X 5 matrix of letters constructed 
using a keyword. Plaintext is encrypted two letters at a time using this matrix.
4. Write a C program for polyalphabetic substitution cipher uses a separate monoalphabetic substitution 
cipher for each successive letter of plaintext, depending on a key.
5. Write a C program for generalization of the Caesar cipher, known as the affine Caesar cipher, has the
following form: For each plaintext letter p, substitute the ciphertext letter C: C = E([a, b], p) = (ap + b) 
mod 26 A basic requirement of any encryption algorithm is that it be one-to-one. That is, if p q, then 
E(k, p) E(k, q). Otherwise, decryption is impossible, because more than one plaintext character maps into 
the same ciphertext character. The affine Caesar cipher is not one-to-one for all values of a. For example, 
for a = 2 and b = 3, then E([a, b], 0) = E([a, b], 13) = 3.
a. Are there any limitations on the value of b? 
b. Determine which values of a are not allowed.
6. Write a C program for ciphertext has been generated with an affine cipher. The most frequent letter of 
the ciphertext is “B,” and the second most frequent letter of the ciphertext is “U.”Break this code.
7. Write a C program for the following ciphertext was generated using a simple substitution algorithm.
53‡‡†305))6*;4826)4‡.)4‡);806*;48†8¶60))85;;]8*;:‡*8†83
(88)5*†;46(;88*96*?;8)*‡(;485);5*†2:*‡(;4956*2(5*—4)8¶8*
;4069285);)6†8)4‡‡;1(‡9;48081;8:8‡1;48†85;4)485†528806*81 (‡9;48;(88;4(‡?34;48)4‡;161;:188;‡?;
Decrypt this message.
1. As you know, the most frequently occurring letter in English is e. Therefore, the first or second (or 
perhaps third?) most common character in the message is likely to stand for e. Also, e is often seen in 
pairs (e.g., meet, fleet, speed, seen, been,
agree, etc.). Try to find a character in the ciphertext that decodes to e.
2. The most common word in English is “the.” Use this fact to guess the characters that stand for t and h.
3. Decipher the rest of the message by deducing additional words.
8. Write a C program for monoalphabetic cipher is that both sender and receiver must commit the 
permuted cipher sequence to memory. A common technique for avoiding this is to use a keyword from 
which the cipher sequence can be generated.
For example, using the keyword CIPHER, write out the keyword followed by unused letters in normal 
order and match this against the plaintext letters:
plain: a b c d e f g h i j k l m n o p q r s t u v w x y z
cipher: C I P H E R A B D F G J K L M N O Q S T U V W X Y Z
