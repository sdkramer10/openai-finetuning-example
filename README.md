# OpenAI Fine-Tuning Example

This repository provides an example of fine-tuning OpenAI's GPT-4o-mini model for classifying customer service support tickets. Through fine-tuning, we are able to increase the classification accuracy from 69% to 94%.

## Prerequisites

- Python 3 installed on your system
- OpenAI API Key

## Setup

1. Install Jupyter Notebook:
   ```
   pip install jupyter
   ```

## Running the Example

1. Start the Jupyter Notebook
   ```
   jupyter notebook openai-finetuning-example.ipynb
   ``` 

2. Execute the cells in the notebook sequentially.

3. As you execute the notebook, ensure you update the OPENAI_API_KEY, training_file, and model_id parameters.

## Notes

1. This example is designed to work with OpenAI's GPT-4o-mini model but can be adapted for other models.

2. For more information on fine-tuning models, refer to OpenAI's documentation (https://platform.openai.com/docs/guides/fine-tuning).
