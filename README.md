# Full-Stack Developer Capstone: Best Cars Dealership

**Project name:** Best Cars Dealership – Dealership Review Web Application

A national car retailer's web application that lists dealership branches across the U.S. and lets customers view and post reviews of each dealer. Reviews are run through a sentiment analyzer so each one is tagged as positive, neutral or negative.

## Features
- Static **About Us** and **Contact Us** pages
- User **registration, login and logout** (Django + React)
- List all dealers and **filter dealers by state**
- View **dealer details** with reviews and sentiment icons
- **Post a review** for a dealer (logged-in users)
- Django admin for **Car Makes** and **Car Models**

## Architecture
| Component | Technology |
|---|---|
| Frontend | React, HTML, CSS, Bootstrap |
| Main web app | Django (Python), SQLite |
| Dealers & reviews API | Node.js / Express + MongoDB (Docker) |
| Sentiment analyzer | Flask + NLTK VADER on IBM Cloud Code Engine |
| CI/CD | GitHub Actions (flake8 + JSHint linting) |
| Deployment | Docker, Kubernetes |

## Author
Muhammad Asad
