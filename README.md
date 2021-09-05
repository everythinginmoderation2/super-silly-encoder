# super-silly-encoder
A server-side project built using Node.js that encodes and decodes messages input into the CLI.


This application offers a message-encryption service that transforms input text, using various ciphers, and displays the encrypted message to the console.

There are three encryption methods provided by this service:

A “Caesar Cipher” in which the characters of the input message are shifted alphabetically by a given amount.
A “Symbol Cipher” in which select characters from the input message are replaced with visually similar symbols.
A “Reverse Cipher” in which each word of the input message is reversed in place.

The progam contents include two files.
'encryptor.js' holds the 3 encryption methods listed above. 
'super-encoder.js' imports the module's functions and uses these methods to create a 'super' encoded message. It also provides a function to decode the output, and return a message equivalent to the user's original input (from the 'endoder' function).


Project origin:
This was originally created to simulate the process of updating an existing 'message-mixer.js' file, after creating an 'encryptor.js' module and refractoring the code to import and use exports from the module.


The simulation read as such:
"The developers over at Super Encoder LLC heard about the encryptors.js module that you just released and want to use your encryption functions to create a new program."


Usage:
The Super Encoder developers want the user to be able to use their program to encode messages and decode them using the commands below.
For encoding, use 'node super-encoder.js encode'
For decoding, use 'node super-encoder.js decode'

