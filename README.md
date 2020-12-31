# The Playfair Cipher
This is an improved version of basic substitution ciphers. This symmetrical digramatic cipher uses a 5x5 matrix and the English alphabet
to code messages with a key (often the cipher text is seen as pairs of letters).

## Why Did I choose to do this
Honestly, it was because of a movie. I was watching the National Treasure movies and in the second one, one of the clues is extracted by
solving a playfair cipher. It was really cool to me and having done substitutions ciphers in class, I thought this would be a good exercise in 
the basics of cryptography.

#How does it work?

##To encrypt something:
Download the playfairencription.py file, make sure you're in the right directory, and run:
`python3 ./playfairencription.py`

You'll be initally asked for the key:
`Enter Key: `
After that you enter the plain text (what you want to encrypt),
`Plain Text: `
The script will produce a ciphered text:
`Cipher Text: `

###Example of encription:
`python3 ./playfairencription.py`

`Enter Key: Playfair Example`
`Plain Text: Hide the gold in the tree stump`
`Cipher Text: BM OD ZB XD NA BE KU DM UI XM MO UV IF`

##To decrypt something:
Download the playfairdecription.py file, make sure you're in the right directory, and run:
`python3 ./playfairdecription.py`

You'll be initally asked for the key:
`Enter Key: `
After that you enter the cipher text (what you want to decrypt),
`Cipher Text: `
The script will produce a deciphered text:
`Plain Text: `
###Example of encription:
`python3 ./playfairencription.py`

`Enter Key: Playfair Example`
`Cipher Text: BM OD ZB XD NA BE KU DM UI XM MO UV IF`
`Plain Text: HI DE TH EG OL DI NT HE TR EX ES TU MP`

You will get the decripted in pairs, I couldn't be bothered to put it back together. Especially with the extra X due to the encription and decription process.

If you have any changes in mind that you think will help this code run better / faster, let me know.

###Lastly, enjoy!
