# Spaceframe Quotation Maker

A professional quotation generation system for Spaceframe Architecture & Design.

## Features

- Connect to Google Sheets database
- Generate professional PDF quotations
- Bill of Quantities (BOQ) management
- Automatic GST calculations
- Modern, professional UI

## Usage

1. Open `quotation-maker.html` in a web browser
2. Enter your Google Sheet ID (default is pre-configured)
3. Click "Connect to Database"
4. Fill in quotation details and add items
5. Generate and download PDF quotation

## Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Google Sheet with proper structure (Items sheet required)
- Google Sheet must be set to "Anyone with the link can view"

## Google Sheet Structure

The system expects a Google Sheet with the following sheets:
- **Items**: Contains product/item data with columns: SNo, Super Category, Category Type, Sub Category, Brand, SKU Name, Description, Unit, Minimum Qty, Rate
- **Company_Details** (optional): Company information
- **Terms_Conditions** (optional): Terms and conditions

## License

Copyright © Spaceframe Architecture & Design
