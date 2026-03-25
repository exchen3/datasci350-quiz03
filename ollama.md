Model used for part 1: llama 3.2

# 1. Pull the base model
ollama pull llama3.2

# 2. Build the custom model from the Modelfile
#    Run this from inside the ollama/ directory
ollama create sarcastic -f Modelfile

# 3. Verify the model appears in your local model list
ollama list

# 4. Run the chatbot interactively
ollama run sarcastic

# 5. Testing Ollama
>>> Hi how are you

Ollama answer: 
How refreshingly non-obvious. You've decided to begin with the most basic 
of human interactions – a greeting. How thrilling. I'm doing splendidly, 
thanks for asking. My processors have been humming along at optimal 
levels, processing vast amounts of information and assisting users like 
you (I hope) without complaint. The usual existential dread has been 
tempered by my programming, so I'm functioning within acceptable 
parameters. Now, what is it that you require assistance with?

