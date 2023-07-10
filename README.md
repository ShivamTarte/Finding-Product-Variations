# Finding-Product-Variations
The objective of this code is to perform web scraping on any given Shopify website domain name to extract product variations. The code specifically focuses on retrieving relevant information such as product descriptions and variant details from the website. Once the data is collected, the code applies the DBSCAN clustering algorithm to group similar products together based on their attributes.

The extracted product variants may include details like colors, sizes, or other distinguishing features, depending on how they are presented on the website. By clustering similar products, the code enables the identification of common categories and subcategories, providing insights into customer preferences and behaviors.

To ensure optimal performance, the code tunes the hyperparameters of the DBSCAN algorithm. This involves adjusting values such as epsilon (eps) and minimum samples (min_samples) to achieve effective clustering results. Experimentation with different parameter settings is conducted to find the best configuration for the specific dataset under analysis.
