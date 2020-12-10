# RSA
Sharing a simple working RSA algorithm in C

I had a hard time finding a simple working RSA algorithm for my project. So I some improvements to 
[this RSA algorithm](https://d3c33hcgiwev3.cloudfront.net/_24f8f0f03c28125c673fd64ce47b253a_rsa.c?Expires=1607731200&Signature=NjPTYrZzCNUskBgDjkHW-x3Hv4YakUGIRoX01XfCQtQD6NcBIBRFBoOuSSyQskuhawDZgAJXf9VJlVvxbK56y~uMx1b2KosOJhTNNRlTdIk8nNh5NTn1zmQGCaRkoIkc-zq5HE1L5flsZumXdd7LR7mJLcUpKqnX9I3Kb72hZWM_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A) shared by Coursera. As it took me some hours, I'm sharing this to whoever could make use of it :)

Steps:
1) Change d, e and n in the defines
2) Change the value of INPUT_FILE to the file you need to encrypt
3) Change the extension of DECRYPTED_FILE to the same of the INPUT_FILE
4) Use GCC to compile: "gcc rsa.c -o rsa"
5) ./rsa

2 files will be created:
 - encrypted.bin -> the file encrypted by RSA
 - decrypted.bmp -> the file 
