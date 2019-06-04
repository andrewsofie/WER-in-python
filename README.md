#WER calculation in python

This file is written in python2. 
Removes punctuation and converts upper to lower case on both reference and hypothesis files. 

- Module needed:   
    - numpy  
    - string
- Usage:  
python wer.py reference.txt hypothesis.txt
or pass normalize as optional third argument to remove punctuation and make case lower in both ref and hyp files
python wer.py reference.txt hypothesis.txt normalize
- Example:
![result](result.jpg)
