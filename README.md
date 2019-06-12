# Parts-of-Speech-Tagging with Hidden Markov Models 

### Aim

To determine the syntactic category of a word from the words in its surrounding context. In this project, I used the [Pomegranate](http://pomegranate.readthedocs.io/) library to build a hidden Markov model for part of speech tagging using a "universal" tagset. 

### Reason for using HMMs
They are faster, not memory intensive and provides satisfactory accuracy for our use case.

Hidden Markov models have been able to achieve [>96% tag accuracy with larger tagsets on realistic text corpora](http://www.coli.uni-saarland.de/~thorsten/publications/Brants-ANLP00.pdf). Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.  

### Alternatives Considered
We can use a RNN but the inference and training time will be longer. Moreover, RNN might improve the model accuracy by atmost 2%. Trade-off between improvement and development time tipped scales in HMM favor.

### Use Cases for POS tagging
It is often used to help disambiguate natural language phrases (as it can be done quickly with high accuracy), determine correct pronunciation during speech synthesis (for example, _dis_-count as a noun vs dis-_count_ as a verb), for information retrieval, and for word sense disambiguation.

### Python Environment
You can recreate the necessary environment using requirements.txt file.
