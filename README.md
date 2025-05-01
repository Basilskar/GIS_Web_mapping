# GIS Web Application

An interactive web-based Geographic Information System built with OpenLayers and GeoServer.

![GIS Web App](https://img.shields.io/badge/GIS-Web%20App-green) ![OpenLayers](https://img.shields.io/badge/OpenLayers-6.0%2B-blue) ![GeoServer](https://img.shields.io/badge/GeoServer-2.0%2B-orange)

## Overview

This application provides a user-friendly interface for visualizing, querying, and analyzing spatial data through your web browser. It connects to a GeoServer backend and offers a comprehensive set of GIS tools.

## Features

- 🌍 Multiple base maps (Satellite, OSM)
- 📊 WMS layer management
- 🔍 Attribute and spatial queries
- 📏 Measurement tools
- 📋 Feature identification
- 🎨 Legend display
- 📊 Tabular data export

## Prerequisites

- GeoServer (default: http://localhost:8084/geoserver)
- Web server
- Modern web browser

## Installation

```bash
# Clone the repository
git clone https://github.com/Basilskar/GIS_Web_mapping.git

# Navigate to the project directory
cd GIS_Web_mapping

# Deploy to your web server
# (or simply open index.html in a browser for local testing)
```

## Configuration

Configure GeoServer with your spatial data sources before running the application.



## Usage Guide

### Basic Navigation
- Pan: Click and drag
- Zoom: Scroll wheel or zoom controls

### Adding Layers
1. Click "☰ WMS Layers"
2. Select a layer
3. Click "Add Layer"

### Querying Data
1. Click "☰ Open Query Panel"
2. Select parameters
3. Click "Execute Query"

## Documentation

For more detailed information on features, customization options, and troubleshooting, see the [full documentation](docs/README.md).

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
