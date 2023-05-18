# COVID-19-project

The COVID-19 pandemic has afflicted all our lives, it nearly brought our whole world to a stop for months. Several methods were developed to detect the virus. RT-PCR being one of the most popular ones. These methods were all, however, time-consuming and resource-intensive. An alternate method could have been very useful in quick detection of the virus, which is very essential. Quarantining the infected individuals is a priority during such a pandemic. And to do that, recognising the virus in an individual quickly would be very much a boon. The advancements in deep learning and computer vision have shown promising results in extracting relevant features from medical images and making accurate predictions using deep learning. This same technology can be applied to Chest X-Ray images to detect COVID-19.

In our project, we employed transfer learning techniques to train convolutional neural network (CNN) models for the purpose of detecting COVID-19. We leveraged the power of pre-trained architectures, specifically VGG16, VGG19, and DenseNet121, to expedite the model training process and benefit from their learned features. Additionally, we developed our own CNN model to compare its performance against the pre-trained models.

By utilizing transfer learning, we were able to leverage the knowledge and features learned by these state-of-the-art architectures from large-scale datasets. This enabled us to effectively extract meaningful information from the Chest X-Ray images related to COVID-19 detection. Transfer learning not only saved us significant computational resources but also enhanced the accuracy and efficiency of our models

Dataset: https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database

Evaluating the Models:

We tested the accuracy scores of all the models on the test set. The custom model achieved 89% accuracy. So, that will be the score to beat for our other models. As expected, they all performed better than our custom model. VGG19 has 93% accuracy on the test set, VGG16 has 94% and DenseNet121 performed the best of all at 95%.

Conclusion:

As expected, the pretrained models have performed far better than our custom model. This demonstrates the usefulness of transfer learning. We were able to achieve nearly 95% accuracy with the pretrained models. This demonstrates the effectiveness of deep learning in COVID-19 detection from chest X-Rays.

However, it is important to keep in mind that this is not a definitive way to diagnose the virus. It can be used as a way to give a quick diagnosis to help in early detection. Additional research and clinical trials will be needed to ensure the robustness of this method and its reliability. This project can be used as a foundation for future development in this field.
