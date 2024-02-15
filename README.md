# eCommerceEventsCosmetics
Repository made for DataGlowUp#30, a challenge created by Heitor Sassaki on Linkedin, ir order to instigate the creation of a data analysis portfolio. This analysis is about an Cosmetics eCommerce Shop

---

# About the dataset
https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-cosmetics-shop

## About the model (~1h)
![image](https://github.com/OtnipG/eCommerceEventsCosmetics/assets/23643357/ed8725a7-f370-42ee-b093-070e3e06ae7f)

## How to read
User user_id during session user_session added to shopping cart (property event_type is equal cart) product product_id of brand brand of category category_code (category_code) with price price at event_time

## Columns Description:
event_time	Time when event happened at (in UTC).
event_type	Only one kind of event: purchase.
product_id	ID of a product
category_id	Product's category ID
category_code	Product's category taxonomy (code name) if it was possible to make it. Usually present for meaningful categories and skipped for different kinds of accessories.
brand	Downcased string of brand name. Can be missed.
price	Float price of a product. Present.
user_id	Permanent user ID.
** user_session**	Temporary user's session ID. Same for each user's session. Is changed every time user come back to online store from a long pause.

## Event Types
view - a user viewed a product
cart - a user added a product to shopping cart
remove_from_cart - a user removed a product from shopping cart
purchase - a user purchased a product

# Kaggle References (~.5h)
https://www.kaggle.com/code/khairizalalfath/data-preparation-and-stuffs
https://www.kaggle.com/code/chenjiawei0618/customer-data-analysis
https://www.kaggle.com/code/ahmedmussaa/cosmetics-shop-s-analysis-interactive-graphs
https://www.kaggle.com/code/danielxing/product-metrics-evaluation-and-consumer-clustering
https://www.kaggle.com/code/lakidataguy/data-viz-funnel-heatmap-countour-plots-and-eda
https://www.kaggle.com/code/lesleyding/ecommerce-users-behavior-analysis
https://www.kaggle.com/code/annettecatherinepaul/ecommerce-analysis-and-recommendations
https://www.kaggle.com/code/yihsiangyen/rfm-analysis-practice
https://www.kaggle.com/code/jianlizhou/customer-segmentation-by-rfm-model-and-k-means


https://www.kaggle.com/code/jibion/sequence-sunburst-from-ecommerce-cosmetics
https://www.kaggle.com/code/wayasam/eda-fpmc-small
https://www.kaggle.com/code/alonhod/brand-category-measures-and-correlation-matrix
https://www.kaggle.com/code/danofer/ecommerce-cosmetic-predict-purchases-data-prep
https://www.kaggle.com/code/coronatianmao/discovering-business-value-from-ecommerce-data
https://www.kaggle.com/code/luthien5921/ecommerce-neural-net-for-recommendation-system

# Academic Reference


# Professional Reference

---
# Lessons learned
