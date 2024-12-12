Few Shot classification is a task to classify a class only from a few label. Few Shot classification is really important because  usually deep learning algorithm need a lot of clean data and label to perform well on classification task.
labelling clean data is not easy and can be very expensive. for example when we want to train a deep learning model to classify new disease from x-ray images, labelling this kind of data is really expensive and possibly rare(there is little patient), so to perform well on this kind of task we need algorithm that can do few shot classification.

 In this colab we will use omniglot dataset to do few shot learning. We will also use <a href = 'https://www.pytorchlightning.ai/'>pytorch lightning</a> as the deeplearning framework.
