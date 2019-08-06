# SiameseCNN

Standard classification is what nearly all classification models use. The input is fed into a series of layers, and in the end , the class probabilities are output. If you want to predict dogs from cats, you train the model on similar(but not same) dogs/cats pictures that you would expect during prediction time. Naturally, this requires that you have a dataset that is similar to what you would expect once you use the model for prediction.

One Shot Classification models, on the other hand, requires that you have just one training example of each class you want to predict on. The model is still trained on several instances, but they only have to be in the similar domain as your training example.

A nice example would be facial recognition. You would train a One Shot classification model on a dataset that contains various angles , lighting , etc. of a few people. Then if you want to recognise if a person X is in an image, you take one single photo of that person, and then ask the model if that person is in the that image(note, the model was not trained using any pictures of person X).

As humans, we can recognize a person by his/her face by just meeting them once, and it is desirable by computers because many times data is at a minimum.


Enter Siamese Networks
Siamese networks are a special type of neural network architecture. Instead of a model learning to classify its inputs, the neural networks learns to differentiate between two inputs. It learns the similarity between them.


##References :


https://becominghuman.ai/siamese-networks-algorithm-applications-and-pytorch-implementation-4ffa3304c18

https://hackernoon.com/one-shot-learning-with-siamese-networks-in-pytorch-8ddaab10340e



