# Word_Prediction
Word Prediction Using Quadgrams and Pentagrams in Python      
</br> The Quadgram model takes an approximate time of **18.99797248840332 seconds** to find the next word given a sequence of three words  
</br> The Pentagram model takes an approximate time of **17.837090015411377 seconds** to find the next word given a sequence of four words  
</br> Dictionaries used in these models :  
 * **vocab** : To assign a unique index to each word in the dataset
 * **trigram**   : to store the list of trigrams along with its frequencies
 * **quadgram**  : to store the list of quadgrams along with its frequencies
 * **pentagram** : to store the list of pentagrams along wth its frequencies
 * **probab**    : to store the probability distribution for the corresponding quadgram or pentagram model
