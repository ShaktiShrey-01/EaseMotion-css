# Fix Header Links Wrapping

## Overview
Resolves a visual issue where top navigation links containing multiple words wrap onto multiple lines, breaking the header's layout and alignment.

## Changes
- Added `white-space: nowrap` to header anchor tags and buttons within `.docs-header-links` in `docs.css`.