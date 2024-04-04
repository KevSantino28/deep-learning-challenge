# deep-learning-challenge

The purpose of this analysis was to help Alphabet Soup select applicants to fund and best ensure those applicants have successful ventures.

Data Pre-processing
  - The variable we targeted for our model was the 'IS_SUCCESSFUL' variable
  - The feature variables were all remaining columns besides the 'IS_SUCCESSFUL' column.
  - Variables 'EIN' and 'NAME' were dropped because they are not targets or features

Compiling, Training, and Evaluating the Model
  - For my first attempt I had 12 hidden_nodes_layer1 and 24 hidden_nodes_layer2, these were mainly random guesses to then try and tweak the model to make it better.
  - I was not able to achieve 75% accuracy
  - For attempt 2 I added a third hidden layer and adjusted the number of each layer. For attempt 3 I used 3 hidden layers again and adjusted the number of layers furthur. None of these got me to achieve the goal od 75%.

Summary
Overall my data learning model best achieved a 72.5% accuracy. Adjusting the number of layers and number of nodes per layer had very little affect on the accuracy. If I were to do this analysis again I'd attempt to use different activation phrases or a completely different model entirely.
