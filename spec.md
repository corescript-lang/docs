# Revision and Specification
## April 2017
- Commands: print, message, set=, printf
- Run JS code with ()
- Print variables with parenthesis (`print Hello, (name)`)
- Make and set variables with `set=` (`set=name=Jimmy`)
- Comments start with `##` and end with newline.
- Alert box `message Hello, World`

## November 2017 (first release)
- Commands: print, printf, var, input, cls, msg, set, if, goto, play, not, stop, button
### Added Commands:
- var: `var name=Jim`
- input: `input key=Press a key`
- msg: (changed from `message`)
- set: `set name=John`
- if: `if name=Jim 42` (if name is "Jim", goto line 42)
- not: opposite of `if`
- goto: `goto 47`
- play: `play https://example.com/audio.mp3`
- stop: halts program
- button: `button [Start game]=10` (make a text button, goto 10 when pressed)
