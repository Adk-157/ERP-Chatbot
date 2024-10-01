# ERP Chatbot

This project aims to develop a chatbot that enhances user interaction with an ERP system by addressing user queries regarding specific functionalities.

## 1. Introduction

### Overview of ERP Product:
The ERP (Enterprise Resource Planning) system integrates various business processes into a single platform, offering key functionalities like accounting, human resources, and inventory management. The chatbot will help the user interact and navigate with the key functionalities provided by the application seamlessly and resolve any queries that they may have regarding the functions.

### Objective:
Create a chatbot to improve the user experience within the ERP system by resolving the queries of the users regarding the key functionalities available in the system.

## 2. Key Functionalities

- **Document Extraction**: Utilize OCR technologies to extract text from various document formats. Allow users to upload documents for processing.
- **Named Entity Recognition (NER)**: Implement NER to identify and classify key entities (e.g., names, dates, locations) within extracted documents. Provide users with summaries of extracted information.
- **Document Classification**: Categorize documents based on predefined criteria (e.g., invoices, contracts) using machine learning models for classification.
- **Digitalization of Documents**: Convert physical documents into digital formats. Offer options for file formats (PDF, Word, etc.) and storage locations.
- **Search Functionality**: Implement a search feature that allows users to query documents based on content, providing suggestions and filters to refine search results.
- **User Verification Screen**: Provide a user verification screen to validate the extracted information with various levels of validation (Data entry, Validator, Approver).
- **Business Rules**: Convert the extracted information into the required format and provide support to enhance manual work.
- **Accounts Management with User Verification**: Enable user registration and authentication, managing user roles and permissions to access specific functionalities.
- **Account Balance Inquiry**: Allow users to check their account balances for different accounts (e.g., checking).
- **Transaction History**: Enable users to retrieve recent transactions and filter them by date, type, or amount.
- **Invoice Management**: Assist users in generating, sending, and tracking invoices. Provide status updates on invoice payments.
- **Expense Tracking**: Help users log and categorize expenses, offering summaries of monthly expenses or reports.
- **Budget Tracking**: Enable users to set budgets for different categories and monitor their spending against those budgets.
- **Payment Reminders**: Send reminders for upcoming payments, due dates, or recurring invoices.
- **User Authentication and Role Management**: Implement secure user login and role-based access for different functionalities.

## 3. Technical Stack Suggestions

- **NLP Tools**: Use frameworks like [Rasa](https://rasa.com/) or any open-source NLP library for chatbot development.
- **Database**: Consider using SQL (e.g., [PostgreSQL](https://www.postgresql.org/)) or NoSQL (e.g., [MongoDB](https://www.mongodb.com/)) for storing user and transaction data.
- **Backend Framework**: Use [Flask](https://flask.palletsprojects.com/) or [FastAPI](https://fastapi.tiangolo.com/) to handle API requests.

## 4. Libraries and Packages

### Required Libraries:
- **NLP**: 
  - [spaCy](https://spacy.io/) or [NLTK](https://www.nltk.org/) (for natural language processing)
  - [Rasa](https://rasa.com/) (for building conversational AI)
- **Machine Learning**: 
  - [scikit-learn](https://scikit-learn.org/stable/) (for machine learning algorithms)
- **Web Framework**: 
  - [Flask](https://flask.palletsprojects.com/) or [FastAPI](https://fastapi.tiangolo.com/) (for building the web server)


### Installation:

1. Clone the repository:
   ```bash
   git clone https://github.com/Dhyanesh18/ERP-Chatbot.git
   cd ERP-Chatbot
