# vim

## insert mode

O - insert above
o - insert below
ci" - change inner " (replaces all text within ")

## motions

w - forward word (until punctuation or after whitespace)
W - forward WORD (until after whitespace)
b - back word
B - back WORD
e - end of word (last letter)
E - end of WORD
ge/gE - end of last word/WORD
]{x} - unmattched x (eg., ]} unmatched } )

f{X} - find character X in line
F{X} - find previous X in line
t{X} - unTil character (character before X)
T{X} - unTil backwards (character after X)
; - repeat find

0 - first character of line
^ - first non-blank character
$ - end of line
g_ - non-blank character at end

} - move paragraph down
{ - move paragraph up
C-D - Down page
C-U - Up page

/{pattern} -search forwards - n - next
?{pattern} - search backwards - N - previous match

gd - go to definition (semantic)
gf - go to file (import)

:\%s/foo/bar - global search and replace
