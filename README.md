# Neural-Net-Image-Saliency
Saliency is defined as the property by which some things stand out. Neural networks are infamously difficult to analyze, which can be problematic when trying to understand why they make decisions. By taking the gradient of the activation, we can create a mapping of the pixel significance, and get a better understanding about what specific regions most influenced the outcome of the net's decision.


It can be interesting to look at how deep convolutional nets respond to inputs that are well outside their training parameters. Imagenet provides a robust dataset of labeled images, however there are very few hand drawn examples included. To test how a neural net will respond, we will provide a model with several abstract and surreal pieces of art. Image saliency from the top four answers are taken from Regnet 800 trained on Imagenet. On the left is the labeled hand drawn image followed by the pixel magnitudes of the top four saliencies, followed by those four saliencies with direction. Brighter values signify more attention paid by the net for each pixel.


![Example readouts of the saliencies](imageSaliency.PNG "saliency")

Source code can be viewed interactively at

https://colab.research.google.com/github/KappnKrunch/Neural-Net-Image-Saliency/blob/main/Abstract_Art_Vanilla_Gradient.ipynb
