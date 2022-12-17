# CS 101 Project 5: Binary Tree From In Order and Level order Traversals
## Project Description:
In this project we were to take in input from three input files given as command line arguments containing an In Order traversal, a Level Order Traversal, and a Huffman Encoded message. From these traversals we were to construct a Huffman Tree and decode the message to print to standard out.

## Implementation:
In order to properly take in the input files, I created three filestreams from the In Order traversal (argv[1]), Level Order traversal (argv[2]), and the Huffman encoded message (argv[3]).  I then created two vectors to store the information from the In Order and Level Order Traversals. I then had to create a Binary Tree class with various constructors, the copy constructor, assignment operator constructor, and the destructor, which satisfies the rule of three. I then created a function that created a tree from the two traversals recursively. After creating the tree from the traversals, I then created a decoded string that was empty initially and concatenated on the results of the Huffman tree decoding.

## Conclusion
I felt that this project was relatively simple for me. It reinforced my ability to both build trees from traversals and Huffman decoding. I also was able to practice fully implementing a class with constructors, destructors and all. I felt that this project really reinforced my ability to translate an algorithm into code.