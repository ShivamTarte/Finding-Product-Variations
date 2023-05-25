# Finding-Product-Variations
This code is designed to extract product variations from any Shopify website URL using web scraping techniques. The code extracts relevant information from the website, such as product descriptions and variant details, and then applies DBSCAN clustering algorithm to group similar products together.

The extracted variants can include attributes such as colors, sizes, or other product features, depending on how they are represented on the website. The clustering algorithm is used to group products together based on their similarity, which can help identify common product categories and subcategories, and potentially reveal insights about customer preferences and behaviors.

To ensure the clustering algorithm performs optimally, the hyperparameters for the DBSCAN algorithm are tuned, with the eps and min_samples values adjusted to achieve good clustering results. This may involve experimenting with different values to find the optimal settings for the specific dataset being analyzed.
