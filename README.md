# Real_Time_Bus_Tracker
This web application is designed to display real-time bus locations on a map using the Google Maps API and data from the Massachusetts Bay Transportation Authority (MBTA). It provides a visual representation of bus movements on a map and updates the bus markers every 15 seconds.
Prerequisites

Before using this application, you need the following prerequisites:

    Google Maps API Key (Replace 'YOUR_API_KEY' in the code with your actual API key.)
    Internet connection to fetch MBTA bus data.

Installation

    Clone or download this repository to your local machine.
    Open the index.html file in a web browser.

Usage

    When you open the web page, it will load a Google Map with bus markers on it.
    The markers represent the real-time locations of buses.
    Buses are updated on the map every 15 seconds.

Code Explanation

    The Google Maps API is loaded using a script tag in the HTML file.
    The JavaScript code in the <script> section initializes the map and markers.
    It fetches bus location data from the MBTA API and updates the map with the latest data.
    Bus markers are color-coded based on their direction.
    The application continuously updates the bus locations every 15 seconds.

Configuration

To use your own Google Maps API key, replace the placeholder 'YOUR_API_KEY' in the script tag with your actual API key.

Notes

    The provided code contains an api key that is not for public use, you need to replace it with your own key.
    The MBTA API endpoint used in the code will need you're own API key available at api-v3.mbta.com

Licensing
    Part of this code is from the MIT xPro classes. All use of this code will be in compliance with their license. 
