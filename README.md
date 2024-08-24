# Photo-Album

This app allows users to add and display images stored in the browser's local storage. It fetches images from local storage upon mounting and displays them on the screen, ensuring that any previously saved images are shown when the app loads.

## Features

- **Input and Button Interface**: The app provides an input field for users to enter the URL of an image and a button labeled "Add Button" to submit the image.
- **Image Storage**: When a valid image URL is submitted, the image is saved to local storage using the `setItem()` method and immediately displayed on the screen.
- **Lifecycle Integration**: The app utilizes an appropriate lifecycle method to fetch and display images from local storage when the component mounts, ensuring that stored images persist across sessions.
