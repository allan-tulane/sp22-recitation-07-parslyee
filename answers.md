# CMPS 2200 Recitation 7
## Answers

**Name:**Lily Yee


Place all written answers from `recitation-07.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt    |1340|826|0.61641791
alice29.txt    |1039367|676374|0.65075570
asyoulik.txt    |873253|606448|0.69209235
grammar.lsp    |26047|17356|0.66633393
fields.c    |78050|56206|0.72012812

There is a consistent trend of Huffman coding costing approximately 66% of the time that fixed length encoding costs.




- **e.**

In this situation, each character has the same frequency, so the finding the Huffman coding cost requires multiplying the length of the encodings and the frequency. Huffman coding will result in a balanced tree. Assuming that there are N leaves, the expected cost will be n log n and this will be consistent across the documents. 
