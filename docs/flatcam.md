# FlatCAM

## Opening your files
First, go to File>Open>Open Gerber... and find the Gerber X2 File saved from Altium. You should only need Copper Signal 1 (and 2 if you have a bottom layer), and Profile. Then to open the drill file, repeat the last step, except click on Excellon... and choose filename.TXT. 

[<img src= "./pics/gerber.png">]()
> above: here is what your files should look like

If you need to change your x-y axis, select all of your files, then choose Options>Object Transform and adjust the Offset values to adjust where the files are in relation to the axis. I used the offset to place the inner green corner on the axis, instead of the outer green corner. 

[<img src= "./pics/offset.png">]()

## Creating the Routing and Drill files
Go to Copper Signal 1 (or at least the file with your main traces) and click on Isolation Routing

[<img src= "./pics/step1.png">]()

A sidebar opens up with different options and this will create the "geometry" of your board. This is like the in between from the Altium Gerber to the CNC files
* Tool Diameter: Choose a slightly larger diameter to essentially tell them "yes my tool is this wide
[<img src= "./pics/oopsstep1.png">]()
[<img src= "./pics/step2.png">]()








