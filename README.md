# Crowd-Sourced Phenomena Testing App

## Overview
This Android application enables crowd-sourced testing across multiple domains such as environmental observations and user interaction experiments. It supports various types of data collection methodologies through an intuitive mobile interface.

## Technology Stack
- **Platform**: Android
- **Programming Language**: Java
- **Database**: Firestore
- **Version Control**: GitHub

## Features
- **User Profiles**: Manage user profiles with capabilities to edit and retrieve contact information.
- **Experiment Management**: Users can publish, unpublish, and end experiments, defining specific rules and constraints for each.
- **Data Visualization**: Display statistical analysis of the trials including histograms and time series plots.
- **Geolocation Integration**: Mandatory geolocation for certain trials, enhancing the accuracy of the experimental data.
- **QR and Barcode Scanning**: Simplify the process of recording trial results by scanning QR codes and barcodes.

## Getting Started
To set up the project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/Beikewzh/PreemptiveOOP.git

# Reference

Code for LocationPicker and TrialLocationsDisp are derived from this tutorial:<br />
https://developers.google.com/codelabs/maps-platform/location-places-android#0<br /><br />

Code for QR-Code and Barcode scanning uses the ZXing library. Link to its repo:<br />
https://github.com/zxing/zxing<br /><br />

Code for the histogram in DisplayExpHistogram.java uses the MPAndroidChart library. Link to its repo:<br />
https://github.com/PhilJay/MPAndroidChart<br /><br />

Code for the time-plot in DisplayExpTimePlot.java uses the GraphView library. Link to its repo:<br />
https://github.com/jjoe64/GraphView<br /><br />
