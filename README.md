# PairGAN
Generate bio scans superimposing the input scan

## Description
Generative model capable of outputing a pair of scans of cell cross sections given the corresponding superimposed scan. Model based on conventional DCGAN.

### Dependencies
* numpy 1.20.1
* tensorflow 2.3.0
* keras 2.4.3
* matplotlib 3.4.2

### Installing
* clone the repository or download directly

### Executing program
* Run the files in jupyter notebook.
* PairGAN to be used for training with given dataset, latent dimension can be modified manully in the last block.
* Generate file to be used to generate scans with pretrained models, path to input image required in the last block.

## Link to data and pretrained models
* Data: https://drive.google.com/file/d/17Pph1KJvQ8fxul8wqPry2JTNI6dFm2Up/view?usp=sharing
* Model: https://drive.google.com/file/d/12_XEYLh-SCvJvEaIqabIu9oCfQo4TaXu/view?usp=sharing

## Author
* Yifei Zhi
* yifei.zhi@student.uts.edu.au

## Acknowledgments
Program structure based on DCGAN section in:
* Brownlee, J. (2020). Generative Adversarial Networks with Python (v1.5).
