# Conky Bright Modern
A set of conkies that are designed to give as much information in as small a space as possible. This was formerly called *dark modern*, but I decided to change it to bright modern. Even if it works for both of those purposes. 

# Preview Images
![Conky Bright Modern][bm]

![Conky Bright Modern Graphs][bmg]
[bm]: https://github.com/bubbadoobop/Conky-Bright-Modern/blob/master/bright_modern/dark_modern.png
[bmg]: https://github.com/bubbadoobop/Conky-Bright-Modern/blob/master/bright_modern/dark_modern-graphs.png


## Changing the options for GPU, CPU, etc.
----
When viewing the preview images for this conky, it should be apparent that the GPU and CPU are being displayed. In order to do that, go to line 57, and change the CPU and GPU to whatever you use. The lines of code should look like this...

```
CPU${alignr}Intel Core i5-4670k@4x 3.8 GHz 
GPU${alignr} EVGA GeForce GTX 970 SC 
```

If your CPU has a different amount of cores, than delete line 66 and upward. To adjust the graph, then change the parameters on 53 and 54 on bright_modern-graphs to your liking. Those lines should look like this...

```
${cpugraph cpu1, 50,150} ${cpugraph cpu2, 50,150} 
${cpugraph cpu3, 50,150} ${cpugraph cpu4, 50,150}
```
