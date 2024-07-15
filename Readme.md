Business contracts are legal documents. The first task is to parse these documents so that have a structure to them. Determine the key details within the contract document. Every contract has clauses and sub-clauses. The next step is to classify the contents of the parsed documents to these clauses. Typically, a contract has an associated template to it, and it is important to determine the deviations from that template and highlight them.


The project aims to develop a web application that validates business contracts by:

1. Upload and Processing: Allowing users to upload their contracts in PDF format, which are then converted to text using PyPDF2.
2. Preprocessing: Cleaning and normalizing the text using regular expressions and NLTK.
3. Named Entity Recognition (NER): Identifying entities in the contract text using a pre-trained NER model.
4. Clause Identification: Detecting clauses and subclauses in the contract text using regular expressions.
5. Template Comparison: Comparing the contract text with a selected template to identify deviations and calculate a similarity score.
6. Highlighting and Summarization: Highlighting keywords and generating a summary of the contract text.
7. Visualization: Displaying the original contract text, highlighted contract text, summary, entities, clauses, and subclauses in a user-friendly interface using Streamlit.
