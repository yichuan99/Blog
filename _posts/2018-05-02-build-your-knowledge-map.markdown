---
layout: post
title:  "Build Your Knowledge Map"
date:   2018-05-02 10:37:30 +0000s
categories: thoughts
---

If I want to fully understand the source code of LevelDB (just an example), how should I do it?

First, apply the NIMI (name, interface, model, implementation) analysis to the problem:

Name: LevelDB

Interface: A database that stores key-value pair.
 
Model: This is hard to capture at first glace, but here are some keywords that we can start with:
1. LSM Tree
2. Non-relational Database
3. Architecture: Write(k,v), Op log, memtable，Immutable memtable，sstable，manifest，LevelDB, current
4. Implemented in C++

Implementation:
https://github.com/google/leveldb

It seems to me that I barely understand anything in the model, let along the implementation. So here is my first conclusion of this state:
Have no idea about the model of the system, so do not think about diving into implementation. 

Here is my step 1:
Use a BFS manner learning to understand keywords in model a little better. After that, use depth-limited DFS to go over all the concepts in the model. 

There is no step 2 yet, because my current knowledge does not support me to do that. Step 2 will be designed after I finish at least 50% of step 1. 

As you can see, this is my attempt to systematically learn some complex thing on my own. It's exciting because it's me applying some of my own learning system, not any professors'. Let's see how it goes. 