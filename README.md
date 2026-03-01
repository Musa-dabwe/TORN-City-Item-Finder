# Torn City Item Finder

This userscript is a rebuilt and enhanced version of the original "City Finds" script for Torn RPG. It helps players identify and value items hidden on the city map.

## Features

- **Item Highlighting**: Automatically detects and highlights items on the city map with a pulsing green circle.
- **Filtering**: Includes a category filter bar to toggle the visibility of specific item types (e.g., Melee, Medical, Drugs, etc.).
- **Item Count**: A real-time counter in the city header showing how many items are currently found on the map.
- **Value Calculation**: Click the item counter to see the total market value of all found items.
- **API Integration**: Securely uses the Torn API (Public access) to fetch up-to-date market values.
- **Desktop Compatible**: Optimized to work reliably on desktop browsers.

## How to Use

1. Install the script using a userscript manager like Tampermonkey.
2. Navigate to the City Map in Torn.
3. If items are found, the green counter will appear in the header.
4. Click the counter to view the total value. On your first click, you will be prompted to enter a Public Torn API key.
5. Use the filter bar above the map to show or hide specific item categories.

## Credits

Rebuilt and enhanced by Zedtrooper [3028329].
**Original Author:** tos

## Safety Note

When prompted for an API key, please use a **Public access** key (16 characters). This script only requires public access to fetch item market values. Do not use Full or Custom access keys.
