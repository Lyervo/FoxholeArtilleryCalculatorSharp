# FoxholeArtilleryCalculatorSharp
A Windows Form Application for calculating artillery coords in Foxhole using OCR to input the fields automatically.

The calculation part is using a C# implementation of earthgrazer's JS code, you can view his work here:
https://github.com/earthgrazer/foxhole-artillery-calc

# Instructions

Use the toggle button Aim Mode to start reading for coords

Q Key - Gather coords from enemy position

E Key - Gather coords from friendly position

\ Key - Writes out result distance and azimuth in your chat for you

When both coords are grabbed it will automatically start calculating the coords for you

# Note
Currently the application grabs the required data by using Optical character recognition technology from Tesseract

This means that obtaining the coords can be interupted by these factors:

1. Low image resolution

2. Bright backgroup

3. Complex backgroup

4. Other text overlapping with the UI

Slightly moving ur mouse to other nearby position and repeatly grabbing the data should yield the results.
