# Product-Recommendation-Engine-Based-on-Visual-Similarity

The subject of this repository was to develop a very basic recommender engine for fashion products. For this case, the system
should recommend goods that look similar. The idea behind is very simple: if a customer is showing interest towards a specific
product by browsing its page, he may also be interested by products that are visually alike. We will implement CNNs with an
image feature extraction approach, with <code>Keras</code> and <code>TensorFlow</code> packages. The recommender engines were
based on pre-trained models: ResNet50 and VGG16. 

![image](https://user-images.githubusercontent.com/45270023/226437350-a3c84da8-dfb4-4f96-81ff-56c1deb5f005.jpg)

The recommender systems are able to find similar products accurately: most of the time the retrieved products have the same
purpose and look very similar. They certainly work well in terms of shapes; patterns are not always recognized.
