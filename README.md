# Triplet-Loss_Siamese_NN
Siamese Network Triplet Loss Influenced from the Original FaceNet. 
This Network is different from the facenet Paper in two ways:
1) The Network uses the RMSE(Root Mean Square Error) as the distance measure between the positve from the anchor and the    negative from the anchor.
2) The Convolutional Layers have been replaced by the Dense layer of 64 Dimensions. (This can be read as an encoding)
~Additional:
This program also visualizes the class seperation by calling a PCAPlotter method. The pca_plotter.py file can be found in this repository.


This Network uses the script provided by gskielian at https://github.com/gskielian/JPG-PNG-to-MNIST-NN-Format to convert the custom dataset into the mnist format i.e ubyte tar.gz formats. 

To use the converted format please install mnist by pip install python-mnist.
https://github.com/sorki/python-mnist 
Use the MNist.load_training method and point to the directory of converted custom dataset's gz files
The custom dataset can then be easily loaded.




 
