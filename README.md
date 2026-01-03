# climate-action-plan-search
A lightweight, client-side search and filter tool that pulls Climate Action Plan data from Google Sheets and displays searchable results on a Squarespace website.

# Climate Action Plan Search Tool

This project provides a searchable and filterable interface for Climate Action Plans using data stored in Google Sheets.

The tool allows users to:
- Search plans using multiple keywords
- Filter by location, ecosystem, topic, and country
- Open linked Climate Action Plan PDFs
- Automatically update when the Google Sheet is modified

## How It Works
- Data is stored in a public Google Sheet
- The sheet is published as a CSV
- JavaScript loads and parses the CSV using PapaParse
- Results are rendered dynamically on the page

## Deployment
This tool is designed to be embedded into a Squarespace site using a Code Block.

### Steps:
1. Publish the Google Sheet to the web as a CSV
2. Copy the Google Sheets CSV URL
3. Paste the contents of `search.html` into a Squarespace Code Block
4. Save and publish the site

## Updating Data
No website changes are required to update the data.
Simply edit the Google Sheet and ensure the column headers remain unchanged.

## Technologies Used
- HTML
- CSS
- JavaScript
- PapaParse
- Google Sheets
- Squarespace
