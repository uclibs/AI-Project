# AI-Project

R&D project to extract text from a document (Word, PDF, Text, etc.) and suggest potential metadata fields for the file (title, description, subject, etc.)

Potential implementation:
1. User submits a document to Scholar@UC and adds basic metadata
1. A background job initiates an AI service that suggestes additional metadata
1. User is sent an email with option to use the suggested metadata
1. If accepted by the user, the suggested metadata is applied to the work

## Annif Worflow:
1. Install Annif: Annif can be installed on a server or a local machine. 
1. Prepare your data: The input data should be in a specific format that Annif can understand. Currently, Annif supports the following formats: plain text, MARCXML, and RDF. You can also use external tools to convert your data into these formats.
1. Create a project: A project in Annif represents a collection of documents that you want to index. To create a project, you need to define the following:
    - A name for the project
    - The language of the documents
    - The type of indexing algorithm you want to use (e.g., TF-IDF, LDA, or SVM)
    - The source of the data (e.g., a file or a URL)

1. Train the model: Once you have created a project, you need to train the model. This involves feeding the model with a set of training data that includes both input documents and their corresponding subject headings. Annif will use this data to learn the patterns and relationships between the input data and the assigned subject headings.

1. Evaluate the model: After training the model, you should evaluate its performance using a separate set of data. The evaluation data should be similar to the training data, but should not be used during training. Annif provides various metrics to evaluate the performance of the model, such as precision, recall, and F1-score.

1. Use the model: Once the model has been trained and evaluated, you can use it to automatically assign subject headings to new documents. Annif provides various ways to use the model, such as a command-line interface, a web-based interface, or an API.
