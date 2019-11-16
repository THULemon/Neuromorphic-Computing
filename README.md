# Neuromorphic Computing

Many works towards **Neurmorphic Computing** have published in devices, circuits, architecture, and algorithms. However, these works are disperse and there are not a unitive review for reaseachers in this field. The **Neurmorphic Computing** project aims to collect the works in neuromorphic/ neuro-inspired computing field to help the researchers to find the information easily. The information is collected from the internet and this project is made publicly available on a non-commercial basis.

This project is started by Tsinghua's [LEMON](http://stor.ime.tsinghua.edu.cn) Group.

**Advisors**: Huqiang Wu, Bin Gao, Jianshi Tang, He Qian

**Contributors**: Wenqiang Zhang, Wenbin Zhang, Xin Mu, Yijun Li, Songtao Wei, Qi Qin

If you have any technical questions or comments, pleasue rise an issue or contact with Wenqiang Zhang (zhang_wenqiang@outlook.com).

*****************

**Table of Contents**:

- [Neuromorphic Computing](#neuromorphic-computing)
  - [Overview](#overview)
  - [Devices](#devices)
    - [Emerging devices and applications](#emerging-devices-and-applications)
    - [Device characterization and modeling](#device-characterization-and-modeling)
  - [Array and demonstrations](#array-and-demonstrations)
  - [Chips](#chips)
    - [SNN chips](#snn-chips)
    - [DNN chips](#dnn-chips)
  - [Architectures](#architectures)
  - [Algorithms](#algorithms)
  - [Topics](#topics)
    - [Tutorial and Survey](#tutorial-and-survey)
    - [Dataset and Benchmark](#dataset-and-benchmark)

*****************

## Overview

## Devices

Neuromorphic computing with novel memory devices has attracted considerable attention. Tremendous efforts have been made to implement artificial neurons and artificial synapses using a variety of emerging devices, such as phase-change memory (PCM), Mott memristor, resistive random-access memory (RRAM), magnetic random-access memory (MRAM), conductive-bridge random-access memory(CBRAM), ferroelectric ﬁeld-effect transistors(FeFET). The neuron-like integrate-and-fire behaviors are usually realized by the threshold switching characteristics of these devices, while the synaptic weight changes in artificial synapses are modulated by means of analog nonvolatile switching onto different levels of resistance (or conductance). Consequently, these emerging devices have attracted significant attention in the past decade as a key enabler of new computing paradigms.

### Emerging devices and applications

1. [The missing memristor found](https://doi.org/10.1038/nature06932), *Nature*, 2008. (HP Labs)
2. [Nanoscale memristor device as synapse in neuromorphic systems](https://doi.org/10.1021/nl904092h), *Nano Letter*, 2010. (University of Michigan)
3. [A fast, high-endurance and scalable non-volatile memory device made from asymmetric Ta2O5-xTaO2-xbilayer structures](https://doi.org/10.1038/nmat3070), *Nature Materials*, 2011. (Samsung Electronics)
4. [A ferroelectric memristor](https://doi.org/10.1038/nmat3415), *Nature Materials*, 2012. (Campus de l’Ecole Polytechnique)
5. [A scalable neuristor built with Mott memristors](https://doi.org/10.1038/nnano.2008.160), *Nature Materials*, 2013. (HP Labs)
6. [Experimental Demonstration of a Second-Order Memristor and Its Ability to Biorealistically Implement Synaptic Plasticity](https://doi.org/10.1021/acs.nanolett.5b00697), *Nano Letters*, 2015. (University of Michigan)
7. [Sub-10 nm Ta Channel Responsible for Superior Performance of a HfO2 Memristor](https://doi.org/10.1038/srep28525), *Scientific Reports*, 2016. (University of Massachusetts)
8. [Stochastic phase-change neurons](https://doi.org/10.1038/nnano.2016.70), *Nature Nanotechnology*, 2016. (IBM)
9. [A magnetic synapse: multilevel spin-torque memristor with perpendicular anisotropy](https://doi.org/10.1038/srep31510), *Scientific Reports*, 2016. (Université Paris-Saclay)
10. [Memristors with diffusive dynamics as synaptic emulators for neuromorphic computing](https://doi.org/10.1038/NMAT4756), *Nature Materials*, 2016. (University of Massachusetts)
11. [A non-volatile organic electrochemical device as a low-voltage artificial synapse for neuromorphic computing](https://doi.org/)10.1038/nmat4856, *Nature Materials*, 2016. (Stanford University)
12. [Chaotic dynamics in nanoscale NbO2 Mott memristors for analogue computing](https://doi.org/10.1038/nature23307), *Nature*, 2017. (HP Labs)
13. [Brain-Inspired Photonic Neuromorphic Devices using Photodynamic Amorphous Oxide Semiconductors and their Persistent Photoconductivity](https://doi.org/10.1002/adma.201700951), *Advanced materials*, 2017. (Sungkyunkwan University)
14. [Neuromorphic computing with nanoscale spintronic oscillators](https://doi.org/10.1038/nature23011), *Nature*, 2017. (Université Paris-Saclay)
15. [Flexible three-dimensional artificial synapse networks with correlated learning and trainable memory capability](https://doi.org/), *Nature communications*, 2017. (Hanyang University)
16. [A High-On/Off-Ratio Floating-Gate Memristor Array on a Flexible Substrate via CVD-Grown Large-Area 2D Layer Stacking](https://doi.org/10.1002/adma.201703363), *Advanced materials*, 2008. (Sungkyunkwan University)
17. [ECRAM as Scalable Synaptic Cell for High-Speed, Low-Power Neuromorphic Computing](https://doi.org/10.1109/IEDM.2018.8614551), *IEDM*, 2018. (IBM)
18. [Ion Gated Synaptic Transistors Based on 2D van der Waals Crystals with Tunable Diffusive Dynamics](https://doi.org/10.1002/adma.201800195), *Advanced Materials*, 2018. (Peking University)
19. [Low-Power, Electrochemically Tunable Graphene Synapses for Neuromorphic Computing](https://doi.org/10.1002/adma.201802353), *Advanced Materials*, 2018. (The University of Pittsburgh)
20. [Multi-terminal memtransistors from polycrystalline monolayer molybdenum disulfide](https://doi.org/10.1038/nature25747), *Nature*, 2018. (Northwestern University)
21. [Synaptic Barristor Based on Phase-Engineered 2D Heterostructures](https://doi.org/10.1002/adma.201801447), *Nature Materials*, 2018. (Korea University)
22. [First Demonstration of a Logic-Process Compatible Junctionless Ferroelectric FinFET Synapse for Neuromorphic Applications](https://doi.org/10.1109/LED.2018.2852698), *EDL*, 2018. (Korea Advanced Institute of Science and Technology (KAIST))
23. [SiGe epitaxial memory for neuromorphic computing with reproducible high performance based on engineered dislocations](https://doi.org/10.1038/s41563-017-0001-5), *Nature Materials*, 2018. (Massachusetts Institute of Technology)
24. [All-Solid-State Synaptic Transistor with Ultralow Conductance for Neuromorphic Computing](https://doi.org/10.1002/adfm.201804170), *Advanced functional materials*, 2018. (Chinese Academy of Sciences)
25. [Ultra-low Power Hf0.5Zr0.5O2 based Ferroelectric Tunnel Junction Synapses for Hardware Neural Network Applications](https://doi.org/10.1039/c8nr04734k), *Nanoscale*, 2018. (Fudan University)
26. [Memristor crossbar arrays with 6-nm half-pitch and 2-nm critical dimension](https://doi.org/10.1038/s41565-018-0302-0), *Nature Nanotechnology*, 2019. (University of Massachusetts)
27. [Parallel programming of an ionic floating-gate memory array for scalable neuromorphic computing](https://doi.org/10.1126/science.aaw5581), *Science*, 2019. (Sandia National Laboratories)
28. [Phase-change heterostructure enables ultralow noise and drift for memory operation](https://doi.org/10.1126/science.aay0291), *Science*, 2019. (Shenzhen University)

### Device characterization and modeling

1. [Memristive switching mechanism for metal/oxide/metal nanodevices](https://doi.org/10.1038/nnano.2008.160), *Nature Nanotechnology*, 2008. (HP Labs)
2. [Atomic structure of conducting nanofilaments in TiO2 resistive switching memory](https://doi.org/10.1038/nnano.2009.456), *Nature Nanotechnology*, 2010. (Seoul National University)
3. [Observation of conducting filament growth in nanoscale resistive memories](https://doi.org/10.1038/ncomms1737), *Nature Communications*, 2012. (The University of Michigan)
4. [In situ observation of filamentary conducting channels in an asymmetric Ta2O5-x/TaO2-x bilayer structure](https://doi.org/10.1038/ncomms3382), *Nature Communications*, 2013. (Samsung Electronics)
5. [Nanoscale cation motion in TaOx, HfOx and TiOx memristive systems](https://doi.org/10.1038/nnano.2015.221), *Nature Nanotechnology*, 2016. (Chonbuk National University)
6. [Direct Observations of Nanofilament Evolution in Switching Processes in HfO2-Based Resistive Random Access Memory by In Situ TEM Studies Chao](https://doi.org/10.1002/adma.201602976), *Nature Materials*, 2017. (Chinese Academy of Sciences)
7. [Nanometer-Scale Phase Transformation Determines Threshold and Memory Switching Mechanism](https://doi.org/10.1002/adma.201701752), *Advanced materials*, 2017. (Pohang University ofScience and Technology)
8. [Dual functionality of threshold and multilevel resistive switching characteristics in nanoscale HfO2-based RRAM devices for artificial neuron and synapse elements](https://doi.org/10.1016/j.mee.2017.09.001), *Microelectronic Engineering*, 2017. (Pohang University ofScience and Technology)
9. [Ionic modulation and ionic coupling effects in MoS2 devices for neuromorphic computing](https://doi.org/10.1038/s41563-018-0248-5), *Nature Materials*, 2019. (University of Michigan)

## Array and demonstrations

1. [Pattern classiﬁcation by memristive crossbar circuits using ex situ and in situ training](https://doi.org/10.1038/ncomms3072), *Nature Communication*, 2013. (University of California, Santa Barbara)
2. [Neuromorphic Hardware System for Visual Pattern Recognition With Memristor Array and CMOS Neuron](https://doi.org/10.1109/TIE.2014.2356439), *IEEE Transactions on Industrial Electronics*, 2014. (Gwangju Institute of Science and Technology)
3. [Brain-like associative learning using a nanoscale non-volatile phase change synaptic device array](https://doi.org/10.3389/fnins.2014.00205), *Nature* ,2015. (Stanford University)
4. [Training and operation of an integrated neuromorphic network based on metal-oxide memristors](https://doi.org/10.3389/fnins.2014.00205), *Nature*, 2015. (University of California, Santa Barbara)
5. [Data Clustering using Memristor Networks](https://doi.org/10.1038/srep10492), *Scientific report*, 2015. (University of Michigan)
6. [Unsupervised learning in probabilistic neural networks with multi-state metal-oxide memristive synapses](https://doi.org/10.1038/ncomms12611), *Nature Communication*, 2016. (University of Southampton)
7. [Sparse coding with memristor networks](https://doi.org/10.1038/NNANO.2017.83), *Nature Nanotechnology*, 2017. (University of Michigan)
8. [Temporal correlation detection using computational phase-change memory](https://doi.org/10.1038/s41467-017-01481-9), *Nature Communication*, 2017. (IBM)
9. [Reservoir computing using dynamic memristors for temporal information processing](https://doi.org/10.1038/s41467-017-02337-y), *Nature Communication*, 2017. (University of Michigan)
10. [Face classification using electronic synapses](https://doi.org/10.1038/ncomms15199), *Nature Communication*, 2017. (Tsinghua University)
11. [Experimental Demonstration of Feature Extraction and Dimensionality Reduction Using Memristor Networks](https://doi.org/10.1021/acs.nanolett.7b00552), *Nano Letters*, 2017. (The University of Michigan)
12. [K‐means Data Clustering with Memristor Networks](https://doi.org/10.1021/acs.nanolett.8b01526), *Nano Letters*, 2017. (The University of Michigan)
13. [Equivalent-accuracy accelerated neural- network training using analogue memory](https://doi.org/10.1038/s41586-018-0180-5), *Nature*, 2018. (IBM)
14. [Implementation of multilayer perceptron network with highly uniform passive memristive crossbar circuits](https://doi.org/10.1038/s41467-018-04482-4), *Nature Communication*, 2018. (University of California, Santa Barbara)
15. [Efficient and self-adaptive in-situ learning in multilayer memristor neural networks](https://doi.org/10.1038/s41467-018-04482-2), *Nature Communication*, 2018. (University of Massachusetts)
16. [Spike-timing-dependent plasticity learning of coincidence detection with passively integrated memristive circuits](https://doi.org/10.1038/s41467-018-07757-y), *Nature Communication*, 2018. (University of California, Santa Barbara)
17. [Analogue signal and image processing with large memristor crossbar](https://doi.org/10.1038/s41928-017-0002-z), *Nature Electronics*, 2018. (University of Massachusetts)
18. [Fully memristive neural networks for pattern classification with unsupervised learning](https://doi.org/10.1038/s41928-018-0023-2), *Nature Electronics*, 2018. (University of Massachusetts)
19. [Demonstration of Generative Adversarial Network by Intrinsic Random Noises of Analog RRAM Devices](https://doi.org/10.1109/IEDM.2018.8614483), *IEDM*, 2018. (Tsinghua University)
20. [Reinforcement learning with analogue  memristor arrays](https://doi.org/10.1038/s41928-019-0221-6), *Nature Electronics*, 2019. (University of Massachusetts)
21. [Temporal data classification and forecasting using a memristor-based reservoir computing system](https://doi.org/10.1038/s41928-019-0313-3), *Nature Electronics*, 2019. (University of Michigan)
22. [Long short-term memory networks in memristor crossbar arrays](https://doi.org/10.1038/s42256-018-0001-4), *Nature Machine Intelligence*, 2019. (University of Massachusetts)
23. [In situ training of feed-forward and recurrent convolutional memristor networks](https://doi.org/10.1038/s42256-019-0089-1), *Nature Machine Intelligence*, 2019. (University of Massachusetts)
24. [Associative Memory for Image Recovery with a High‐Performance Memristor Array ](https://doi.org/10.1002/adfm.201970209 ), *Advanced Functional Materials*, 2019. (Tsinghua University)

## Chips

### SNN chips

1. IBM's TrueNorth: [A million spiking-neuron integrated circuit with a scalable communication network and interface](https://doi.org/10.1126/science.1254642), *Science*, 2014.
2. Intel's Loihi: [Loihi: A Neuromorphic Manycore Processor with On-Chip Learning](https://doi.org/10.1109/MM.2018.112130359), *IEEE Micro*, 2018.
3. Tsinghua's Tianjic: [Towards artificial general intelligence with hybrid Tianjic chip architecture](https://doi.org/10.1038/s41586-019-1424-8), *Nature*, 2019.

### DNN chips

## Architectures

## Algorithms

## Topics

### Tutorial and Survey

**Lectures**:

1. The Chua Lectures: From Memristors and Cellular Nonlinear Networks to the Edge of Chaos. Links: [youku](https://v.youku.com/v_show/id_XMTg1MjQwMzg3Ng==.html?spm=a2h0j.11185381.listitem_page1.5!12~A), [youtube](https://www.youtube.com/playlist?list=PLtS6YX0YOX4eAQ6IrOZSta3xjRXzpcXyi)

**Books**:

1. [Analog VLSI Implementation of Neural Systems](https://www.springer.com/gp/book/9780792390404), edited by Carver Mead and Mohammed Ismail, 1989.
2. [Principles of Neural Design](https://mitpress.mit.edu/books/principles-neural-design), by Peter Sterling and Simon Laughlin, 2015.

**Reviews**:

1. [Memristive switching mechanism for metal/oxide/metal nanodevices](https://doi.org/10.1038/nnano.2008.160), *Nature Nanotechnology*. 2008. [Device]
2. [Phase Change Memory](https://doi.org/10.1109/JPROC.2010.2070050), *Proceeding of IEEE*, 2010. [Device]
3. [Neuromorphic silicon neuron circuits](https://doi.org/10.3389/fnins.2011.00073), Frontiers in Neuroscience, 2011. [Circuit]
4. [Metal–Oxide RRAM](https://doi.org/10.1109/JPROC.2012.2190369), *Proceeding of IEEE*, 2012. [Device]
5. [Memristive devices for computing](https://doi.org/10.1038/NNANO.2012.240), *Nature Nanotechnology*, 2012. [Device]
6. [Neuromorphic computing using non-volatile memory](https://doi.org/10.1080/23746149.2016.1259585), *Advances in Physics: X*, 2017. [Device]
7. [A Survey of Neuromorphic Computing and Neural Networks in Hardware](https://arxiv.org/abs/1705.06963), *Arxiv*, 2017. [Chip]
8. [In-memory computing with resistive switching devices](https://doi.org/10.1038/s41928-018-0092-2), *Nature Electronics*, 2018. [Device]
9. [Organic electronics for neuromorphic computing](https://doi.org/10.1038/s41928-018-0103-3), *Nature Electronics*, 2018. [Device]
10. [Neuro-inspired Computing With Emerging Nonvolatile Memory](https://doi.org/10.1109/JPROC.2018.2790840), *Proceeding of IEEE*, 2018. [Device]
11. [Large-Scale Neuromorphic Spiking Array Processors: A Quest to Mimic the Brain](https://doi.org/10.3389/fnins.2018.00891), *Frontiers in Neuroscience*, 2018. [Chip]
12. [Memristive crossbar arrays for brain-inspired computing](https://doi.org/10.1038/s41563-019-0291-x), *Nature Materials*, 2019. [Array]
13. [Bridging Biological and Artificial Neural Networks with Emerging Neuromorphic Devices: Fundamentals, Progress, and Challenges](https://doi.org/10.1002/adma.201902761), *Advanced Materials*, 2019. [Device]

### Dataset and Benchmark

1. [MNIST](http://yann.lecun.com/exdb/mnist): The MNIST database of handwritten digits has a training set of 60,000 examples, and a test set of 10,000 examples.
2. [MNIST-DVS](http://www2.imse-cnm.csic.es/caviar/MNISTDVS.html): The MNIST-DVS database consists of a set of 30,000 DVS recordings of different handwritten digits. A total of 10,000 original 28x28 pixel handwritten digit images from MNIST were upscaled using smoothing interpolation algorithms to three different scales. Each upscaled digit was then displayed on an LCD monitor with slow motion and a 128x128 pixel DVS (Dynamic Vision Sensor) was used to record the moving digits.
3. [SVHN](http://ufldl.stanford.edu/housenumbers/): SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with minimal requirement on data preprocessing and formatting.
4. [CIFAR](http://www.cs.toronto.edu/~kriz/cifar.html): The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. The CIFAR-100 dataset dataset is just like the CIFAR-10, except it has 100 classes containing 600 images each. There are 500 training images and 100 testing images per class.
5. [ImageNet](http://www.image-net.org/): ImageNet is an image database organized according to the WordNet hierarchy (currently only the nouns), in which each node of the hierarchy is depicted by hundreds and thousands of images.
6. [Microsoft's COCO](http://cocodataset.org/#overview): COCO is a large-scale object detection, segmentation, and captioning dataset.
