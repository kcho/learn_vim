# Learn_vim

Learn VIM keys


## Contents

1. Target audience
1. VIM
2. Plan
3. Basic keys
4. VIM basic configuration
5. Change file structure using vim
6. Adding a column to a csv file
7. Softwares used


## 1. Target audience

- People who
    - use terminal on daily basis
    - edit text files on daily basis
    - work with any type of programming script
    - work with a fair number of consistently named files (~ 1000)

+ people who work with MR neuroimaging data


## 2. VIM

- editor, not writer
- focus on motion of the cursor



## 3. Plan

### 10, 10, 5, 4

- 10 mins a day
- 10 mins with your own document
- five days a week
- for four weeks
- daily contents will focus heavily on revision


---

## Day 1

### 1. Keep pressing `ESC` (This keeps you in the edit mode)

- You should stay in edit mode most of the times.
- Pressing `ESC` will take you to edit mode.
    - You don't have to worry about mode for now.
- Just keep pressing `ESC` button.
- Pressing `ESC` many times does not mess up the script.

![]( docs/key_movements_1_esc.gif)

### 2. Basic keys

- Do not use arrow buttons!
    - Use j,k for up and down,
    - Use h,l for left and right instead


### 3. VIM basic configuration

- Since we will be keep pressing `ESC` all the time,
    - let's map `jj` as the key for going to the edit mode.



1. open `~/.vimrc` by `vi ~/.vimrc`
2. Press `i` to enter insert mode
3. add `imap jj <ESC>` to a new line
4. Press `ESC` to enter command mode
5. type `:wq`, which means save and exit


- From now, make a habit of keep pressing `jj` all the time!


## Day 2
## Day 3
## Day 4
## Day 5
## Day 6
## Day 7
## Day 8
## Day 9
## Day 10
## Day 11
## Day 12
## Day 13
## Day 14
## Day 15
## Day 16
## Day 17
## Day 18
## Day 19
## Day 20
