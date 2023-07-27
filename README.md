# multiobjective_adversarial_examples
Deep neural networks like ResNet and VGG16 are very accurate in classifying images. However, recent studies have proven that these models can misclassify if pixels in the image are changed in very small ways. The changes are small enough so that a human will still correctly recognize the image. Algorithms that change images by adding a perturbation to cause misclassification are known as adversarial attacks. They are commonly built and studied in academia to improve the security of neural networks.

I have built an adversarial example algorithm that uses multiobjective optimization. The algorithm returns a pareto front of adversarial images for a given input image. To illustrate how this works, below is an example of a fighter jet image from the CIFAR 10 dataset:

To study the perofrmance of this algorithm I have used images from the CIFAR10 and ImageNet datasets for my experiments. 


