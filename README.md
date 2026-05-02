# The-Ultimate-Guide-to-Vim
Everything you need to go from confused to confident in Vim. :scroll:

<img src="https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/vim-icon.png" alt="vim icon" style="width:300px">

##### before enter any commands below ESC needs to be pressed

## Basic Movement
_pick h and j keys with your right hand indicator_
```
h j k l => left, down, up, right
w b => next word, previous word (this turns you 80% faster)
0 => begining of line
$ => end of line
gg => go to top of file
G => go to end of file
Ctrl+d, Ctrl+u => scroll page by a half down or up
```

## Basic Insert
```
i => insert before cursor
a => insert after cursor
I => insert in start of a line
A => insert in end of a line
o => insert in line below
O => insert in line above
```

## Save and Exit
```
:w => save
:q => quit
:wq => save and quit
:w! => force save
:q! => force quit
```
**Tip**: to save and exit with no need of above commands just press SHIFT+ZZ

## Edit
```
x => cut a line
dd => delete a line
yy => copy a line
p => paste a line
u => undo a change
Ctrl+r => redo a change
```

## Selection
```
v: normal selection
V => select a whole line
Ctrl + v => block selection
```

## Searching
```
/texto → forwards search
?texto => backwards search
n => go to next term in search
N => go to previous term in search
```

## Divine Magic Initiation
```
dw => erase word near cursor
d$ => erase a whole line
cw => change word near cursor
ci" => change content inside " at a line
di( => erase a whole content inside parenthesis
. => repeat last action
% => jump over parenthesis, curly braces and brackets
(>> or <<) => indent forward or backwards
* => jump to next same term in file near cursor
```

_Congrats! now you now how to quit in vim._
