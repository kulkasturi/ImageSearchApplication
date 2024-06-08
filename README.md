

# ImgSrc - Image Search Application

ImgSrc is a simple web application that allows users to search for images using the Unsplash API. Users can enter a search term and view a variety of images related to that term. They can also load more images by clicking the "Show More" button.

## Features

- Search for images using the Unsplash API.
- Display search results in a responsive grid layout.
- Load more images with the "Show More" button.
- Click on an image to view it on Unsplash.

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

You need a modern web browser to run this application.

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/imgsrc.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd imgsrc
    ```

3. **Open `index.html` in your browser to view the application:**

    ```bash
    open index.html
    ```

### Usage

1. Open the application in your web browser.
2. Enter a search term in the input field and click the "Search" button.
3. Browse the search results.
4. Click "Show More" to load additional images.

## Code Overview

### HTML

- The main structure of the application is in the `index.html` file.
- Contains the form for image search, results display, and the "Show More" button.

### CSS

- Styling for the application is in the `style.css` file.
- Includes responsive design for different screen sizes.

### JavaScript

- The main functionality of the application is in the `script.js` file.
- Uses the Unsplash API to fetch images based on the user's search query.
- Dynamically updates the DOM to display search results.

### Unsplash API

- This project uses the Unsplash API to fetch images. You need an Unsplash Access Key to use the API.
- Replace `const accessKey = "YOUR_ACCESS_KEY"` with your actual Unsplash Access Key in the `script.js` file.

## Project Structure

