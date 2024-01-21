# Web eyes
Web eyes is a simple canvas with eyes that follow the face of the person in front of the computer using the webcam.

Note that this requires Experimental Web Platform features to be enabled in chrome
https://developer.chrome.com/blog/browser-flags/


## Description
Web eyes is a simple one file project featuring a canvas with animated eyes that track the movements of a person's face detected through the computer's webcam.

## How It Works
Web eyes utilizes Experimental Web Platform features to access the computer's webcam and employ face detection algorithms. The animated eyes on the canvas then dynamically follow the detected face by calculating the distance and angle to the detected face.

## Getting Started
To use Web eyes, follow these steps:

1. Enable Experimental Web Platform features in Chrome by navigating to `chrome://flags/` in your browser.
2. Look for "Experimental Web Platform features" and set it to "Enabled."
3. Restart your Chrome browser to apply the changes.

## Usage
Open the index.html in your browser and allow access to your webcam. The animated eyes should now start following your face once it is detected.

## Compatibility
Web eyes is only tested in Google Chrome with Experimental Web Platform features enabled.

## License
This project is licensed under the MIT License.