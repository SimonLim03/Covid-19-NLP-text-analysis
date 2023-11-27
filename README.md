# Covid-19-NLP-text-analysis

- Text analysis is the process of classifying, sorting, extracting and analysing text-based information using computer software, in order to understand human-written texts and further relationships and pattern of information. This report conducts text analysis on dataset that is associated with the COVID-19 vaccine expressions and will try to find out the narrative and insights of the dataset. The dataset involves a variety of expressions for 181 common questions about COVID-19 vaccine.

- The columns of the dataset are as follow ():

- Sentence - the expression written by an annotator (or taken from VIRADialogs)
- label - the question for which the expression was written
- label_idx - the running class index associated with this label


- This report conducted text analysis using various techniques, including word count, word frequency, word association, k-mean clustering and sentiment analysis. In the phase of word frequency, 'covid-19', 'vaccine', 'booster', 'side effect' and 'safe' were most frequent words. 'side effect' may reveal social concerns and negative perspective on covid-19 vaccine. On the other hand, 'safe' indicates a positive perspective on vaccine.

- Furthermore, word association confirmed that 'side' and 'effect' are one word and 'side effect' were frequently associated with the word 'vaccine' in more than two words assoication. Also, K-mean clustering also confirmed that at least 2767 expressions were related to concerns and side effects of vaccine.

- Lastly, it was difficult to measure sentiment of primary words since many of primary words were mostly neutral. However, if advanced sentiment analysis, using deep learning, is performed, there will be more likely that primary words are negative.

- Overall, 'side effect' is one of the main words, indicating negative perspectives of COVID-19 vaccine.
