# Social Media Engagement Analysis

## Installation

To run the project, you'll need to have the following Python packages installed. You can install them using the following command:

```bash
pip install scikit-learn numpy pandas matplotlib seaborn
```

## Unsupervised Learning
Unsupervised learning is a machine learning paradigm where the algorithm learns patterns from input data without explicit supervision or labeled responses. Unlike supervised learning, where the algorithm is trained on labeled data to make predictions, unsupervised learning algorithms operate on input data without labeled responses, seeking to discover hidden structures or intrinsic patterns within the dataset. This approach is particularly useful when dealing with unlabelled data or when the task involves discovering underlying relationships or grouping similar data points together. Unsupervised learning techniques are widely used across various domains, including data mining, pattern recognition, and exploratory data analysis.<center><img src=https://static.javatpoint.com/tutorial/machine-learning/images/unsupervised-machine-learning-1.png></center>

## K means Clustering
K-means clustering is a popular unsupervised learning algorithm used for partitioning a dataset into K distinct, non-overlapping clusters. The goal of K-means clustering is to group data points into clusters based on similarity, where each cluster is represented by its centroid, the mean of the data points belonging to that cluster. The algorithm iteratively assigns data points to the nearest centroid and then recalculates the centroids based on the mean of the assigned data points. This process continues until the centroids no longer change significantly or a specified number of iterations is reached. K-means clustering is widely used for various applications, including customer segmentation, image processing, and anomaly detection, providing an efficient and scalable solution for clustering large datasets.<center><img src=https://assets.blog.code-specialist.com/k_means_animation_6cdd31d106.gif></center>

## About Dataset
The dataset contains features of social media posts. Here are the explanations of the variables in the dataset:

### Features
| Variable            | Explanation                                                                     |
|---------------------|---------------------------------------------------------------------------------|
| num_reactions       | Total number of reactions received by the post                                  |
| num_comments        | Total number of comments received by the post                                   |
| num_shares          | Number of shares of the post                                                    |
| num_likes           | Number of "likes" received by the post                                          |
| num_loves           | Number of "loves" reactions received by the post                                |
| num_wows            | Number of "wows" reactions received by the post                                 |
| num_hahas           | Number of "haha" reactions received by the post                                 |
| num_sads            | Number of "sad" reactions received by the post                                  |
| num_angrys          | Number of "angry" reactions received by the post                                |
| status_type_link    | 1 if the post contains a link, 0 otherwise                                      |
| status_type_photo   | 1 if the post contains a photo, 0 otherwise                                     |
| status_type_status  | 1 if the post contains text, 0 otherwise                                        |
| status_type_video   | 1 if the post contains a video, 0 otherwise                                     |

### Project Target
- Complete exploration of dataset along with interactions analysis and status type analysis.
- Segregating the training instances based on given features.
- Finding optimal number of clusters based on different types of metrics.
- Visualization of the clusters in reduced dimensional space.
- Analysis of features across clusters.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the [LICENSE]() file for details.

## Contact
For questions or issues, please contact me (Soumyadeep Ghosh) via mail: soumyadeepghosh57@gmail.com