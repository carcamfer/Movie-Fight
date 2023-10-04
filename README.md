# Movie Fight

## Overview

Movie Fight is an application where users can compare two movies and see which one is the best based on certain criteria. The application provides an interactive user interface to search for and select movies to compare.


## Technologies Used 

- HTML5
- CSS3
- JavaScript
- Axios
- Bulma CSS Framework
- Font Awesome

## File Structure

### Root Directory

#### 1. `index.html`

Provides the HTML structure of the application, embedding the scripts and linking the CSS files for styling and functionality.

#### 2. `style.css`

Contains the CSS rules to style the application ensuring a user-friendly interface and experience.

#### 3. `autocomplete.js`

Includes the JavaScript function `createAutoComplete` responsible for handling the autocomplete functionality of the movie search.

#### 4. `utils.js`

Defines utility functions like `debounce` which optimizes certain operations (like API requests) by introducing a delay for better performance and reduced resource usage.

### Test Folder

#### 1. `autocomplete.test.js`

Contains unit tests for the application, particularly focusing on the functionality of the autocomplete feature. It tests scenarios like:
- Ensuring the dropdown starts closed.
- Confirming that the dropdown opens up after a search.

#### 2. `test.html`

HTML file to visualize the running tests, incorporating the Mocha testing library and Chai assertion library to facilitate testing operations.

## How to Use

1. **Search for Movies**: Use the search bar to type the name of the movie you wish to compare.
2. **Select Movies**: From the dropdown, select the desired movie.
3. **Get Results**: The app compares selected movies and indicates which one is the best based on certain parameters.

## Running Tests

Navigate to `test/test.html` in your browser to run the tests and see the test results.

## Contributing 

Your contributions are always welcome! Please create a pull request with your changes.


