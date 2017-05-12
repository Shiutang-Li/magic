# magic
Automagic data science

## How to Install
Open terminal and go to where you want the file to be cloned to locally

### Paste this command into terminal
```git clone https://github.com/champstank/magic.git```

### How to run demo
git clone https://github.com/champstank/magic.git
cd magic/
sh magic.sh examples/text_sentiment.tsv

## Supports models for text, regression and classification

### Example run for text 
docker run --rm latest /bin/sh -c "python magic/run.py examples/sentiment.tsv"

#### Output 
<img src="https://github.com/champstank/magic/blob/master/images/text.png" width="350" height="250">

### Example run for regression 
docker run --rm latest /bin/sh -c "python magic/run.py examples/auto-mgp.csv"

#### Output
<img src="https://github.com/champstank/magic/blob/master/images/regression.png" width="150" height="100">

### Example run for classification
docker run --rm latest /bin/sh -c "python magic/run.py examples/loan_approval.csv"

#### Output
<img src="https://github.com/champstank/magic/blob/master/images/text.png" width="350" height="250">
