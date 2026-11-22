# Hands-on — Programming Image Filters with Python PIL

The lesson with your hands and your feet, not only your eyes.

## Rules on paper first
Take the nine-pixel grid from Do it first. Apply the negative rule (subtract each number from 255) to all nine pixels by hand. Then apply the threshold rule with a limit of 120: average above 120 becomes white (255, 255, 255), below becomes black. Which rule kept more of the picture's information? Say why.

## Real filter, real photo
With Python and Pillow: open a photo, print its size and mode, then write the greyscale program — two loops, average, write back — and save the result as a new file. Open both images side by side. Then change one line to make the negative filter instead, and run it again on the original.
