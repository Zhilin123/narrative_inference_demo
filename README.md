Demo

Please download pretrained weights beforehand. 

Requirements

python 3.6

To install all requirements, run pip install -r requirements.txt

Data Format 

The code assumes the input text is in a json-formatted file with the following keys:

'id': unique id for each narrative

'full_context': the narrative split into a list of sentences 


Generation

Para-M: python demo.py --model_path /path/to/modeldir/ --model_type 'nomem' --decoding beam --beam 10 --source example.jsonl

Para-M (mem): python demo.py --model_path /path/to/modeldir/ --model_type 'mem' --decoding beam --beam 10 --source example.jsonl 

Citing 

Link: https://arxiv.org/abs/2010.01486
