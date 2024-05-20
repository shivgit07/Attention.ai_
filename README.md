# Attention.ai_
The provided code fine-tunes the Phi-3-mini model to answer specific e-commerce-related questions by identifying relevant tables, columns, and relationships in a database schema. It involves preprocessing the metadata and questions, loading and tokenizing the data, and using the Hugging Face transformers library for model fine-tuning. After fine-tuning, the model can generate structured outputs that map questions to the appropriate database schema elements, facilitating easier query generation and data retrieval. The final model is saved for future use in generating these structured outputs.</br>
The `training_data.json` file contains the data used for fine tuning the model. </br>
It is created using the Word2vec Embedding model to generate the 2 most relevant keywords by finding the best correlation between the question and metadata.keys() or the table names.
Similarly, relevant columns for the 2 tables were also selected.
