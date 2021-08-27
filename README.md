# Amazon_sales_recommedation
## Objective 
Build a recommender system that recommends similar apparel items in ecommerce using text and image data

## Deliberables
-Scraped the data from amazon e-commerce using ‘auto scrap’ library

-After cleaning we worked on 7 features (asin, brand, color, product_type_name, medium_image_url, title, formatted_price) out of 19 features and 28K objects

-Finally taken 16K rows after deduping, and text pre-processing, out of 180k rows initially
-In BoW, TF-IDF and W2V, W2V (word to vector)  showing grateful results
-In visual features based on similarity we used CNN model (VGG16) that is showing good recommendation
-All the models could be tested ‘A|B testing’ techniques

