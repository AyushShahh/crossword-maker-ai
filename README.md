# Crossword Maker AI
Given a set of words and structure, it will generate a possible crossword.

```
$ python generate.py data/structure3.txt data/words2.txt output.png
█████████████████████████
█████████████████████████
█████████████████████████
█SOPHISTICATED██RESPECT██
█Q██O██H█O█U█E███P█A█O███
█U██W██E█R█B█S██DISTANT██
█ENTERTAINMENT███S█I█C███
█E██V██T██E██R██FOREVER██
█Z██E██E██A██O███D█N█R███
█EXTRAORDINARY██MEETING██
█████IN█████U███R████████
█████ME█████BASIS████████
████A██N██████T██████████
████SIDE██████R██████████
████I██R██████I██████████
████A██V██████K██████████
████N██E████CLEAR████████
█████████████████████████
█████████████████████████
█████████████████████████
```

![](output.png)

Usage:<br>
```
$ python generate.py structure words [output]
```

- structure: path to the structure text file
- words: path to the words text file
- [output]: name of the output png file (optional). If not specified, it will only print crossword to terminal

Example structure file:<br>
```
##############
#######_####_#
#____________#
#_#####_####_#
#_##_____###_#
#_#####_####_#
#_###______#_#
#######_####_#
##############
```

_ represents an empty box where a letter needs to be placed, # represents solid blocks.

words text file should contain each word on a new line.