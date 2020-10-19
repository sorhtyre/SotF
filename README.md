# SotF
Permutation generator

Script accepts an input pattern in the form of ABCDEFGH, where A = first variable ... H = eigth variable

Permutation is generated via 0-9 numbers, non-repeating
Numbers used within the pattern are excluded from the permutation
Pattern can implement duplicate variables

Current limitaion is 8 digit length

Example:

./SotF -p 01AABB67
01223367
01224467
...
01995567
01998867

30 combinations created
