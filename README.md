# Motors.co.uk Frontend Technical Test

## Background
The local zoo has a new consignment of animals. They would like an app to allow their keepers to view the animals, mark their favourites and sort them by such key criteria as number of limbs and furriness.

## Technical considerations
We would like you to build the app using React, ensuring best practices are followed and the code is clean and modular. The app needs to be functional across a range of devices.

We have included Redux for state management. To get you started there is a button that triggers an example action to update the store and log the result to the console. Please feel free to remove these.

If you are aren't sure about how to complete one of the tasks then please write some pseudo code to explain how you would approach it.

## Setup
1. Make sure you have Node installed (>= 8.9.2)
2. Clone the repository
3. Run `npm install`
4. To start the app run `npm start`. This will run webpack-dev-server and webpack --watch and the project will be available at http://localhost:8080/ (hot reloading is enabled)
5. Open index.html in your browser

## Tasks

### Please complete the following tasks

* Add some markup for an introductory section. Use the text from animals.txt
* Render a list of animals using React - We have started this in `AnimalList.jsx`
* Add the following functionality to the React app to allow the user to:

    * Remove an animal from the list
    * Indicate which animals are their favourites - Show a list of favourites in `Favourites.jsx`
    * Add some filtering and / or sorting for different properties

* Style your components

Thank you for taking the test!