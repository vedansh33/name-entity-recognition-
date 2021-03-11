# name-entity-recognition-
Named-entity recognition is a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages

# Dataset

This is the link for the [dataset](https://noisy-text.github.io/2017/emerging-rare-entities.html)


# Approach

- First I extracted the main information from the dataset to process it further.
- I used a pretrained DistilBert transformer which had a token classifier to classify the words according to thier entities
- I used DistilBert tokenizer to tokenize the words so that they can be processed by our model.

# Result

- The evaluation loss after training was .13 

# Sample Input

https://user-images.githubusercontent.com/50076662/110750474-8ab10a00-8268-11eb-854e-31ab3bf5d20a.png

## Sample Result

https://user-images.githubusercontent.com/50076662/110750474-8ab10a00-8268-11eb-854e-31ab3bf5d20a.png
