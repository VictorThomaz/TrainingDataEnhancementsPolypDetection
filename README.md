# Training Data Enhancements for Improving Colonic Polyp Detection Using Deep Convolutional Neural Networks

ABSTRACT

BACKGROUND: Over the last years, the most relevant results in the context of polyp detection were achieved through deep learning techniques. However, the most common obstacles in this field are still the lack of variability of data as well as its amount. This paper describes a method to reduce this limitation and improve polyp detection results using publicly available colonoscopic datasets.

METHODS: To address this issue, we increased the number and variety of images from the original dataset. Our method consists on adding polyps to the dataset images. The developed algorithm performs a rigorous selection of the best region within the image to receive the polyp. This procedure preserves the realistic features of the images while creating more diverse samples for training purposes. Our method allows copying existing polyps to new non-polypoid target regions. We also develop a strategy to generate new and more varied polyps through generative adversarial neural networks. Hence, the developed approach enriches the training data, creating automatically new samples with their appropriate labels.

RESULTS: We applied the proposed data enhancement over a colonic polyp dataset. Thus, we can assess the effectiveness of our approach through a Faster R-CNN detection model. Performance results show improvements over the polyp detections while reducing the false-negative rate. The experimental results also show better recall metrics in comparison with both the original training set and other studies in the literature.

CONCLUSION: We demonstrate that our proposed method has the potential to increase the data variability and number of samples in a reduced polyp dataset, improving the polyp detection rate and recall values. These results open new possibilities for advancing the study and implementation of new methods to improve computer-assisted medical image analysis.
