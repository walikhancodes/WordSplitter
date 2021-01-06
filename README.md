WordSplitter - 

Implemented the following string processing algorithm: given a dictionary and a string with no whitespace, determined whether or not spaces can be inserted into the string so that each resulting word exists in the given dictionary. To make things efficient, the dictionary was preprocessed into a trie (Trie.java). The program should accept the following input: 

java WordSplitter [dictionary] [string]

and the output should be the string with spaces inserted, or "No splitting found." if no such splitting exists. For example, using the sample words.txt and running:

java WordSplitter words.txt thisisthereason 

should give an output like: 

this is the reason 

while running, 

java WordSplitter words.txt zzzyyyxxx 

should give the output:

No splitting found.
