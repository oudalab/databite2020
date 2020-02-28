## Tutorial 2: Image Classification
Prepared by: Jasmine DeHart

Everything you could need to get started with an image model. In this tutorial, we look at both traditional classification models as well as neural networks. In SkLearn we explore Random Forest and Support Machine Vectors. From Pytorch, we develop a Neural Network Model with Cross Entropy Loss, 15 Epochs, and LogSoftMax Activation on the last layer.

Both examples use the Handwritten Dataset. The pptx file will provide you with the basic outline you need to get started. If there's anything I missed feel free to let me know!

### Before you begin, feel free to complete a Pre-knowledge Survey: https://ousurvey.qualtrics.com/jfe/form/SV_bsmwcDdK24VneEB

MNIST: Handwritten Dataset download used for Pytorch.

Pytorch Model: my_mnist_model.pt
SkLearn Models: rf_classifier.joblib, svc_classifier.joblib

Load Pytorch Model: model = torch.load(PATH)
		    model.eval() or model.train()

Load Sklearn Models: clf = load('filename.joblib')

The Pytorch Example folder provides a templated design for use of creating a model with your own photos. There is a sample data folder, python notebook, and saved model file for viewing. This model has not been created to run the best, only for a template to help structure a neural network for your own endeavors. Best of luck!

### After you complete this tutorial, feel free to complete a Post-knowledge Survey: https://ousurvey.qualtrics.com/jfe/form/SV_0On07oFsn378Kzz

~ Jasmine
