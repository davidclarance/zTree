---
layout: post
title: Creating randomized arrays
excerpt: "Create a array with randomized numbers drawn without replacement"
categories: code
tags: [Randomization]
comments: true
share: true
---


<div class="btn-group">
 <a href="https://raw.githubusercontent.com/davidclarance/zTree/gh-pages/CodeSnippets/RandomizedArray/RandomizedArray.txt" class="btn">Download raw text </a>
 <a href="https://github.com/davidclarance/zTree/blob/gh-pages/CodeSnippets/RandomizedArray/RandomizedArray.ztt" class="btn">Download ztt </a>
 <a href="https://github.com/davidclarance/zTree/blob/gh-pages/CodeSnippets/RandomizedArray/RandomizedArray.png" class="btn">View image</a>
</div>





### Description

1. **Author**: David Clarance. See original attribution and details below.  
2. **Purpose**: Generate an array with randomized numbers drawn without replacement from a distribution. 
3. **Version**: 3.6.6


### Documentation

###### Attribution and details

This method is by no means mine. It derives from the [Fisher-Yater shuffle](https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle) algorithm. I first saw it used by [Anwar A. Ruff](http://anwarruff.com/) and he provides code and a really nice, detailed explanation [here](http://cess.nyu.edu/cess-experiments/z-tree-cheat-sheet/v-random-role-assignment/). Anwar has a great set of tools for running experiments, do check out his [github](https://github.com/aaruff) page. 

###### Using the text file

To use the zTree text file, click the **Download text** button above. It will take you to a text file. Right click and "Save As" to your computer. In zTree use File > Import to read the file in. Please note that there are compatibility issues across different zTree versions so make you have a version that's the same or later than the version the file was written in.

###### Important variables in the zTree file

`order[n]` - Array that is randomized. `n` gives the length of the array.


