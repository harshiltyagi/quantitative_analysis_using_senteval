# quantitative_analysis_using_senteval

## Code

#### Dependencies
The code runs as an extension of the following libraries:
* [SentEval](https://github.com/facebookresearch/SentEval) from FAIR (modified version)
* [Flair](https://github.com/zalandoresearch/flair) from Zalando Research

#### Running the code

Install the dependencies.
```bash
pip install flair segtok bpemb deprecated pytorch_transformers allennlp
```

Run the bash script to get the data for downstream tasks.
```bash
data/downstream/get_transfer_data.bash
```
