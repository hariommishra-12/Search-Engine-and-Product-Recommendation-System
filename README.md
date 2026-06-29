# Search-Engine-and-Product-Recommendation-System

This project is a Search Engine and Product Recommendation System built using Python, Streamlit, and Natural Language Processing (NLP) techniques. It allows users to search for products using natural language queries and recommends the most relevant products based on text similarity.

The application uses TF-IDF (Term Frequency-Inverse Document Frequency) for text vectorization and Cosine Similarity to rank products according to their relevance.
<br><br>
**Features**<br><br>
- Search products using natural language queries.<br>
- Product recommendations based on text similarity.<br>
- NLP preprocessing using tokenization and stemming.<br>
- Interactive user interface built with Streamlit.<br>
- Displays the top 10 most relevant search results.<br><br>

**Technologies Used**<br><br>
- Python<br>
- Pandas<br>
- NumPy<br>
- NLTK<br>
- Scikit-learn<br>
- Streamlit<br>
- Pillow (PIL)<br><br><br>
**Project Structure**<br><br>

├── app.py<br>
├── amazon_product.csv<br>
├── README.md<br>
└── LICENSE<br><br>

**Installation**<br><br>

- Navigate to the project directory<br>
- cd Search-Engine-and-Product-Recommendation-System<br>
- Install the required packages<br>
- pip install -r requirements.txt<br>
- Download the required NLTK tokenizer<br>
- import nltk<br>
- nltk.download('punkt')<br>
- Run the Streamlit application<br>
- streamlit run app.py<br><br>

**How It Works**<br><br>
- Load the Amazon product dataset.<br>
- Preprocess product titles and descriptions using tokenization and stemming.<br>
- Convert text into TF-IDF vectors.<br>
- Compute cosine similarity between the user's query and product descriptions.<br>
- Display the top matching products in the Streamlit interface.<br>
- Future Improvements<br>
- Add product images and ratings.<br>
- Filter search results by category.<br>
- Improve recommendation accuracy using Sentence Transformers or BERT embeddings.<br>
- Optimize search by precomputing the TF-IDF matrix.<br>
- Deploy the application online using Streamlit Community Cloud.<br><br>
**License**<br><br>

This project is licensed under the MIT License.<br><br>

**Author**<br><br>

Hari Om Mishra
