# Mobile HCI Project: Gesture-Based Menu Navigation

## Project Description

This project is a gesture-based menu navigation system for mobile devices. It leverages the TensorFlow.js Handpose model to detect hand gestures through the device camera. Users can navigate through different menu items by performing gestures such as thumbs up. The project also utilizes device orientation to switch between menu items.

## Features

- Gesture detection using TensorFlow.js Handpose model.
- Real-time video feed from the device camera.
- Device orientation-based menu navigation.
- Visual feedback and interaction for selected menu items.

## Files

- `index.html`: The main HTML file containing the structure of the menu and video elements.
- `style.css`: The CSS file for styling the menu items and other elements.
- `glitchURL.html`: Glitch URL reference for the project.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd <repository-folder>

2. **Open the project folder:**
   - Make sure all files (index.html, style.css,
    and glitchURL.html) are in the same directory.
3. **Open 'index.html' in a web browser::**
   - Simply double-click the index.html file or use a
    local server to view the project in a browser.

## Usage

### Start the camera:
- Click the "Start Camera" button to allow the application to access the device camera.
- Grant necessary permissions for the camera and device orientation.

### Gesture Navigation:
- Perform a thumbs up gesture to navigate to the selected menu item.
- The selected menu item will be highlighted with a different border color and size.

### Orientation Navigation:
- Tilt the device to switch between different menu items based on the device orientation.
- The orientation change will be debounced to avoid frequent updates.

## External Libraries
- [TensorFlow.js](https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@latest)
- [Handpose Model](https://cdn.jsdelivr.net/npm/@tensorflow-models/handpose@latest)

## Acknowledgements
This project was developed as part of a Mobile Human-Computer Interaction (HCI) course. Special thanks to the instructors and peers for their support and feedback.


