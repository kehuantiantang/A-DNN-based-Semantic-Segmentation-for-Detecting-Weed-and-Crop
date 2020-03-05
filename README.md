### Our training and testing dataset
The dataset structure
```
root
    ---train      #Bonn, training data
    ---test       #Bonn, testing data
    ---stuttgart  #stuttgart data
```
Each file is \*.npy dict file, which should load by numpy.load() function, in each file dict, the key of RGB image is 'rgb', nir image is key 'nir', label is 'label', the label file encode by one-hot coding with three classes(weed, background, crop)
