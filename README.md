# Nonosmotic_sodium_storage
This repository describes the ongoing scientific work on the deposition of nonosmotic sodium salts in muscles.
The aim of this investigation is to find a way how to determine whether the given point of muscle is a cellular space or an interstitial space by spectral images.
We will begin the exploration from the fact that sodium is easily washing away element, so it luminesces mostly from cellular space.

So the simple idea is to make a dataset, which contains coordinate and sodium luminescence intenisty of the given point and then find optimal parameters for clusterisation algorithm to divide cellular and intersticial clusters accurately.
More information you can find reading the notebook [`exploration24.ipynb`](https://github.com/dpaneke/Nonosmotic_sodium_storage/blob/master/exploration24.ipynb)

Of course, this approach is quite simple and depends on good feature engineering (not only coordinates and sodium luminiscence intensity), that is a subject for further discussions
