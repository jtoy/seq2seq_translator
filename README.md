## tensorflow seq2seq model

Given a folder that contains a 2 files, first.txt and last.txt with an equal number of lines, build a seq2seq model.
This could be a translation model, email -< response model, or any other tetx that can be modeled as first -> last.
Both text files MUST contain the same amount of lines, each line corresponds to the other file's same line position

This code is meant to run on *nix/mac, not windows

to run:
```
source ~/tensorflow/bin/activate
python translate.py --data_dir ~/data_sets/eng-fren/
```


the data dir assumes that there are 2 txt files.  


