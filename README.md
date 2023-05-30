# PyTorch Helper Files

The following are key helper files i use related to all PyTorch projects

**data_setup.py** - Contains functionality for creating PyTorch DataLoader's for (e.g. typically for image classification data)

* create_dataloaders function - Creates training and testing DataLoaders.  Takes in a training directory and testing directory path and turns them into PyTorch Datasets and then into PyTorch DataLoaders.

**engine.py** - Contains functions for training and testing a PyTorch model.

* Trains the model - this is my PyTorch training loop

**model_builder.py** - Contains PyTorch model code to instantiate a TinyVGG model

* This is typically used for test purposes or quick VGG model creation to test infra...

**predictions.py** - Utility function to make predictions

**train.py** - Trains a PyTorch "image classification" model using device-agnostic code.

**utils.py** - File containing various utility functions for PyTorch model training.

* this file contrains the save model function to save the torch model as .pth
