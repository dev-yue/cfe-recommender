# Recommender

Build a recommendation engine using Django &amp; a Machine Learning technique called Collaborative Filtering.

# Django -> ML Pipeline
    - Get Data - via Django
        - [x] User
        - [] Ratings -> Collaborative Filtering
        - [X] Dataset -> Movies
            - Scrape from the Internet
            - API -> Software-to-software
            - User-generated content -> cold start problem
            - [x] Open Source Datasets -> Kaggle -> The Movies Dataset
    - Prepare Data - via Django & Panda
    - Train Model from Data - via Django & Celery using Keras
    - Use Model on New Data - via Django & Celery using Keras

## Helpful Guides
- [Using a Cloud-based Redis Server](https://www.codingforentrepreneurs.com/blog/remote-redis-servers-for-development/)
- [Install Redis on Windows](https://www.codingforentrepreneurs.com/blog/redis-on-windows/)
- [Install Redis on macOS](https://www.codingforentrepreneurs.com/blog/install-redis-mac-and-linux)
- [Celery + Redis + Django Setup Guide](https://www.codingforentrepreneurs.com/blog/celery-redis-django/)