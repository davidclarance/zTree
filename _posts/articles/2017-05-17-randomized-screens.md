---
layout: post
title: Randomizing screens within a stage
excerpt: "Generate random orders of screens within a stage"
categories: code
tags: [Randomization]
comments: true
share: true
---


<div class="btn-group">
 <a href="https://raw.githubusercontent.com/davidclarance/zTree/gh-pages/CodeSnippets/RandomizingWithAStage/RandomizingWithAStage.txt" class="btn">Download raw text </a>
 <a href="https://github.com/davidclarance/zTree/blob/gh-pages/CodeSnippets/RandomizingWithAStage/RandomizingWithAStage.ztt" class="btn">Download ztt </a>
 <a href="https://github.com/davidclarance/zTree/blob/gh-pages/CodeSnippets/RandomizingWithAStage/RandomizingWithAStage.png" class="btn">View image</a>
</div>



### Description

1. **Author**: David Clarance. See original attribution and details below.  
2. **Purpose**: Randomize screens within a stage. Useful if you want to randomize the order of decisios made by participants. 
3. **Version**: 3.6.6


### Documentation

###### Attribution and details

This file derives from drawing numbers generated in a [randomized array](https://davidclarance.github.io/zTree/code/randomized-array/). The randomized array  method is by no means mine. It derives from the [Fisher-Yater shuffle](https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle) algorithm. I first saw it used by [Anwar A. Ruff](http://anwarruff.com/) and he provides code and a really nice, detailed explanation [here](http://cess.nyu.edu/cess-experiments/z-tree-cheat-sheet/v-random-role-assignment/). Anwar has a great set of tools for running experiments, do check out his [github](https://github.com/aaruff) page. 

###### Using the text file

To use the zTree text file, click the **Download text** button above. It will take you to a text file. Right click and "Save As" to your computer. In zTree use File > Import to read the file in. Please note that there are compatibility issues across different zTree versions so make you have a version that's the same or later than the version the file was written in.

###### Important variables in the zTree file

`order[n]` - Array that is randomized. `n` gives the length of the array.

`game_counter` - Counter variable that cycles through screens within a stage. 




