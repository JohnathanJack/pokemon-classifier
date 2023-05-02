# pokemon-classifier

# Project/Goals
The goal of this project is to create an image classification model through a CNN that correctly identifies the starter pokemon: Bulbasaur, Charmander, Squirtle and Pikachu. The secondary objective was to transform the model to differentiate between a real animal and a pokemon.

# Process
1. Obtain a dataset of pictures and filter out 'bad' pictures of the pokemon.
    -Incorrectly named pokemon in its specific folder, corrupted images, unsupported image types
2. Experiment with CNN layers and choose the best model that produces the highest accuracy
3. Utilize transfer learning to improve model performance

# Results
After utilizing transfer learning for the multivariate classification, an accuracy of 91% was achieved for differentiating between the four starter pokemon. More data may increase the accuracy of the results, but I am satisfied with the progress I have made with the model for now. The binary classification model was made directly using the transfer learning method and had an accuracy score of 98%. The model was very good at differentating between a pokemon and a real animal. More in depth analysis of the errors can help me understand the underlying principles of its decision. 
