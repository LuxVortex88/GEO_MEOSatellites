# GEO_MEOSatellites

# Orbital Position Simulation – GEO & MEO Satellites

This project demonstrates how to calculate and visualize the position of **Geostationary (GEO)** and **Medium Earth Orbit (MEO)** satellites using Python, `numpy`, and `astropy`.

## Features
- Define Keplerian orbital elements for GEO & MEO satellites.
- Convert orbital elements to GCRS (Geocentric Celestial Reference System) coordinates.
- Generate satellite position vectors for a defined time period.
- Prepare time-stepped data for animation (6-hour simulation with 200 steps).

## Code Highlights
- Rotation matrix conversion from perifocal to GCRS.
- Position vector representation using `astropy.coordinates.SkyCoord`.
- Time propagation using `astropy.time.Time`.

## Example Output
```text
GEO Satellite Position (GCRS): (42121.836, 0., 0.) km  
MEO Satellite Position (GCRS): (26533.44, 0., 0.) km  
