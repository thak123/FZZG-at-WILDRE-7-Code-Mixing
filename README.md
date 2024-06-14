# FZZG@WILDRE-7 Sentiment Analysis for Code-switched Data

## Code
- Convert the dataset into Alpaca dataset format using prepare.py
- Update the file names for train, test and (validation if any)
- Train the model using train_7b.py
- Predict/Eval using eval_7b.py
  
## Data
- [Dataset](https://github.com/wildre-workshop/wildre-7_code-mixed-sentiment-analysis)
  
## Cite
If you find our work useful kindly cite the following paper

```
@inproceedings{thakkar-etal-2024-fzzg,
    title = "{FZZG} at {WILDRE}-7: Fine-tuning Pre-trained Models for Code-mixed, Less-resourced Sentiment Analysis",
    author = "Thakkar, Gaurish  and
      Tadi{\'c}, Marko  and
      Mikelic Preradovic, Nives",
    editor = "Jha, Girish Nath  and
      L., Sobha  and
      Bali, Kalika  and
      Ojha, Atul Kr.",
    booktitle = "Proceedings of the 7th Workshop on Indian Language Data: Resources and Evaluation",
    month = may,
    year = "2024",
    address = "Torino, Italia",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.wildre-1.9",
    pages = "59--65",
    abstract = "This paper describes our system used for a shared task on code-mixed, less-resourced sentiment analysis for Indo-Aryan languages. We are using the large language models (LLMs) since they have demonstrated excellent performance on classification tasks. In our participation in all tracks, we use \textit{unsloth/mistral-7b-bnb-4bit} LLM for the task of code-mixed sentiment analysis. For track 1, we used a simple fine-tuning strategy on PLMs by combining data from multiple phases. Our trained systems secured first place in four phases out of five. In addition, we present the results achieved using several PLMs for each language.",
}

```
