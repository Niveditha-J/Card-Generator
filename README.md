# Card Generator with Dynamic Features
A Python-based project to create personalized greeting cards with dynamic customization options, including text, background color or image, border customization, and audio playback of messages.

## Features
1. Personalized Text
Add the recipient's name and a custom message to the card.
Supports dynamic font resizing and alignment for optimal readability.
2. Background Customization
Choose a solid background color (e.g., yellow, #FF5733) or use an image as the background.
Scales background images to fit the card dimensions seamlessly.
3. Customizable Borders
Adjust the card's border color and width to enhance its design.
4. Dynamic Font Options
Select from various font styles to match the tone of the card.
Automatically adjusts text placement and font size based on content length.
5. Text-to-Speech (TTS) Integration
Generates an audio file of the card message using the gTTS library.
Recipients can listen to the message by playing the audio.
6. High-Quality Output
Saves the card in PNG format, ready for sharing or printing.

## Installation
## Prerequisites
Ensure you have Python 3.7 or higher installed on your system.

## Dependencies
Install the required Python libraries:

pip install pillow gtts

python card_generator.py

## Follow the Prompts:

Enter the recipient’s name, message, background options, and border preferences.
Optionally, choose a background image.
## Output:

A personalized greeting card is saved as a PNG file (e.g., card.png).

An audio file (e.g., card_message.mp3) is created for the card message.

Result: Share the card digitally or print it for physical use.

## Example
Input:
Recipient Name: Nivedha

Message: "Happy Birthday Dear! Love you, Stay blessed!"

Background Color: yellow

Border Color: black

Border Width: 10 pixels
## Output:
A beautiful birthday card with the entered details.

An audio file named card_message.mp3 with the message.
