## Machine Learning Assignment: Clustering images by RGB (Red, Green, Blue) values

A set of images that come from four categories: sunsets, rivers, trees and forests, and cloudy skies is provided. For each image the average intensity of its red, green, and blue pixels is also given, so there is a 3-dimensional representation of the data.

The task is to find a good clustering of these images using Expectation Maximization (EM) algorithm. Ideally the algorithm would find clusters that roughly correspond to the four image categories. Machine Learning libraries are not used.  

As the result, the model is good at distinguishing ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `cloudy skies` and ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `sunsets`, but seems to have difficulty in distinguishing between ![#c5f015](https://placehold.it/15/4B872F/000000?text=+) `rivers` and ![#c5f015](https://placehold.it/15/4B872F/000000?text=+) `forests`. To achieve a better performance, a richer representation of the data than simply the average [R G B] values for each image is needed.
