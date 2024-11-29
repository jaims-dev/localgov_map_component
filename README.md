# Localgov Map Component

This module adds configuration for 2 paragraphs types, Map and Map location, that can then be used to add new fields to content types for displaying markers in a map, with the help of Geofields and Leaflets.

A typical usecase is: site editors want to add a map to a node, with one or several markers on it, in a quick and easy fashion just by dropping pins and adding labels with little effort or setup; rather than having to add addresses and what not to fields in forms.

## Requirements

This module requires the following modules:

- [Geofield](https://www.drupal.org/project/geofield)
- [Geofield Map](https://www.drupal.org/project/geofield_map)
- [Leaflet](https://www.drupal.org/project/leaflet)
- [Paragraphs](https://www.drupal.org/project/paragraphs)

## Installation

Install as you would normally install a contributed Drupal module. For further information, see [Installing Drupal Modules](https://www.drupal.org/docs/extending-drupal/installing-drupal-modules).

## Configuration

1. Enable the module at Administration > Extend.
2. Enable the paragraphs type: 'Map' to any content type you want to use for displaying markers in a map
