# How to run

Open python3 cli in your terminal

1. Import class HuffmanCoding

## from HuffmanCoding import HuffmanCoding

2. Make a path variable. This path variable must have the location of your text file that you'd like to compress.

## path="/Users/sarvagya/Desktop/Python projects/huffman_proj/sample.txt"

3. Make an object of HuffmanCoding

## H = HuffmanCoding(path)

4. Call the compress function -

## H.compress()

5. The compressed file is stored in the same path.

To decompress the file -

Use that same object "H" to call the decompress function, pass the path of compressed file as a parameter
H.decompress('/Users/sarvagya/Desktop/Python projects/huffman_proj/sample.bin')
