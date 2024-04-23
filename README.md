# Google Maps API and Yelp Data Integration

![Google Maps API](https://developers.google.com/maps/images/maps-icon.svg) ![Yelp](https://s3-media0.fl.yelpcdn.com/assets/srv0/developer_pages/952bc5853d69/assets/img/brand_guidelines/yelp_fullcolor_outline.png)

## Overview

This project involves integrating data from the Google Maps API and Yelp to provide users with location-based information such as nearby restaurants, cafes, and other businesses. By leveraging the powerful features of both APIs, users can discover popular venues, read reviews, and obtain directions seamlessly.

## Features

- **Search Nearby Places**: Utilize the Google Maps Places API to search for nearby places based on specified criteria such as type (e.g., restaurants, cafes) and location.
- **Get Business Information**: Fetch detailed information about businesses, including name, address, phone number, ratings, reviews, and photos, using the Yelp Fusion API.
- **Display on Map**: Display search results and business locations on an interactive map powered by the Google Maps JavaScript API.
- **Get Directions**: Allow users to get directions to selected businesses using the Google Maps Directions API.
- **Filter and Sort Results**: Implement filtering and sorting options to refine search results based on user preferences.

## Setup

To run this project locally, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using `git clone`.
2. **Install Dependencies**: Install the necessary dependencies by running `npm install` or `yarn install`.
3. **Set up API Keys**:
    - Obtain API keys for both Google Maps API and Yelp Fusion API.
    - Create a `.env` file in the root directory of the project.
    - Add your API keys to the `.env` file in the following format:
      ```
      REACT_APP_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
      REACT_APP_YELP_API_KEY=your_yelp_api_key
      ```
4. **Start the Development Server**: Run `npm start` or `yarn start` to start the development server.
5. **Access the Application**: Open your web browser and navigate to `http://localhost:3000` to access the application.

## Usage

1. **Search for Places**: Enter a location and select the type of places you want to search for (e.g., restaurants, cafes).
2. **View Results**: Explore the search results displayed on the map and in the list view.
3. **Get Business Details**: Click on a marker on the map or a business in the list to view detailed information, including ratings, reviews, and photos.
4. **Get Directions**: Click on the "Directions" button to get step-by-step directions to the selected business.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:
- Fork the repository
- Create a new branch (`git checkout -b feature/your-feature`)
- Commit your changes (`git commit -am 'Add some feature'`)
- Push to the branch (`git push origin feature/your-feature`)
- Create a new Pull Request
