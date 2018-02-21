# Replace
This is a program that will convert text to custom characters or grawlix.

## Description
Grawlix is often used in comic books to depict the expression of anger.
This program will take a string and determine the amount of characters in that string.
After the program has determined the amount of characters it will look for vowels and draw grawlix in the following
pattern; '@#$%!&?'. You can also use this program to draw custom characters in a style of choice.

## How to use
In your command line install Replace with
`npm install replace`

## Usage & Examples
```
//First we need to set a word as a variable so that we can run "replace" on it
var word = Voldemort

//Replacing vowels
replace.vowel(word); //V*ld*m*rt

//Replacing inner characters of a word
replace.inner(word) //V*******t

//Draw the word in grawlix
replace.grawlix(word); //@#$%!&?@#

//You can also set parameters for each of these to customize your vowels, inner characters, or grawlix
replace.vowel(word, '^'); V^ld^m^rt

 ```
## License

@ISC Felix den Heijer
