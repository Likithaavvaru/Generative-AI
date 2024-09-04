# Generative-AI

# Requirements
.Python
.cohere Python package

Install the Cohere library

Obtain an API Key by Sign up at Cohere and get your API key.

# Usage
Configure your API Key: Replace COHERE_API_KEY with your actual Cohere API key.
Generate Text: The script uses the Cohere generate method to create text based on a specified prompt. The parameters used are:
prompt: The text input for which the model generates a response (e.g., "Write something about Beaches").
max_tokens: The maximum number of tokens (words or word pieces) in the generated text (set to 300 in this example).
temperature: Controls the randomness of the output. A value of 0.5 balances creativity and coherence.
stop_sequences: Sequences where the model should stop generating further text (e.g., newline character \n).
