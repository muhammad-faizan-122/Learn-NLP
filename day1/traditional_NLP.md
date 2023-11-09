Traditional NLP method with more detailed explanations and examples:

1. **Rule-Based Systems**:
   - **Description**: These systems operate on sets of hand-written rules. The rules can be based on grammar, syntax, or specific patterns in text.
   - **Example**: A simple rule-based system for identifying questions might look for sentences that start with "What", "Why", "How", etc., and end with a question mark. For instance, the rule can be written as `If a sentence starts with a 'Wh-' word and ends with '?', then classify it as a question`.

2. **Lexicon-Based Approaches**:
   - **Description**: In these methods, a large lexicon or dictionary of words, each tagged with information like part of speech, sentiment, etc., is used to analyze text.
   - **Example**: For sentiment analysis, a lexicon might tag words like "happy", "joyful", and "pleased" as positive, and words like "sad", "angry", and "disappointed" as negative. The overall sentiment of a text is then determined based on the prevalence of these tagged words.

3. **Morphological Analysis**:
   - **Description**: This involves breaking down words into their base forms (lemmas) and affixes. It's crucial in understanding the grammatical function and meaning of words.
   - **Example**: The word "running" can be broken down into its root "run" and the suffix "-ing". This process is essential in languages with rich morphology, like German or Russian, where word forms change extensively.

4. **Syntax Analysis and Parsing**:
   - **Description**: This is about analyzing the grammatical structure of sentences. It involves understanding how words in a sentence relate to each other.
   - **Example**: In the sentence "The cat sat on the mat", a syntactic parser would identify "The cat" as the subject, "sat" as the verb, and "on the mat" as the prepositional phrase acting as an adverbial.

5. **Semantic Analysis**:
   - **Description**: This step involves understanding the meaning of words and how these meanings combine in sentences.
   - **Example**: In the sentence "I banked on him to win", semantic analysis helps distinguish whether "banked" refers to a financial institution or to having confidence in someone.

6. **Statistical Methods**:
   - **Description**: These methods use statistical techniques to analyze and make predictions about language. 
   - **Example**: An n-gram model might predict the next word in a sentence based on the frequency of word sequences in a training dataset. For instance, in a bigram (2-word sequence) model, given the word "heavy", the model might predict "rain" if "heavy rain" is a common phrase in its training data.

7. **Finite State Machines (FSMs)**:
   - **Description**: FSMs are used for tasks that can be divided into a finite number of states. They are particularly useful for pattern recognition in text.
   - **Example**: A FSM could be used for phone number recognition in text. It would move through various states as it identifies country codes, area codes, and the main number, changing states based on the pattern of digits and separators (like dashes or spaces).

Each of these traditional methods has its strengths and is particularly suited for structured and rule-governed aspects of language. However, they often require extensive manual effort to create rules or lexicons and can struggle with the ambiguity and evolving nature of natural language, which led to the rise of more flexible machine learning and deep learning approaches in NLP.