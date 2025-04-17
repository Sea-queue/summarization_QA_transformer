# Project Overview: 
In this project, we built a Transformer-based text summarizer from scratch using PyTorch. <br>The idea was to take research paper abstracts from the arXiv dataset and generate their titles automatically. We didn’t use any pre-built models instead, we coded everything ourselves, including the attention layers and positional encodings. We also trained our own tokenizer using Byte Pair Encoding. The model was trained on a small portion of the data and evaluated using ROUGE, BLEU, and BERTScore. Doing it all manually helped us really understand how Transformers work under the hood.


How to Run:
1. Install dependencies:<br>
```pip install datasets tokenizers rouge_score bert_score nltk```<br>

<i>Note: The code to install the dependencies is already present in the notebook . You can run it by executing the cell containing the code.

2. Run the notebook cells in order.

3. Visualizations and generated summaries will appear as output cells.