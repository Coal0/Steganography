# Steganography
A python steganography tool

*DONE* *Main TODO*
1. #DONE# Main funtion to accept argument 
2. #DONE# A function what reads images and writes it to a byte-array
3. #DONE# A Encoder function
4. #DONE# A Decoder function

*Also TODO*
1. #DONE# Encrypt the text
2. #DONE# Add Code to randomize
     + Example -rgb rb # Changes only Red and Blue
     + Example -s 10   # Steps over 10 rbg arr and then changes

*New TODO*
1. #DONE# Add check if image has enough space for the string to hide
2. #DONE# Make code more readable for other programmers PEP-8
3. #DONE# Make more prints for users
4. #DONE# improve seed method
5. #DONE# **MAYBE** Add encryption from file... instead of text in command promt

*Yet Another TODO*
1. #DONE# Fake data
2. #DONE# Rename as suggested
3. #DONE# refractor usability of the code....
   - A python script that drives the command line tool
   - A module that handles LSB encoding/decoding, and operates on an image array. It should make no attempt at encryption, but simply work with whatever data is passed, whether encrypted or not.
   - A separate module to handle encryption/decryption.

*Newest TODO*
1. RSA-BASED-ENCRYPTION/DECRYPTION
2. improve location of files, so we can work with files outside of the current directory
3. complete ./install ---> Setup source controll
     Example: 
     stego/
     |------Setup/Install
     |------Test
     |------stego
          |--------module1.py
          |--------module2.py
          |-------- _init_.py
