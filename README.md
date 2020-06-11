# Image2Art-Using-CycleGAN

In this <a href='https://arxiv.org/pdf/1703.10593.pdf'> research paper</a>, they present an approach for learning to translate an image from a source domain X to a target domain Y in the absence of paired examples. 

Their goal is to learn a mapping G: X → Y such that the distribution of images from G(X) is indistinguishable from the distribution Y using an adversarial loss. Because this mapping is highly under-constrained, we couple it with an inverse mapping F: Y → X and introduce a cycle consistency loss to enforce F(G(X)) ≈ X (and vice versa). It exactly called CycleGAN.

Datasets are available : https://people.eecs.berkeley.edu/~taesung_park/CycleGAN/datasets/
