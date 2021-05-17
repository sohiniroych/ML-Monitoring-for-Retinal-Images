# ML-Monitoring-for-Retinal-Images
In this exercise we use the weights and biases (https://github.com/wandb/client) platform to monitor ML classification progress as well asto track model performance at production time to detect concept drift and data drift. To replicate the tutorial video in https://youtu.be/-OH-9tNgcmM, follow the steps below.
# Step 1: Download the training data
This codebase uses retinal images from the website:  http://www2.it.lut.fi/project/imageret/diaretdb1/
Use the code named "Step 1" in the folder "code" to generate the groundtruth (GT) folder structure neede for the tutorial.

# Step 2: Create a login at Weights and Biases
Weights & Biases; https://www.wandb.ai/

# Step 3: Run the code
Use the code named "Step 2" to run ML model training and producrion monitoring.

# Step 4: Production testing
For the final step download the STARE data from https://cecas.clemson.edu/~ahoover/stare/. This is the test data used to analyze for drift at production time.
