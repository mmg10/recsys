# Real-time Recommendation System with Deep Learning

A scalable, microservices-based recommendation system that uses deep learning to provide personalized recommendations and adapts in real-time to user interactions.


## Installation



Build and start the services:
```bash
docker-compose up --build
```

## Usage

### Getting Recommendations

You can get recommendations using either cURL or Python:

#### Using cURL:
```bash
curl -X POST http://localhost:8000/recommend/ \
-H "Content-Type: application/json" \
-d '{"user_id": 1, "movie_ids": [1, 2, 3, 4, 5]}'
```

#### Using Python:
```bash
python test_recommendation.py
```
