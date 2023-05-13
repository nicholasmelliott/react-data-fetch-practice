# GifSearch

A React application that allows you to search for gifs using the Giphy API.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Key](#api-key)
- [License](#license)

## Installation

To run the application on your local machine, you need to have [Node.js](https://nodejs.org/en/) installed. Once you have Node.js installed, follow these steps:

1. Clone this repository or download the zip file.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install all the required dependencies.
4. Run `npm start` to start the application.
5. Open your browser and navigate to `http://localhost:3000/`.

## Usage

Once the application is up and running, you can search for gifs by typing in a search term in the search bar and clicking on the "Search" button. The application will fetch the first 24 results from the Giphy API and display them on the page. You can also press the "Enter" key to submit the search.

If you don't specify a search term, the application will search for gifs related to the word "reaction" by default.

## API Key

This application uses the public beta key of the Giphy API, which has a limit of 42 requests per hour. If you would like to use this application extensively or make your own modifications, you will need to get your own API key by signing up at [https://developers.giphy.com/dashboard/](https://developers.giphy.com/dashboard/). Once you have an API key, replace the `api_key` parameter in the `axios.get` call with your own API key.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
