The code in `radar_data_processing.ipynb` allows users to:

- generate (batches of) plots of RADAR data
- manipulate plots (e.g., crop, filter, zoom)
- generate videos from the plots (.mp4 or .avi)
- generate optical flow on the resulting videos using OpenCV's (a) dense Farneback method, (b) sparse Lucas-Kanade method, and (c) dense pyramid Lucas-Kanade optical flow
- make .gifs (from the resulting optical flow images or the RADAR plots themselves)

There are several parameters that may be toggled for the sparse Lucas-Kanade method algorithm, specifically the `goodfeaturestoTrack()` function, including masks, maximum number of edges, and quality of edges.

For examples of optical flow generated using this code see here: (access might be restricted) [https://github.com/waggle-sensor/summer2021/blob/main/Razin/Optical%20Flow%20Report.md](https://github.com/waggle-sensor/summer2021/blob/main/Razin/Optical%20Flow%20Report.md ) 

