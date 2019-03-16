# Pokemon_GAN
DCGAN for pokemons generating

![alt text](https://github.com/andrey4ru/Pokemon_GAN/blob/master/GAN_models/EXTENDED_200_EPOCH_64_ALLDATA/weights/test_pokemon_1000.png)


How to use:

1. Unzip dataset
2. Import libreries
3. Initialize functions

For new models training:
1. Load dataset to memory
2. Set batchsize and number of epochs
3. Load pretrained models from directory or initialize new
4. Train!

For new images generating:

1. Use model which was trained or load pretrained from folder
2. Run function 'generate_image()', as parameters set output folder, generator model, 
dimension of resulted images(dim*dim), image name 
