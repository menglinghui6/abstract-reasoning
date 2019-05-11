# abstract-reasoning

This project refers to the paper "Measuring abstract reasoning in neural networks" (https://arxiv.org/abs/1807.04225)

Data: https://console.cloud.google.com/storage/browser/ravens-matrices

Images are of size 160x160x16. The last dimension denotes the panel number for the matrix, with the first 8 panels being the "context", and the last 8 being the "choices".

NB: each matrix of context is built by randomly sampling of:
<ul>
<li> relation types (R, with elements r): progression, XOR, OR, AND, consistent union 1
<li> object types (O, with elements o): shape, line
<li> attribute types (A, with elements a): size, type, colour, position, number
</ul>


