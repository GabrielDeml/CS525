# Future Work

The following is a list of things that could be done to improve the quality of the results:
* Do fact checking
* Use BERT

BERT! Ok how can we not talk about BERT right now. Ever since BERT came out a couple of years ago it has taken over. Everyone seems to be using it these days. In the future I think we could get better results if BERT was fine-tuned along with adding a classifier in at the end. It would probably make sense to use a couple of fully connected layers and a sigmoid function as the classifier. Using this model should give us a better understanding of the context of the words in the sentence. 

Another thing that could be done is to add a satire label to the model. Sometimes people are making fun of people who believe the fake information. It is hard to classify this as true or fake information because it really isn’t either. Hence why there should be a satire label. Given only true and fake labels it would be hard for a model to be able to classify satire text snippets correctly

It would be interesting to do a combination of fact checking and classification. For each of the statements in the text snippets fact checking could be done to make sure that the information is true. From there it would be simple to classify it as true vs false just based on if the whole statement is true. If the fact check is unsure the text could be classified based on the wording using a classifier. If the fact checker determines that something is false the statement could then be passed into a context classifier to determine if it is satire or not. 

Try an LSTM. It would be interesting seeing the results of an LSTM classifying the text snippets. Using an LSTM would allow for more contextual understanding. 

It would also be interesting to use a genetic optimizer. I am personally obsessed with this type of machine learning. It is the part of machine learning I would like to do a lot of research in the future. 

This isn’t strictly about machine learning, but it would be interesting to get a crowd sourced dataset of people on the internet voting whether or not a statement is false. Then given that dataset it would be interesting to compare it to the classification of several different machine learning models. It would be most interesting to look at the ones that mess up both humans and computers and figure out why. There may be a way to phrase or put a statement that makes it look believable even if the information is not. 

It would be interesting to fact check inside the same statement. The model would be checking for consistency in the statement. For example it would check to make sure that the ball that was thrown through the window doesn’t go from green to red in the same statement. If facts are changing throughout the statement then it would seem that the statement is trying to be deceptive. This approach would probably work less for written text and more for speech since written text can be proof read. It could be applied to such things as verbal questions and answers and videos.  I’m not sure how to go about building a model to do such a thing, but it would be interesting to work on.  

Try a standard RNN. It would be interesting almost just as a baseline to compare the other models. 

