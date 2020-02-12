# Keras Generation 1 Pokedex
### A  convolutional neural network to identify Pokémon  
I was inspired by Adrian Rosebrock pokedex which only identified 5 pokemon.   I decided to try to create a pokedex that could identify any of the 150 pokemon.

## Dataset
Kaggle dataset of only generation 1 pokemon (1-150) with each pokemon having at least 30 images was retrieved . This was to provide the model with enough information so it could learn and make accurate predictions. Then test set was created from the dataset by selecting a few random pokemon images.
The official pokemon site to retrieve the pokemon information of the identified pokemon.

## Environment
Python 3  
Tensorflow 2  
Keras  
Numpy  
OpenCV (cv2)    
Matplotlib  
OS  
BeautifulSoup

## Training model accuracy of 97% but model has accuracy of 69%
# Possible Improvements
Increase the size of the training set to include more images for each to further train the model.
Possibly expand to include the Generation 2 and onwards pokemon.
