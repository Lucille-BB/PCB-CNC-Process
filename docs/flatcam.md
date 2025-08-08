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
* Tool Diameter: Mattwach has a better description for this, but choosing the V tool (even though the standard blades are V) causes problems, and you can't choose the depth the machine cuts, **at least with my version of FlatCAM.** I had so many problems, so I finally just went with C1 (i'm not sure about the others, they might be fine - I haven't played around with that setting exactly). Choose the diameter that you want the final cuts to be - I usually go with 0.3mm which gives plenty of clearance from the rest of the board. 
* Passes: This is 
* 
[<img src= "./pics/oopsstep1.png">]()
[<img src= "./pics/step2.png">]()








