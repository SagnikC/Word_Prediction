# Word_Prediction
## Word Prediction Using Quadgrams and Pentagrams in Python
### Summer Internship Project at Indian Institute of Technology Kharagpur 
* Token length of corpus : **2.4 million**
* Vocabulary : **50k**
* Corpus has been divided into **training corpus**, **test corpus** and **held-out corpus**(for tuning parameters of grid search)
* **Interpolation** has been used while calculating probability distribution of quadgrams in the training corpus
* **Back-off** method has been used in the final stage of word prediction
* Three kinds of smoothing techniques have been implemented : **Add-1**, **Good-Turing** and **Kneser-Ney**
* **Perplexity** of each of these three techniques has been calculated for comparison purposes
