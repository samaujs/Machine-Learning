## Process the Environmental, Social, and Governance (ESG) information with Probabilistic Machine Learning model for Sustainability Investment

> Nowadays, the Web is a common medium for corporations to effectively disseminate and demonstrate their efforts to incorporate sustainability practices into their business processes.  This led to the idea of using the Web as a source of data to measure how companies are progressing towards meeting the new sustainability requirements recently stipulated by the United Nations. From a initial sample of sustainability-related reports were identified and collected.
- Environmental, social, and governance (ESG) criteria are a set of standards for a company’s operations that socially conscious investors use to screen potential investments.
- Environmental criteria consider how a company performs as a steward of nature and environmentally conscious.
- Social criteria examine how it manages relationships with employees, suppliers, customers, and the communities where it operates.
- Governance deals with a company’s leadership, executive pay, audits, internal controls, and shareholder rights.

> Topic models represent a family of machine learning algorithms that extract topics from raw texts.  A topic is intended here as a list of words that occur in statistically meaningful ways.  Topic modelling algorithms do not require any prior annotations or labelling of the documents.  Instead, the topics emerge from the analysis of the original texts.  Latent Dirichlet Allocation (LDA) is a special type of unsupervised topic modelling.  Given a collection of documents, it assigns to each topic to a distribution over words and to each document to a distribution over topics.

> Here we use LDA to identify topics on the text extracted from pdf documents or raw texts from NIPS papers.  Topics can allow us to understand what areas of sustainability each document covers, such as environment, supporting charities, employees well-being, etc., and in what proportion.  Some of the covered areas are : 
- Explore Latent Dirichlet Allocation on ESG pdf documents and/or NIPS papers
- Topic predictions for unseen documents
- Using K-Means clustering algorithm for ESG categorisation
- Using Max matching word ratio to identify the ESG category with reference to the input ESG dictionary from domain expert
- Multi-class predictions for ESG category

> References :<br>
>[1] Latent Dirichlet Allocation, by David M. Blei, Andrew Y. Ng and Michael I. Jordan, 2003<br>
>[2] LDAvis: A method for visualizing and interpreting topics, by Carson Sievert and Kenneth E. Shirley, 2014.<br>
