## tensorflow seq2seq model

Given a folder that contains a 2 files, first.txt and last.txt with an equal number of lines, build a seq2seq model.
This could be a translation model, email to response model, or any other text that can be modeled as first -> last,input-> output,etc.
Both text files MUST contain the same amount of lines, each line corresponds to the other file's same line position

This code is meant to run on *nix/mac, not windows

to run:
```
source ~/tensorflow/bin/activate
python translate.py --data_dir ~/data_sets/eng-fren/
```


the data dir assumes that there are 2 txt files.  

you will need files with at least 1000 lines, but realistically you will need millions of lines to build a model that makes sense
