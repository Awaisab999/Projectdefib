# Defibrillator Finder

The Defibrillator Finder is a Python program that helps users find the closest defibrillator based on their location and search radius. It provides a user-friendly graphical interface for easy interaction.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)

## Features

- Find the closest defibrillator based on user-provided location information.
- Optionally set a search radius to narrow down the results.
- Display an interactive map with user's location and nearby defibrillators.
- Utilizes geographical data and haversine distance calculation.

## Requirements

To run the Defibrillator Finder program, you need:

- Python 3.x
- Required Python libraries: pandas, tkinter, folium, geopy
##Installation
Install the required Python libraries using pip:
pip install pandas tkinter folium geopy
Usage
Navigate to the program directory in your terminal:
cd defibrillator-finder
Run the program using the following command:
python defibrillator_finder.py
The program will open a graphical user interface (GUI) where you can enter your location details and set a search radius.

Click the "Display The Closest Defibrillator" button to find the closest defibrillator to your location without a search radius.

Click the "Display The Closest Defibrillator with Radius" button to find defibrillators within the specified search radius.

The program will generate an interactive map in the file map.html, displaying defibrillator locations.
