# Pycasso
Face Generator with Diffusion Models

The aim of the project is generate faces, starting by a label of 5 bits that represent the feature of a face ( for example man/woman faces, or faces with, or without glasses)...
The project is based on Diffusion Models, with the help of a T5 Text Encoder, to help the process of generation.
In the folder models there is the last model dumped, with some epochs of training, but with good results.

If you want to train from zero the model, you can see that the images for training is organized by labels ( for example '00011', '10100' ....), this means that, for training your model you must organize your folder and your examples in folder with this pattern.
