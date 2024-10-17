# Project 2: Contradictory, My Dear Watson

For the second UM Data Team Club project we will be diving into Natural Language Inference (NLI). This time, our goal is to explore and analyze the relationships between different pairs of text to understand if one sentence logically follows from another. To do so, we will be attempting to solve the Contradictory, My Dear Watson challenge from Kaggle. The goal of this project is to perform two NLI models. The first one using the **BERT** (Bidirectional Encoder Representations from Transformers) model from preset, and the second one using the same model but doing **Transfer Learning**.

## Challenges
As with any data science project, we encountered several challenges. Early on, we faced difficulties installing and running the KerasNLP library, mainly due to version incompatibility issues with other dependencies. Additionally, understanding the different approaches to implementing these type of models, whether through a preset or using transfer learning, proved to be complex. Each approach came with its own challenges. We had to navigate the complexities of using a preset model versus transfer learning, each with its own demands in terms of processing and implementation. On top of that, understanding the differences between the many language models out there took some digging, as each one offers distinct advantages, whether it is better efficiency, greater accuracy, or how well it adapts to different types of data.

## The Model
BERT (Bidirectional Encoder Representations from Transformers) is a pre-trained language model based on the transformer architecture, designed to understand the context of a word by analyzing both the preceding and following words in a sentence. Its structure is made up of layers of encoders that process text bidirectionally, allowing it to capture deeper nuances in language. BERT is trained on large datasets using unsupervised tasks like masked language modeling and next sentence prediction.

When importing BERT from a preset, you're using a predefined version of the model that has already been trained on general data, such as large text corpora and books. This option is faster and more convenient because the model is ready to be used directly for tasks like classification without requiring additional training. For this instance, we were inspired by the notebook [KerasNLP starter notebook Contradictory Dear Watson by Alexia Audevart.](https://www.kaggle.com/code/alexia/kerasnlp-starter-notebook-contradictory-dearwatson)

On the other hand, transfer learning involves taking a pre-trained model like BERT and fine-tuning it for a specific dataset or task by adjusting its weights. In transfer learning, additional layers can be added to the model, and parts or the entire model can be retrained to enhance performance on a specific task. While this approach can yield better results in some cases, it is more resource-intensive and time-consuming compared to using a pre-trained model directly from a preset.

![Alt text](Images/new_BERT_Overall.jpg)

## Key Lessons
Understanding natural language inference (NLI) models, especially BERT, can seem overwhelming at first, but with time and hands-on experience, it gets easier. As we worked through the Contradictory, My Dear Watson challenge, we realized how important it is to understand BERT's structure in order to use it effectively for text classification. Importing BERT from a preset made things faster and easier, allowing us to focus more on fine-tuning the model. On the other hand, exploring transfer learning showed us the depth involved in adapting pre-trained models. This experience taught us how to balance convenience and precision, depending on the approach.

Now, having gained a deeper understanding of these models, we're excited to tackle new challenges and push the boundaries of what we can achieve. The lessons we've learned have not only sharpened our skills but also fueled our enthusiasm for diving into the next project with even more confidence and curiosity.
## References

https://www.kaggle.com/code/alexia/kerasnlp-starter-notebook-contradictory-dearwatson

https://keras.io/guides/keras_nlp/getting_started/

https://keras.io/guides/transfer_learning/

https://huggingface.co/docs/transformers/model_doc/bert

https://poloclub.github.io/transformer-explainer/

https://www.youtube.com/playlist?list=PLoROMvodv4rOwvldxftJTmoR3kRcWkJBp
