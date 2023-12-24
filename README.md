# Restaurant Chatbot Using NLP

## Project Overview

This project focuses on developing a restaurant chatbot using Natural Language Processing (NLP) and Flask. The chatbot aims to automate routine tasks in a restaurant setting, such as handling orders, bookings, and customer queries. It leverages advanced NLP techniques to interact with users in a natural, conversational manner.

## Installation

To run the chatbot, you will need the following libraries:
- NLTK
- Random
- Datetime
- Pymongo
- Uuid
- Json
- Codecs
- Flask
- Sklearn

Install these packages using pip:
```bash
pip install nltk random datetime pymongo uuid json codecs flask sklearn
```

## Dataset

The dataset includes various intents and corresponding patterns and responses in JSON format, which are used to train the chatbot.

## Methodology

The methodology involves:
- Data Pre-processing: Normalizing and embedding sentences.
- Intent Classification: Using cosine similarity for determining the intent of user messages.
- Response Generation: Based on identified intents, generating appropriate responses.
- Database Integration: Using MongoDB for storing menu items, bookings, and feedback.
- Flask Integration: Developing a web application for the chatbot interface.

## Project Workflow

- Building dataset
- Message normalizing
- Sentence embedding
- Intent classification
- Creating database (MongoDB)
- Response generating based on intent
- Integrating code with Flask

## Final Outcome

The chatbot successfully performs tasks such as showing menus, taking orders, collecting feedback, answering FAQs, and managing table bookings.

## Usage

To use the chatbot:
1. Clone the repository.
2. Run the Jupyter Notebooks in the following order:
   - `sentence_normalizer.ipynb`
   - `Data_embedder.ipynb`
   - `intent classifier.ipynb`
   - `Response_generator.ipynb`
   - `app.ipynb`
3. Interact with the chatbot through the Flask web interface.

## References

Key references and studies that supported this project are available in the dissertation report and PowerPoint presentation.

## License

This project is licensed under the MIT License.

## Acknowledgments

Special thanks to the School of Emerging Science and Technology, Gujarat University for their support and guidance throughout this project.

