# cube

![https://asciinema.org/a/609595](cube_demo.gif)

## Things that work:

- virtual cube
- adjustable scale
- configurable keybindings
- mediocre keybindings display

## Things that are yet to come:

### better keybindings display

instead of opening as a full screen help menu like most programs, i would
rather it be more of a "cheat sheet". I want the face moves and the rotations
on the left side, and the wide moves and the slice moves on the right. Since
there are the same amount of face moves as there are wide moves, but the slices
and rotations are half as much each, putting face with rotations and wide with
slices will make both sides balanced.

they will support a maximum of 5? 8? keys defined per move

- by this i mean, things may overlap if you have more than that

they will position themselves nicely, i've yet to decide how they will look
if the window gets small enough that the cube cannot fit with the help
displayed as well, the cube will shrink before the help goes away

- this shrinking concerns me, because i'd already been thinking about a user
configurable "desired size" that would be tracked separately from current size

since the cube will shrink if it doesn't fit, i thought it may be nice for it
to expand again if you make the window bigger

maybe any of this auto-sizing business can just get thrown out, if the cube
doesn't fit then print a message that says "hey cube doesn't fit at that scale,
shrink it with these keys '', current scale x" or whatever.

either way, if the help makes the cube shrink, then if i take the help away
would the cube get bigger?

I think the help should never make the cube shrink

if the help won't fit on screen, then it should go away (or say something like
space available)

i dunno i have to see what other people do
nah screw that i'll make my own decision

i checked anyway, seems like other programs will make things small to a point,
then stuff that doesn't print is just getting cut off

wonder how I should do that
