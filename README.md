# Deception-Detection

## Overview
The Deception Detect Extension is a tool designed to help users identify potential deceptive content on websites by scanning for the presence of known deceptive words. The extension analyzes webpage content for a comprehensive list of deceptive words associated with dark patterns and misleading practices.

## Installation
To use the extension, follow these steps:

- Download or clone this repository.
- Open **Google Chrome**.
- Navigate to **chrome://extensions/**.
- Enable "**Developer mode**" in the top-right corner.
- Click on "**Load unpacked**" and select the folder named **Deception Dectection**.
## Usage
Once the extension is installed, click on the extension icon in the Chrome toolbar. The extension popup will appear, providing information on the presence of deceptive words on the current webpage.
Note: If the extension is not loaded refresh the webpage and try again.

## Files

* **manifest.json**: Configuration file that defines the extension's metadata and permissions.

* **matches.js**: Handles the background communication between the extension and the webpage.

* **popup.js**: Manages the extension popup, initiating communication with the webpage and displaying the results.

* **popup.html**: HTML file defining the structure of the extension's popup.

## Contributing
If you'd like to contribute to the project, feel free to fork the repository, make your changes, and submit a pull request.



