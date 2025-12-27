# Open-Source iOS Apps

## Overview
A web-based viewer for the Open-Source iOS Apps curated list. This project displays a searchable, filterable catalog of 899+ open-source iOS, watchOS, and tvOS applications.

## Project Structure
- `index.html` - Main web interface with search and filtering
- `server.py` - Simple Python HTTP server
- `contents.json` - Source data containing all app information
- `README.md` - Original project documentation

## Running the Project
The server runs on port 5000 using Python's built-in HTTP server:
```bash
python server.py
```

## Features
- Browse 899+ open-source iOS apps
- Search by name or description
- Filter by category (Apple Watch, Games, etc.)
- Filter by programming language (Swift, Objective-C)
- Apps sorted by GitHub stars
- Direct links to GitHub repos and App Store listings

## Recent Changes
- December 27, 2025: Created web viewer interface for the curated list data
