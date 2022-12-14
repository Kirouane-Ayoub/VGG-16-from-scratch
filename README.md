# VGG-16-from-scratch
VGG16 is a convolution neural network (CNN ) architecture that was used to win ILSVR (Imagenet) competition in 2014. It is considered to be one of the most excellent vision model architectures to date. The most unique thing about VGG16 is that instead of having a large number of hyper-parameter they focused on having convolution layers of 3x3 filter with a stride 1 and always used the "same" padding and "maxpool" layer of 2x2 filter of stride 2. It follows this arrangement of convolution and "maxpool" layers consistently throughout the whole architecture. In the end, it has 2 FC (fully connected layers) followed by a softmax for output. The 16 in VGG16 refers to it has 16 layers that have weights. This network is a pretty extensive network and it has about 138 million parameters.

![vgg16](https://user-images.githubusercontent.com/99510125/204149993-b35003a2-03c8-43d4-99e7-01e73b36d560.png)


For more information visit : https://www.linkedin.com/pulse/everything-you-need-know-vgg16-ayoub-kirouane
