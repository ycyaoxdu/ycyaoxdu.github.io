+++ 
draft = false
date = 2022-10-22T10:36:46+08:00
title = "Vim Skills"
description = ""
slug = ""
authors = ["Yuchen YAO"]
tags = []
categories = ["Learning"]
externalLink = ""
series = []
+++

## Numbers 
we can use numbers to make command execuate several times.\
Such as:
`number + direction/word` to "jump", such as: 7l, 2k, 8w, 4e,
`number + G` to number-th line



## Navigate

&nbsp;&nbsp;    - `%` : jump between paired brackets. \
direction: \
&nbsp;&nbsp;    - `h` : left \
&nbsp;&nbsp;    - `j` : down \
&nbsp;&nbsp;    - `k` : up \
&nbsp;&nbsp;    - `l` : right \
word: \
&nbsp;&nbsp;    - `w` : to the start of next word \
&nbsp;&nbsp;    - `b` : to beginning of the word \
&nbsp;&nbsp;    - `e` : to end of the word \
screen: \
&nbsp;&nbsp;    - `H` : top of screen \
&nbsp;&nbsp;    - `L` : bottom of screen \
line: \
&nbsp;&nbsp;    - `0` : the beginning of the line \
&nbsp;&nbsp;    - `$` : the end of the line \
file: \
&nbsp;&nbsp;    - `gg`: the beginning of the file\
&nbsp;&nbsp;    - `G` : the end of the file


## Find and Search
### Find
character: \
&nbsp;&nbsp;    - `f` : next character, `fi` finds next i\
&nbsp;&nbsp;    - `F` : previous character, `Fi` finds previous i\
word: \
&nbsp;&nbsp;    - `*` : next word same as the one under cursor\
&nbsp;&nbsp;    - `#` : previous word same as the one under cursor


### Search 
&nbsp;&nbsp;    - `/ + text +'enter'` : search the target text\
&nbsp;&nbsp;    - `n` : for next\
&nbsp;&nbsp;    - `N` : for previous


## Insert
&nbsp;&nbsp;    - `i` : insert from the cursor\
&nbsp;&nbsp;    - `I` : insert from beginning of the line\
&nbsp;&nbsp;    - `a` : append to the cursor\
&nbsp;&nbsp;    - `A` : append to end of the line\
&nbsp;&nbsp;    - `s` : delete the character under the cursor and insert\
&nbsp;&nbsp;    - `S` : delete the line and insert\
&nbsp;&nbsp;    - `o` : new line below\
&nbsp;&nbsp;    - `O` : new line above


## Delete: 
&nbsp;&nbsp;    - `x` : delete the character under the cursor\
&nbsp;&nbsp;    - `X` : delete the character before the cursor(backspace)\
&nbsp;&nbsp;    - `d` : delete and copy\
combined command:     `dw` delete the word, `d2e` , `d2w`
        

## Replace:
&nbsp;&nbsp;    - `r` : replace the character under the cursor


## Repeat:
&nbsp;&nbsp;    - `.` : repeat the command\
&nbsp;&nbsp;    - `number + insert + word + esc + - ` : repeat a word many times, 5igo'esc'- means repeat go 5 times('esc' means press the key esc)\
&nbsp;&nbsp;    - `~` : to upper/lower


## Copy & Paste
Copy: `yy`\
Paste: \
 &nbsp;&nbsp;       - `p` : paste behind\
&nbsp;&nbsp;        - `P` : paste before


## Undo & Redo
&nbsp;&nbsp;    - `u` : undo.
&nbsp;&nbsp;    - `'ctrl' + R` : redo.



## Commands
&nbsp;&nbsp;    - `v` : visual mode\
&nbsp;&nbsp;    - `:w` : save\
&nbsp;&nbsp;    - `:q` : quit\
&nbsp;&nbsp;    - `:q!` : force quit\
&nbsp;&nbsp;    - `:help` : help

