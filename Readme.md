# DL_Projects  hands-on deep learning experiments

This repository collects compact, runnable deep-learning projects I built while learning and experimenting with neural networks. Projects are intentionally small so you can run them quickly and learn the core ideas without heavy infrastructure.

What you'll find here
- Practical experiments: image classification, generative models, sequence models, and transfer-learning demos.
- Clean notebooks and scripts that show the full flow: data -> model -> training -> quick evaluation.
- Most projects are runnable on a CPU for small datasets; a GPU is recommended for larger experiments.

Quick start
1. Clone:

   git clone https://github.com/vijaykalore/DL_Projects.git

2. Create and activate a virtual environment (PowerShell):

   python -m venv .venv
   .\\.venv\\Scripts\\Activate.ps1

3. Install dependencies for a typical project:

   pip install -r requirements.txt

4. Open the project you want and run the main notebook or script:

   jupyter lab

Project index (open the folder name in this repo)
- Project 01 ( Breast Cance Classification with NN )  breast cancer classification with a simple dense NN.
- Project 02 ( MNIST Digit classification using NN )  baseline dense network on MNIST digits.
- Project 03 ( Dog vs Cat Classification Transfer Learning )  transfer learning with pretrained CNN backbones.
- Project 04 ( CIFAR 10 Object Recognition using ResNet50 )  ResNet50-based classifier on CIFAR-10.
- Project 05 ( Face Mask Detection using CNN )  real-time face mask detector with CNN.
- Project 06 ( Fashion MNIST end-to-end Project )  EDA and classification on Fashion-MNIST.
- Project 07 ( Plant Disease Prediction CNN Deep Leanring Project )  plant leaf disease classifier.
- Project 08 ( Neural Network using PyTorch Breast Cancer Prediction )  PyTorch implementation for breast cancer.
- Project 09 ( Generate Handwritten Digit Images DCGAN )  DCGAN for handwritten digit generation.
- Project 10 ( IMDB reviews Sentiment Analysis LSTM )  LSTM-based sentiment classifier on IMDB.
- Extra Learning Notebooks  supplementary experiments and notes.

Notes and recommendations
- Many projects download data at runtime. Check each project's notebook/header for dataset download steps and local paths.
- If a project contains a `requirements.txt` file, use it to install the exact dependencies for reproducibility.
- For visualization-heavy projects, add a `results/` folder with sample outputs (images, GIFs) to the project folder  this helps reviewers quickly see results.

Ideas to make this repo more attractive
- Add a short `README.md` inside the top 4 projects with: project goal, dataset source, main notebook/script, and one-sentence results.
- Add 23 representative screenshots (predictions, loss curves, generated samples) to the root README or the project folders.
- Add an MIT `LICENSE` to encourage reuse.

Contributing
- Want to contribute? Open an issue describing the change or create a focused pull request. Please include a short README for new projects and a note about how you tested changes.

Enjoy exploring  run the notebooks, change hyperparameters, and make things your own.

 Vijay
