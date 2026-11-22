# Hands-on — NMEA Frames — How GPS Devices Report Position

The lesson with your hands and your feet, not only your eyes.

## Decode by hand
Decode this frame completely: `$GPGGA,091530,4358.250,N,00728.500,E,1,10,1.0,120.0,M,,,,*hh` — time, latitude and longitude in decimal degrees, fix quality, satellites, altitude. (The checksum is written "hh" here; on a real frame it is two hexadecimal digits.)

## Decode by program (if Python is available)
Write the decoder: split a $GPGGA line on commas, extract the fields, convert the coordinates. Test it on the frame from Do it first and check it against your hand conversion (48.1173° N, 11.5167° E). If folium is available, plot the point; if several frames are provided, plot the track.
