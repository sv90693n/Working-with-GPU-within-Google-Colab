# Working-with-GPU-within-Google-Colab

Introduction to using GPUs on Google Collaboratory and implementing a simple neural network, training this network and using the resulting model for probability prediction.


Part-1:  Configure your Notebook on Google Colab and select GPU acceleration:

Reference:  https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d

Perform pages 1-8 from this tutorial (until the mnist example; excluding it).  See printed PDF:  “Google Colab Free GPU Tutorial - part-1.pdf”


Part-2: Access files from Google Cloud Storage within Colab Notebooks

Reference: https://medium.com/analytics-vidhya/how-to-access-files-from-google-cloud-storage-in-colab-notebooks-8edaf9e6c020


Part-3:  Learn and apply useful tip when working with GPUs in Google Colab

Reference:  Same as for Part-1: https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d

Perform pages 15-21 of this tutorial, starting with section “Some Useful Tips”, installing Keras, Pytorch frameworks, checking the device-ID (confirming GPU is active and working) and type/model of the GPU you have allocated for your Colab network and checking the amount of RAM your Colab instance has, serving your notebook. See printed PDF: “Google Colab Free GPU Tutorial Part-2.pdf”

Part-4: Compare Computer Capabilities of your GPU and CPU within your Colab instance.

Reference: https://colab.research.google.com/notebooks/gpu.ipynb

Add code from section “Observe TensorFlow speedup on GPU relative to CPU” and run it within your Colab notebook.  Capture the value of “GPU speedup over CPU:”  Expected values are:
•	31x for Tesla T4 GPU
•	12-12x for Tesla K80 GPU


 
Part-5: Implement simple Neural Network and train a Sequential Keras Model


Assumption: Keras and Tensorflow are already installed within your Colab notebook based on work performed within parts 1,2,3,4.
Reference: “Portions of reading are taken from MachineLearningMastery.docx”
