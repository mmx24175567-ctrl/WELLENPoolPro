WELLEN_Pools Pro+ v7 - UPDATED (spotlights added)
Files:
- main.py (Kivy app) - updated to include spotlights (colored & white)
- assets/marble/*.jpg (thumbnails)
- GOOGLE_MAPS_API_KEY.txt (paste your Google Maps API key here)
- README.txt (this file)
How to run (desktop):
  pip install kivy requests
  python main.py
Notes:
  - Colored spotlight unit price default: 3500 EGP
  - White spotlight unit price default: 2900 EGP
  - Marble calculated per linear meter (length); width 40cm is descriptive only
  - Overflow doubles marble cost (inside + outside)
  - Distance surcharge = (distance_km / 100) * 5%
