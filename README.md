<h1> Cybercrime Victim Summarization NLP System</h1>

This project is a Natural Language Processing (NLP) pipeline designed to extract and summarize information about victims of cybercrimes from social media datasets. Using advanced text preprocessing, entity recognition, and summarization techniques, this system identifies key details and generates concise descriptions of cybercrime incidents.

<h3>Features</h3>

<li>Text Preprocessing: Cleans raw social media text by removing URLs, mentions, hashtags, special characters, and normalizing text.</li>

<li>Named Entity Recognition (NER): Identifies entities such as names (PERSON) and locations (GPE) using spaCy.</li>

<li>Summarization: Generates concise summaries using the facebook/bart-large-cnn transformer model.</li>

<li>Validation: Ensures summaries include references to extracted entities for relevance.</li>

<li>Visualization: Provides insights into entity distributions using bar charts.</li>
