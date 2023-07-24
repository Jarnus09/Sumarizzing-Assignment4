# Sumarizzing-Assignment4

The model to generate comedy lines is made by using the TensorFlow library with the help of Keras library. Two LSTM layers have been used for this purpose one of which is bidirectional along with two dropout layers to reduce overfitting. One embedding layer has also been added to the model to embed the words into vectors of 100 dimensions.

Hyperparameters such as 

#### * The units in the lstm layer

#### * The probability of the neurons being deactivated

#### * The length of the sequences


have been adjusted accordingly to get better results.

# Files committed

* `model.py` - All the necessary code required to make the model is present here.
* `my_model (2).keras` - Contains the weights required to make the neural network made with the help of model.py
* `tokenizer.pkl` - The tokenizer used for this model to change the words into numbers.
* `app.py` - Code for website needed to generate text with the help of http POST request is present here. Flask API has been used for this purpose which renders the template (`html.html`) present in the templates folder.

The link for the training data (dataX) is present [here](https://drive.google.com/file/d/1GUZov6k3cO3JC-q2XgPuDx892uD4zJjj/view?usp=drive_link).
The model does not produce very good results but it showed a significant improvement when it was trained for more number of epochs. It could not be trained for more number of epochs due to RAM issues.

# Snippets 
![image](https://github.com/Jarnus09/Sumarizzing-Assignment4/assets/121663944/c4834935-fa46-4252-b2a7-d9696c8afe25)



![WhatsApp Image 2023-07-24 at 14 56 09](https://github.com/Jarnus09/Sumarizzing-Assignment4/assets/121663944/24c3bd53-e00f-4a53-8456-4bcd71ec4d5b)



![image](https://github.com/Jarnus09/Sumarizzing-Assignment4/assets/121663944/8816acee-84db-497c-92fe-a05f033d9750)



![image](https://github.com/Jarnus09/Sumarizzing-Assignment4/assets/121663944/d2679d93-8d3d-4a60-9d43-fd084c9e337c)






