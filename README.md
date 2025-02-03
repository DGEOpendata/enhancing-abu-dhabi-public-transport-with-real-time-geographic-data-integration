# Abu Dhabi Transport Map Integration

## Overview
This project demonstrates how to integrate Abu Dhabi's public transport data with a dark gray base map to create an interactive map application. The map includes transport routes and stops, offering users a comprehensive view of the public transport network.

## Requirements
- Python 3.x
- `requests` library to fetch data from APIs
- `folium` library to create interactive maps

## Installation
1. Install Python from [python.org](https://www.python.org/).
2. Install the necessary libraries using pip:
   bash
   pip install requests folium
   

## Running the Example
1. Ensure you have access to the transport and base map dataset APIs. Replace `http://example.com/abu-dhabi-transport-data.json` and `http://example.com/abu-dhabi-dark-gray-base-map` with actual URLs.
2. Run the script:
   bash
   python abu_dhabi_transport_map.py
   
3. Open the `abu_dhabi_transport_map.html` file in a web browser to view the interactive map.

## Customization
- Update route and stop colors and icons in the code to match your application's theme.
- Modify the initial map center and zoom level as needed.

## Contribution
Feel free to fork the repository and submit pull requests for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.