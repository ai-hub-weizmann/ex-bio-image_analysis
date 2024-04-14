## ex-bio-image-analysis
This repository contains a link to Ofra Golani's bio-image analysis tutorials.

The first link is a link to Ofra's tutorial about image analysis with Fiji:

# Incorporating Machine Learning Tools into Image Analysis Workflows using Fiji, Ilastik and Stardist

A typical image analysis workflow includes segmentation of regions and objects (eg nuclei or cells), measuring multiple features for objects and regions, and 

quantifying relations between objects. Fiji is an open-source software platform based on ImageJ and a collection of compatible plugins focusing on general purpose

image analysis for life-sciences. It is scriptable and enables fast prototyping of image analysis workflows. Ilastik, StarDist and other Fiji plugins provide an 

easy way to exploits recent advances in machine-learning and deep-learning based algorithms as handy components for use within image analysis workflows. In this 

hands-on workshop we introduce building image analysis workflows using Fiji, Ilastik and StarDist: 

https://github.com/WIS-MICC-CellObservatory/OsteoclastsWorkflow-Tutorial.

Data used within this tutorial is courtsey of Dr. Sabina Winograd-Katz and Prof. Benny Geiger, Weizmann Institute of Science

For questions about the tutorial, please contact me (Avital Steinberg from the AI-hub for science)

Link: https://www.dropbox.com/scl/fo/ofnld2p0i8k5tbip48gn7/h?rlkey=s5leoh3ei1ph7i4iej4bnbynb&dl=0
 
## ZeroCode Deep Learning for BioImage Analysis

This is a link to Ofra Golani's new Zero Code Deep Learning tutorial. If you have a mac with the new silicon chip, it's recommended to use a PC instead:
 
A typical image analysis workflow includes segmentation of regions and objects (eg nuclei or cells), measuring multiple features for objects and regions, and quantifying relations between objects.

There are many approaches for object segmentation and one should choose an appropriate approach for his own task. Deep learning based object segmentation became a leading method for many bioimage analysis (BIA) tasks. However, using them from scratch have a big overload of preparing large training dataset, selecting network architecture and implementing it. Models are usually trained for specific tasks, and are rarely suitable for general purpose applications.

In this tutorial we will use the task of nuclei segmentation learn how to:

1. Use the StarDist Deep-learning instance segmentation for nuclei segmentation within the Fiji image analysis platform, using pre-trained model.

2. Try it on nuclei from different biological experiments, and explore cases where it works well and less so, and try to understand why this happens and what can be done to improve it.

3. We will train our own StarDist models using an easy to use and accessible, code-free solution called ZeroCostDL4Mic, using a given training dataset. We will try it within a Google-colab using a Jupyter Notebook and deploy the trained model within Fiji.

4. We will learn how to prepare ground-truth dataset for training on our own task, and use it to retrain the initial model using our own data.

5. You can then explore the effects of different training parameters and augmentation on the results.

6. You are welcome to explore other options within ZeroCodeDL4Mic.
