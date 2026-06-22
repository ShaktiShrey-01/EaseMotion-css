# Fix Header Content Overflow

## Overview
Resolves an issue where the "Live Demo" button and rightmost navigation items get cut off on constrained viewports due to improper overflow handling.

## Changes
- Replaced `flex-wrap: wrap` with `flex-wrap: nowrap` in `docs.css`.
- Added `overflow-x: auto` to allow graceful horizontal scrolling of the navigation links.
- Hidden the scrollbar natively to maintain the clean aesthetic.