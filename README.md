
# Customer Market Segmentation using K-means Clustering

This repository contains the code and documentation for a customer segmentation project using the K-means clustering algorithm. The goal of this project is to categorize customers based on their purchasing behaviors, allowing businesses to tailor targeted marketing strategies. The determination of the optimal number of clusters is a crucial step, and we utilized both the Elbow Method and Silhouette Score Method for validation.

## Screenshots

![distortion score](https://github.com/vibhudixit123/CUSTOMER_SEGMENTATION/assets/104568465/642073a7-1ecb-432a-a387-55148f8e06b6)

![clusters](https://github.com/vibhudixit123/CUSTOMER_SEGMENTATION/assets/104568465/e304cd43-5aa5-42a3-a69f-e4bb8bc372ff)

![Silhouette Score](https://github.com/vibhudixit123/CUSTOMER_SEGMENTATION/assets/104568465/24514c6c-76a3-4b31-8e98-db3c049eaa09)

![3D plot](https://github.com/vibhudixit123/CUSTOMER_SEGMENTATION/assets/104568465/30ca5b5e-80fd-4bc7-ad52-36c41615cc1d)
![Silhouette plot](https://github.com/vibhudixit123/CUSTOMER_SEGMENTATION/assets/104568465/59025c74-c645-4fa3-807b-0bcb5a20afe1)



## DATA
The customer data is stored in the my_store_customer.csv file. The dataset includes relevant features such as purchase history, frequency, and other characteristics that are essential for customer segmentation.
## Method
K-means Clustering:

The K-means clustering algorithm was employed to categorize the customer base into distinct segments based on their similarities in purchasing behaviors.

Optimal Cluster Number Determination:

We used two methods for determining the optimal number of clusters:
Elbow Method: An inflection point was observed at 5 and 6 clusters, indicating a potential optimal number.
Silhouette Score Method: Silhouette plots were used to visually represent the consistency and separation of clusters.

Visualization:

3D plots were constructed to provide an intuitive understanding of the distribution of customers within each cluster.
## License

[MIT](https://choosealicense.com/licenses/mit/)

