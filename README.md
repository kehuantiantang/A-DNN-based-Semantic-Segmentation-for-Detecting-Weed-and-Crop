### Our training and testing dataset
The dataset structure
```
root
    ---train      #Bonn, training data
    ---test       #Bonn, testing data
    ---stuttgart  #stuttgart data
```
Each file is \*.npy dict file, which should load by numpy.load() function, in each file dict, the key of RGB image is 'rgb', nir image is key 'nir', label is 'label', the label file encode by one-hot coding with three classes(weed, background, crop)

### New link
The git lfs has problem about my account, I re-upload the dataset to google cloud. This is the download link:
- [train](https://drive.google.com/file/d/19chwaYWAYRT5nEduFq896a6BQOsZBvDY/view?usp=sharing)
- [test](https://drive.google.com/file/d/1_3ECFQJpY0nDASIhf_Tg9VIme6oOCiHL/view?usp=sharing)
- [stuttgart](https://drive.google.com/file/d/19chwaYWAYRT5nEduFq896a6BQOsZBvDY/view?usp=sharing)

**Each folder may has `\*.ypn.npy` file, it is the mislabeled file, segmentated weed may small or not fully annotated. You can remove or relabel them for further research.**

If you find the data is useful for your project, please cite those paper. Thank you so much.

### Citation
```
You J, Liu W, Lee J. A DNN-based semantic segmentation for detecting weed and crop[J]. Computers and Electronics in Agriculture, 2020, 178: 105750.
```
