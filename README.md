********************************************************************************
	
			HUFFMAN CODING IMPLEMENTATION

*******************************************************************************
Implemenattion of Huffman Coding Algorithm

Testing/Running the program : -

1) Save / Clon the repo
2) The repo consist of the files like sample.txt,sample.bin,sample_decompressed.txt
3) Run the program(huffmancoding.py) to compress the given files.

To run the program with any other sample text files of your choice :- 

EDIT the path of the sample.txt in huffmanCoding.py with your file name along with the full directory structure. 
Then running the program will create specified 2 files that is file.bin and file_compressed.txt

*******************************************************************************

Explaination :- 

This Algorithm consist of 2 functions specifically, that is compress and decompress. I had eventually broken down both of them in further more helper functions for easy implentation

Compression consist of :-

1. Making the frequency dictionary
2. Making heap using prebuilt heapq((library)
3. Merging the nodes with the minimum of the heaps and creating the BinaryTree Nodes further, which is having the value along with the frequency.
4. Making the codes
5. Encoding the text
6. padding the text to make every bits in 8 bit format
7. Making the byte array 
8. Output being stored to the file

Decompression consist of :-

1. Reading the binary file
2. Removing the padding and getting the actual text
3. Decoding the text further with the use of reverse dictionary created while doing the encoding
4. Output the decoded txt to the output file

********************************************************************************


Importance :- The algorithm compression would help to reduce the size of the actual final reduce to almost half, that is within the ration of 2:1

*******************************************************************************
