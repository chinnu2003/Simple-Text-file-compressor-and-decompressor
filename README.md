# Simple-Text-file-compressor-and-decompressor

This project is based on Huffman Coding, a lossless, bottom-up compression algorithm. 
It can compress and decompress any text files.

## Implementation in Project
This project supports two functions:
1) Encode: Compresses input file passed.
2) Decode: Decompresses Huffman coded file passed back to its original file.

## How to run this project?
To run this project you need to create an executable file.

### For compression
1)'g++ encode.cpp huffman.cpp -o main' // create main.exe file
2)'./main xxxxx.txt compressedFile.huf'

### For De-compression
1)'g++ encode.cpp huffman.cpp -o main' // create main.exe file
2)'./main xxxxx.txt compressedFile.huf' // create outputfile.txt

## Result: 
This project is just an implementation of Huffman coding, 
it is not as efficient as the compression algorithm used currently to compress files.
