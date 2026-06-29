# Wayland Touch Calibrator

A minimal Wayland Touch Calibrator for use on kiosk systems where a browser
runns fullscreen.

1. Open https://christianmayer.github.io/WaylandTouchCalibrator/test.html 
   on the kiosk system
2. Open https://christianmayer.github.io/WaylandTouchCalibrator/index.html 
   on a different, second system
3. Click on the kiosk system (at least) on the four crosses in the edges
   (T1, T3, T7, T9) and insert the coordinates on the second system
4. Optional: you might add more test points to increase the quality of 
   the calibration calculation
5. Copy the calculated calibration string to the Wayland configuration
6. Restart and test; when necessary refine and/or repeat