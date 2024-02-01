
Flight Tracking Application with Python
Overview
This repository contains a Python application for real-time flight tracking using open air traffic data from OpenSky Network. The application fetches live air traffic data through the OpenSky Network REST API, processes the data, and plots the aircraft positions on a map. The map is displayed in a web browser, providing a user-friendly interface for tracking flights.

Features
Live Air Traffic Data: The application retrieves real-time air traffic data, including information such as aircraft callsign, origin country, velocity, altitude, and more.

Interactive Map: The plotted aircraft positions are displayed on an interactive map, allowing users to explore and track flights visually.

Hover Information: Users can hover over aircraft icons to view additional information, including callsign, origin country, velocity, and altitude.

Automatic Updates: The application automatically updates the displayed data at regular intervals, providing a near real-time tracking experience.

Prerequisites
Before running the application, make sure you have the following dependencies installed:

Python 3.x
Bokeh
Requests
Pandas
NumPy
