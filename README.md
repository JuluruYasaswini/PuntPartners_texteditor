Features
Font Family Selection: Choose from a list of available font families.
Font Variant Selection: Adjust the font weight and style (italic/regular) using the dropdown menu.
Italic Toggle: Toggle italic styling on and off.
Save Settings: Automatically saves the current font settings and text content to localStorage.
Reset Settings: Resets font settings to default and clears the text content.
Export Content: Save the current text content to a .txt file.
Files
index.html: The main HTML file that structures the editor layout.
texteditor.css: Contains the styling for the editor and controls.
texteditor.js: Handles the functionality for fetching fonts, updating styles, saving settings, and exporting content.
fontstyle.json: A JSON file containing font styles and variants. (Note: This file needs to be created with the appropriate font data.)
Usage
Loading Fonts: Ensure you have a fontstyle.json file with the required font data.
HTML Structure: The editor consists of dropdowns for font family and variant, a toggle for italic, a text area for editing, and buttons for resetting and saving content.
Initialization: On page load, the editor initializes by fetching fonts and applying any saved settings from localStorage.
Customization: Select different font families and variants, toggle italic style, and see changes applied in real-time.
Saving and Resetting: Use the Save button to export content to a .txt file and the Reset button to revert to default settings.
