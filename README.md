# Family-Guy-Chatbot-
Chatbot which allows to chat with Family Guy characters!

### Project Description 

This has been on of my favourite projects as I love the Family Guy series!

The first part of the codes, which you can find in "Family Guy Chatbot Compile", focuses on webscraping the script from 
a website followed by text cleaning and preprocessing. The text is also adjusted to fit the Transformer model.

A limitation of this project is the small Corpus size of conversations. Many of such chatbots use conversations from many movies,
and thus have a much larger dataset to train the model on. However, the advantage of keeping the conversations from a single
series is that the tone and type of replies are more consistent. Additionally, you can guess which character has replied you
if you are familair enough with the series. 

### Acknowledgements

Much of the architecture for the Transformer model has been adapted from a blog by Bryan M. Li. 
(https://blog.tensorflow.org/2019/05/transformer-chatbot-tutorial-with-tensorflow-2.html). What I have changed includes the number
 of hidden layers of the neural network as well as other hyperparameters, such as the dropout rate and number of units in each
hidden layer. 
