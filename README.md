# NonPlanarInfill
A postprocessing script that allows non-planar infill in prusaslicer

This script deforms your infill in a sine wave on the Z axis. 

Use it like this (while choosing your own values):
```"C:\Path\To\Python\python.exe" "C:\Path\To\Script\nonPlanarInfill.py" -frequency 1.5 -amplitude -0.2```

Don't use Gyorid or Archimedean Chords as infill, it works but it will process A WHIIIILE. All other infill patterns are fine.

Here is the video about this repo: 


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/CkxIca0W6Ss/0.jpg)](https://www.youtube.com/watch?v=CkxIca0W6Ss)
