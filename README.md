# Autocorrection Algorithm
An attempt at implementing the autocorrect algorithm using edit distances and Dynamic Programming.

We use autocorrect every day on your cell phone and computer. This notebook is an attempt to replicate the same to an extent

Methodology

- Get a word count given a corpus
- Get a word probability in the corpus 
- Manipulate strings 
- Filter strings 
- Implement Minimum edit distance to compare strings and to help find the optimal path for the edits. 
- Implement dynamic programming


Similar systems are used everywhere. 
- For example, if you type in the word **"I am lerningg"**, chances are very high that you meant to write **"learning"**.
