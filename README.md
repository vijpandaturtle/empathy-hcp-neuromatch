# Empathy HCP Neuromatch 

This is the code for the neuromatch project by the group "Palak Paneer". 

**Question :** Can BOLD signals predict social cognition? How? Comparing linear decoder and deep learning.

**Abstract (Tentative) :** Empathy, which is defined as recognizing and understanding the states of mind of others, could be regarded as an advanced function of the human brain. This project seeks to link the neural activity of empathy with its perception. To be more specific, can social cognition task fMRI data be used to predict empathy? And how? Predictions based on a linear decoder and deep learning model are implemented and compared to answer these questions.
The idea of predicting empathy by a linear decoder is very straightforward. What is assumed here is that there are some brain regions that are directly related to empathy and based on a linear combination of these BOLD values, empathy could be easily detected. What a linear decoder does here is to map the brain activity with specific behavior. Using a linear decoder, theoretically, we could predict any kind of behavior as long as we know the activity in the relevant brain regions.
In contrast, deep learning model is more complex. It uses various inductive biases and tries to mimic the brain functions (very loosely). Also, it’s a complex model, so it kind of makes sense to analyze a complex model (brain) with another complex model (deep neural nets). Although, in our task we’ll mostly perform simple classification, it would be interesting to observe how well the model takes in the data and extracts a better representation from it, so the downstream task is easier to solve.

**Hypothesis :**
Our hypothesis is that deep learning models are more interpretable than the linear decoder model. 
Mathematically we would write this as 
Linear decoder : y=b+W⊤X
Non-linear(deep learning) model : f(x)=σ(b+W⊤X)


