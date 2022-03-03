# BRAIN-TUMOR Autofocus Layer for Semantic Segmentation
<h1>Introduction</h1>
<p>This is a PyTorch implementation of the autofocus convolutional layer proposed for semantic segmentation with the objective of enhancing the capabilities of neural networks for multi-scale processing. Autofocus layers adaptively change the size of the effective receptive field based on the processed context to generate more powerful features. The proposed autofocus layer can be easily integrated into existing networks to improve a model's representational power.

Here we apply the autofocus convolutional layer to deep neural networks for 3D semantic segmentation. We run experiments on the Brain Tumor Image Segmentation dataset (BRATS2015) as an example to show how the models work. In addition, we also implement a series of deep learning based models used for 3D Semantic Segmentation. The details of all the models implemented here can be found in our paper: Autofocus Layer for Semantic Segmentation.</p>


<h1>Data Sets</h1>

<p> We got this data set from smi website and the name of the data set is Brats2015 , the data set format in in the .mah file i.e., the MRI images will be in the 16 bit integers where we need to use SimpleITK or AutoDesk Revit or Mahjongg Solitaire Settings to open the files.</p>

<h1>Environement</h1>

