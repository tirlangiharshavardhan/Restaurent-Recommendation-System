# Restaurant Recommendation System Readme

## Introduction
Welcome to the Restaurant Recommendation System! This system is designed to recommend restaurants based on user preferences for cuisines and geographical location. The system utilizes cosine similarity to match user preferences with available restaurants and recommends the nearest restaurant based on the given geographical coordinates.

## Features
- **Cuisine-based Recommendation**: Users can input their preferred cuisines, and the system will recommend restaurants that offer those cuisines.
- **Geographical Location-based Recommendation**: Users can provide their current geographical coordinates (latitude and longitude), and the system will recommend the nearest restaurants based on these coordinates.
- **Cosine Similarity**: The system uses cosine similarity to match user preferences with restaurant attributes to provide accurate recommendations.

## Usage
1. **Input User Preferences**:
    - Specify your preferred cuisines (e.g., Italian, Chinese, Mexican).
    - Provide your current geographical coordinates (latitude and longitude).

2. **Get Recommendations**:
    - Receive restaurant recommendations based on your specified preferences.
    - The system will provide a list of recommended restaurants sorted by cosine similarity score.

3. **Select Nearest Restaurant**:
    - If geographical coordinates are provided, the system will also recommend the nearest restaurant based on the given location.

## Requirements
- Python 3.x
- NumPy
- Google Earth
- Scikit-learn

