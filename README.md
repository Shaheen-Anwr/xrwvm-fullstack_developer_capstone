# xrwvm-fullstack_developer_capstone

## Project name: Best Cars Dealership – Full-Stack Developer Capstone

Best Cars is a national car retailer in the U.S. with dealership branches across the country. This web application lets visitors browse the dealership branches, filter them by state, read reviews for each dealer, and — after signing in — post their own reviews of a dealership.

## Features

- Browse all dealerships and filter them by state
- View a dealer's details and its customer reviews, each tagged with a sentiment (positive, neutral or negative)
- Register, log in and log out
- Logged-in users can post a review for a dealership, choosing the car make, model and year
- Django admin site for managing car makes and car models
- About Us and Contact Us pages

## Architecture and technologies

| Part | Technology |
|---|---|
| Frontend | React (dealers, dealer details, post review, login, register pages), HTML/Bootstrap (home, about, contact) |
| Main web app | Django, with SQLite for users, car makes and car models |
| Dealers and reviews service | Node.js / Express with MongoDB, run with Docker Compose |
| Sentiment analyzer | Flask + NLTK VADER, deployed on IBM Cloud Code Engine |
| CI/CD | GitHub Actions (flake8 for Python, JSHint for JavaScript) |
| Deployment | Docker image on IBM Cloud Container Registry, deployed to Kubernetes |
