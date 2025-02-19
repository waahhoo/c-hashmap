# C Hashmap
This is my implementation of a hashmap in C. It is completely functional. The makefile and testy doesn't work for some reason, so sorry about the testing if you wanted to run tests. However, all of the functions work as desired (and there are a ton of long comments to explain what each one does).

# Overview
The main files with code are hashmap_funcs.c and hashmap_main.c for this project. You can feel free to look through them, I did my best to make them readable, but in the end, C is annoying and hard to understand unless you know C already.

The hashmap_funcs.c file has all the code for the actual hashmap implementation, so if you're only interested in the hashmap itself and what it can do, go there.

# Hashmap_funcs.c
For more in-depth documentation, look at in-code comments.
The hashmap generates a hashcode for the key for placement in the map later. There are also functions for initializing the hashmap (`hashmap_init`), as well as functions for putting and getting keys into the map (`hashmap_put`, `hashmap_get`).
There is also a function for freeing the memory used for the hashmap, saving the hashmap to a file, loading a hashmap from a file, and a helper function for displaying the hashmap itself.
Lastly, there are two functions (`next_prime`, `hashmap_expand`) for expanding the size of the hashmap once the load gets too high.

# General Stuff
It's been a while since I've used C, so probably a lot of this code is really inefficient and not very good. This is just an old project I did to work on C, data structures, and memory allocation.
