# LLMs-CheatSheet

## Which technique helps mitigate bias in prompt-based learning?

`Prompt Calibration` because prompt calibration involves adjusting prompts to minimalize bias in the generated outputs.
Fine-tuning modified the model itself, while data augmentation expands the training data.
Gradient clipping prevents exploding gradients during training.

## Do you need to have a vector store for all your text-based LLM use cases?

No, a vector store is used to store the vector representation of a word or sentence.
These vector representations capture the semantic meaning of the words or sentences and are used in various NLP tasks.
However, not all text-based LLM use cases require a vector store.
Some tasks, such as summarization, sentiment analysis, and translation, do not need context augmentation.
Here is why:
* **Summarization**: This task involves condensing a larger body of text into a short summary.
It does not require the context of other documents or sentences beyond the text being summarized.
* **Sentiment Analysis**: This task involves determining the sentiment (positive, negative, neutral) expressed in a piece of text.
It is typically done based on the text itself without needing additional context.
* **Translation**: This task involves translating text from one language to another.
The context is usually provided by the sentence itself and the broader document it is part of, rather than a separate vector store.
