# Project 2: Contradictory, My Dear Watson

For the second UM Data Team Club project we will be diving into Natural Language Inference (NLI). This time, our goal is to explore and analyze the relationships between different pairs of text to understand if one sentence logically follows from another. To do so, we will be attempting to solve the Contradictory, My Dear Watson challenge from Kaggle. The goal of this project is to perform two NLI models. The first one using the **BERT** (Bidirectional Encoder Representations from Transformers) model from preset, and the second one using the same model but doing **Transfer Learning**.

## Challenges
As with any data science project, there are challenges. Early in the project, we had difficulty installing and running the KerasNLP library (a natural language processing framework) due to version incompatibility issues with other dependencies. Also

## The Model
BERT (Bidirectional Encoder Representations from Transformers) is a pre-trained language model based on the transformer architecture, designed to understand the context of a word by analyzing both the preceding and following words in a sentence. Its structure is made up of layers of encoders that process text bidirectionally, allowing it to capture deeper nuances in language. BERT is trained on large datasets using unsupervised tasks like masked language modeling and next sentence prediction.

When importing BERT from a preset, you're using a predefined version of the model that has already been trained on general data, such as Wikipedia and books. This option is faster and more convenient because the model is ready to be used directly for tasks like classification without requiring additional training. Para este caso nos inspiramos en la notebook de [KerasNLP starter notebook Contradictory DearWatson by Alexia Audevart](https://www.kaggle.com/code/alexia/kerasnlp-starter-notebook-contradictory-dearwatson)

On the other hand, transfer learning involves taking a pre-trained model like BERT and fine-tuning it for a specific dataset or task by adjusting its weights. In transfer learning, additional layers can be added to the model, and parts or the entire model can be retrained to enhance performance on a specific task. While this approach can yield better results in some cases, it is more resource-intensive and time-consuming compared to using a pre-trained model directly from a preset.

![Alt text](Images/new_BERT_Overall.jpg)

## Key Lessons

## Future Steps

## References

https://www.kaggle.com/code/alexia/kerasnlp-starter-notebook-contradictory-dearwatson

https://keras.io/guides/keras_nlp/getting_started/

https://keras.io/guides/transfer_learning/

https://huggingface.co/docs/transformers/model_doc/bert

https://www.youtube.com/playlist?list=PLoROMvodv4rOwvldxftJTmoR3kRcWkJBp
