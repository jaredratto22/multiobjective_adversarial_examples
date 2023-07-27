# multiobjective_adversarial_examples
Deep neural networks, like ResNet and VGG16, are very accurate in classifying images. However, recent studies have proven that these models can misclassify if pixels in the image are changed in very small ways. The changes are small enough so that a human will still correctly recognize the image. Algorithms that change images by adding a perturbation to cause misclassification are known as adversarial attacks. They are commonly  studied in academia to improve the security of neural networks.

I have built an adversarial example algorithm that uses multiobjective optimization where the objectives are to create adversarial images while also minimizing both its number of changed pixels and the amount of change applied to each pixel. For a given input image, the algorithm returns a [pareto front](https://en.wikipedia.org/wiki/Pareto_front) of adversarial images that vary by the number of pixels changed. To illustrate how this works, below is an example of a fighter jet image from the CIFAR10 dataset:



