## Sentence Parser
This project is a simple natural language sentence parser using context-free grammar (CFG) in Python. The program parses sentences, identifying grammatical structures like noun phrases (NP) and generating parse trees. It also extracts noun phrase chunks from a given sentence.

![image](https://github.com/user-attachments/assets/34445a8e-6010-4367-adc0-5381c8ad4f6b)

# Features  
- **Sentence Parsing**: Given a sentence, the program uses a pre-defined CFG to parse the sentence into its grammatical components.  
- **Noun Phrase Chunking**: Extracts noun phrase chunks from the sentence tree. A noun phrase chunk is a subtree labeled as "NP" that does not contain other nested noun phrases.  
- **Preprocessing**: Converts the sentence to lowercase and removes any non-alphabetic words before parsing.  
# Grammar Rules  
The grammar rules are based on standard sentence structures and include:  

- **Terminals**: Common parts of speech such as nouns, verbs, adjectives, adverbs, etc.  
- **Non-Terminals**: Higher-level syntactic structures like noun phrases (NP), verb phrases (VP), and sentences (S).  
