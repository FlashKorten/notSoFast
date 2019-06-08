## What is this?
```
'notSoFast' is a thin wrapper for mplayer to repeat slowed down sections of songs
(or anything else mplayer plays). mplayer has to be in execution path.
```

## How do I use it?
```
USAGE: notSoFast <FILE>
   appendable parameters:
     -s seconds [starting offset       | default:         0 ]
     -d seconds [duration              | default: unlimited ]
     -l loops   [number of repetitions | default: unlimited ]
     -t         [use scaletempo filter | default:        no ]
     -f speed   [use factor for speed  | default:       1.0 ]
     -h         [print this message    | default:        no ]
```

## Could you give an example? I'm confused...
```
Example: notSoFast foobar.ogg -s 93 -d 7 -l 4 -t -f 0.86

         repeats foobar.ogg from 1:33 to 1:40 for 4 times
         at 0.86 the normal speed without changing pitch
```

## I'm still confused - but thanks anyway ;)
