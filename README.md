# Face-Recognition-using-Transfer-Learning
In this project, I have used the pictures of my friend's and my face as the dataset. This is done through the process of Transfer Learning using Keras and Mobilenet and the weight of Imagenet.

# Setting Up :
Load the necessary packages and libraries. 

```
from keras.applications import MobileNet
from keras.models import Sequential
from keras.layers import Dense, Dropout, Activation, Flatten, GlobalAveragePooling2D
from keras.layers import Conv2D, MaxPooling2D, ZeroPadding2D
from keras.layers.normalization import BatchNormalization
from keras.models import Model
```

# Create your own Dataset :
I created my own Dataset by downloading the images of the actors Dulquer Salmaan, Lili Reinhart and Princess Diana.

# Explanation :
I am using Mobilenet as it is lightweight in its architecture. It uses depthwise separable convolutions which basically means it performs a single convolution on each colour channel rather than combining all three and flattening it.

I trained the dataset on Google Colab where it created an h5 file.

The code is pretty simple and can be used in the identification of anything. I used the code earlier to wish my friend 'A happy birthday' whenever she entered the frame. The same code with minor modifications has been used to identify the celebrities. The number of classes can be increased to suit your purpose.

# Output :

