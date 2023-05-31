# computer's memory is vulnerable to our nature (because of radiation reaction)

to detect errors, we add some bits to each memory **word**

a word has **m** bits, with **r** bits check, will become **n** bits **codeword**

we can detect if two **codewords** are different, by computing the EXCLUSIVE OR operation and count the number of 1 bit in the result, this called **HAMMING DISTANCE**

for example: 10**001**001 and 10**110**001 have d = 3 