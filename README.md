# Excel Data Transformer for Elker Import

Web-based tools to transform Excel data into the Elker import template format.

## Tools Included

### 1. data-transformer.html
- Basic transformer with hardcoded mappings
- Quick transformation for known data formats
- Automatic detection of messages, case notes, and files

### 2. data-transformer-mapper.html
- Advanced transformer with visual column mapping interface
- Searchable column dropdowns
- Save/load mapping presets
- Support for multiple source file formats
- Multi-column selection for unstructured data

## Features

- **100% Client-side**: All processing happens in your browser - no data is sent to any server
- **Preset Support**: Save column mappings and reuse them across multiple files
- **Timestamp Parsing**: Automatically parse timestamped content into separate entries
- **Multi-row Generation**: Create multiple rows from single source (Messages, Case Notes, Files)
- **Auto-mapping**: Intelligent column name matching
- **Excel Export**: Generate properly formatted Excel files ready for import

## Usage

1. Open either HTML file in a modern web browser
2. Upload your source Excel file
3. For mapper version:
   - Map source columns to target fields
   - Save mapping as preset for future use
4. Click Transform to generate the output file
5. Download the transformed Excel file

## Target Template Structure

The transformer outputs 7 sheets matching the Elker import template:
- Report List (22 fields)
- Report Responses (15 questions)
- Messages
- Case Notes
- Files
- Status Changes
- Unstructured Data

## Browser Compatibility

Works best with:
- Chrome/Edge (recommended)
- Firefox
- Safari

## Security

- All data processing happens locally in your browser
- No external API calls or data transmission
- Source data never leaves your computer