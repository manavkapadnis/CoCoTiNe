# CoCoTiNe : Compositional Committees of Tiny Networks

This repository is the official repository of CoCoTiNe paper submitted at the [28th International Conference on Neural Information Processing (ICONIP2021)](https://iconip2021.apnns.org/).

## Authors - Goh Howe Seng, Manav Nitin Kapadnis, Tomas Maul

Deep neural networks tend to be accurate but computationally expensive, whereas ensembles tend to be fast but do not capitalize on hierarchical representations. This paper proposes an approach that attempts to combine the advantages of both approaches. Hierarchical ensembles represent an effort in this direction, however they are not compositional in a representational sense, since they only combine classifier decisions and/or outputs. We propose to take this effort one step further in the form of compositional ensembles, which exploit the composition of the hidden representations of classifiers, here defined as tiny networks on account of being neural networks of significantly limited scale. As such, our particular instance of compositional ensembles is called Compositional Committee of Tiny Networks (CoCoTiNe). We experimented with different CoCoTiNe variants involving different types of composition, input usage, and ensemble decisions. The best variant demonstrated that CoCoTiNe is more accurate than standard hierarchical committees, and is relatable to the accuracy of vanilla Convolutional Neural Networks, whilst being **25.7 times faster in a standard CPU setup**. In conclusion,
the paper demonstrates that compositional ensembles, especially in the context of tiny networks, are a viable and efficient approach for combining the advantages of deep networks and ensembles.

### Sections
1. [Paper](#system-description-paper)
2. [Architecture](#architecture)
3. [Noteworthy Achievements](#achieivements) <!-- *please change the header over here* -->
4. [Implementational Details](#implementation-details)
5. [Citing](#Cite-details)
6. [Author Contact Details](#authors-info)

## Paper  (pending)
Our paper can be found [here](to be added).  
Our presentation for the conference can be found [here](to be added).

## Architecture

The Transformer Architecture used by us is shown in the figure. We used the pre-trained models realeased by [HuggingFace](https://huggingface.co/transformers/pretrained_models.html).

![Transformer Architecture](https://github.com/manavkapadnis/Enigma_ArgMining/blob/main/model_architecture.png)

  

  
  

- All the files are meant to be executed on Google Colab environment.
 
- The files are serated into folder by datasets. Each folder consists of all variant of experiments conduct of that datasets.

- <Final HiCoTiNe MNIST.ipynb> at the root directory are meant to be an example of the final implementation of HiCoTiNe tested on MNIST dataset.

- For HiCoTiNe v1.1 to v3 in each folder, the file <HiCoTiNe1 Layer 1 'dataset name'.ipynb> that act as a control for first HiCo layer had to be executed first.
	- Google Drive account had to be mounted during execution of HiCoTiNe v1 to v3.

- Besides that, every thing is ran normally by connecting to an environment and run each cell.


The original Google Colab files can be accessed at https://drive.google.com/drive/folders/1IcMgBMvcjZdkiMC85WgRWTEqOIMhp3nK?usp=sharing
