## tensorflow seq2seq model
this is based off tensorflow's seq2seq code, but with slight modifications and generalized so any dataset can be applied to it

Given a folder that contains a 2 files, first.txt and last.txt with an equal number of lines, build a seq2seq model.
This could be a translation model, email to response model, parser model, or any other text that can be modeled as:
input-> output
Both text files MUST contain the same amount of lines, each line corresponds to the other file's same line position

This code is meant to run on *nix/mac, not windows

to train:
```
source ~/tensorflow/bin/activate
python main.py --data_dir ~/data_sets/eng-fren/ --train_dir ~/train_dir
```

to inference:
```
source ~/tensorflow/bin/activate
python main.py --train_dir ~/train_dir  --decode True --input "hello world"
```

the data dir assumes that there are 2 txt files.  

