# Automatic evaluation Metrics of Knowledge-intensive LongText Generation

## Setup
```
cd NLG_evaluation
pip install -r requirements.txt
```
## Generation
wiki_new.json and wiki_old.json are 
One can run the following to create one generation experiment.  
```
python main.py -g -m gpt2 -p /scratch/yd2481/NLG_evaluation/wiki_old.json --top_p 0.7 --temperature 0.1 -o ./generation_new
```
We do not suggest you

## Evaluation
```
python main.py -e -o /generation
```

## Results

