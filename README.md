# conversation-depression-detection
This repository depicts a set of solutions for detecting depression through natural conversation. 

A conversation agent (either `Llama3-8b-instruct` or `MentaLLaMA-chat-7B` depending on notebook) will carry out a conversation with patients to gather relevant information in a natural manner (simulated via `Llama3-8b-instruct` trained on real patients with differing depression scores), after which an evaluator agent (also based on `Llama3-8b-instruct`) will predict a BDI-II depression score and a set of relevant symptoms.

Notebooks were run either on Google Colab or Kaggle (see folder names) due to differing hardware constraints.

The `submissions` folder contains a set of conversations and evaluated results used as submissions for the CLEF 2026 eRisk shared task on Conversational Depression Detection, under team name `The-Interrogators`.

Full paper TBD

Project built for the Biomedical NLP course at the University of Bucharest, Master's degree.

