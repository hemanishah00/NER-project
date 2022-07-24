# NER-project
Trained a language model on WIESP dataset. Used various architectures like ELMO and our own custom architecture. 
Notebooks (In the recommended order):
1. EDA
2. Baseline and ELMO
3. Custom_Model
4. Balanced_Custom_Model: This is very similar to the Custom model notebook, except for the preprocessing
to balance data, for model 2, 3 and 4.
5. Autocorrector: This notebook contains an autocorrect tool trained on this corpus. Suppose one
is trying use one of our models to predict the NER tag of a word and they
accidentally type the incorrect spelling , this returned autocorrect suggestions that
are the closest match from our data. This can be used as a tool when
implementing the model for an end user.
