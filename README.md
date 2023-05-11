# Text Summarization using different LLM's

## Overview
* In these notebooks we are using different LLM's models to do text summarization.
* Our objective is to fine-tuned these models on financial dataset **[FINDSum](https://github.com/StevenLau6/FINDSum)** and compare different LLM's


## About Dataset
* We are using **[FINDSum](https://github.com/StevenLau6/FINDSum)** dataset which have financial paragraphs and there summaries.
* We have build a sample dataset from `FINDSum-Liquidity/liquidity_input_2000/` where we got train, test and val datasets.
* You can find [preprocess.ipynb](https://github.com/ianuragbhatt/text-summarization/preprocess.ipynb) where we have extracted the sample datasets.


## Summarization

IPython Notebook(s) for text summarization.

| Notebook | BLEU Score | Description | 
|--------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| [ts_abstractive_GPT2.ipynb](https://github.com/ianuragbhatt/text-summarization/blob/main/ts_abstractive_GPT2.ipynb) | 0 | Fine-tuned GPT2 on FINDSum `samples=1322` to do abstractive summarization.|
| [ts_abstractive_T5.ipynb](https://github.com/ianuragbhatt/text-summarization/blob/main/ts_abstractive_T5.ipynb) | 0 | Fine-tuned T5 on FINDSum `samples=1322` to do abstractive summarization.|

<!-- ## Extractive

Jupyter Notebooks with Extractive Summarization

| Notebook | Description | BLUE Score |
|--------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| [ssm-lambda.py](https://github.com/ianuragbhatt/datascience-jupyter-notebooks/blob/master/aws/ssm-lambda.py) | Fetch online SSM instance details using LAMBDA. | 0.00 | -->

## credits

* [Template for this repository](https://github.com/donnemartin/data-science-ipython-notebooks) by Donne Martin
* [FINDSum Dataset](https://github.com/StevenLau6/FINDSum)

## contributing

Contributions are welcome!  For bug reports or requests please [submit an issue](https://github.com/ianuragbhatt/text-summarization/issues).

## contact-info

Feel free to contact me to discuss any issues, questions, or comments. I don't use twitter that much So, you can ping me on gmail and Linkedin

* Email : [anur4g.bhatt@gmail.com](mailto:anur4g.bhatt@gmail.com)
* Medium : [ianuragbhatt](https://ianuragbhatt.medium.com/)
* Twitter : [@ianuragbhatt](https://twitter.com/ianuragbhatt)
* GitHub : [ianuragbhatt](https://github.com/ianuragbhatt)
* LinkedIn : [ianuragbhatt](https://www.linkedin.com/in/ianuragbhatt)
