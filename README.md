# Dog Breed classification using CNN
This project is about detecting the dog's breed from the user supplied image. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling, otherwise it'll say "Neither a dog nor human detcted in the image".

First it'll try to detect if human face is in image and give the estimation of most resembling dog breed, if human not detected in image then it will try to detect if dog is in image and give the estimation of it's breed, if neither human nor dog is detected then it'll provide estmation based on "Imagenet" dataset.

Complete roadmap is here :

    1. Import dataset
    
    2. Detect humans
    
    3. Detect dogs
    
    4. Creating a CNN (from scratch)
    
    5. Use a pretrained CNN (from transfer learning)
    
    6. Write final algorithm
    
    7. Prediction
    
## step 1 : Import dataset
The dog dataset was downloaded from (https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip), the human dataset was downloaded from (https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). 

There were 133 total dog categories, 8351 total dog images, 6680 training dog images, 835 validation dog images, 836 test dog images and 13233 total human images.

