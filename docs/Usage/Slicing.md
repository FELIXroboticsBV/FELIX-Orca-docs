# Slicing

Slicing is a process of converting your model to the instructions understandable by our printers.

The output of the slicer is a file with a list of instructions and various metadata for the printer. This file is called called `gcode` and most commonly contains extension `.gcode` or `.gx`

Thanks to orca this process is as simple as clicking one button.

Before proceeding with this guide make suer you have your model prepared for slicing. You can learn how to do that in a [Printing guide](./Printing.md)

---

To slice your model simply click on the `Slice plate` button on the top right of your screen.

<figure markdown="span">
  ![Alt text](../images/printing-and-slicing/slicing.gif){ width="1000" }
  <figcaption>Slicing</figcaption>
</figure>

!!! Warning

    Depending on the complexity and selected process (quality preset) this process might take multiple minutes and in extreme cases even hours.

## Print preview

Once the model is sliced you will be automatically redirected to the preview panel.

If you are not, you can press `Tab` on your keyboard or select `Preview` on the top menu bar to examine the paths which your printer will take.

### Horizontal slider

Horizontal slider represents `Layer progress` this will show you how the extruder moves on the given layer and in which order it is going to extrude material on the printing bed.

You can play this as a timlapse or use your mouse to drag the slider around.

### Vertical slider

Vertical slider is used to switch between different layers, unlike horizontal slider you can not run the timelapse of layer printing.

Use this slider to examine how the you model will be printed from the inside. You can observe vrious infill patterns as well as supports and inner walls.

## Exporting your model

Once you are happy with the g-code you can press export to the disk.

This will show you pop-up with the same file browser as when you were importing you model.

This time around, however, you need to navigate to the location on your computer where you want the `.gcode` file to be saved.

<figure markdown="span">
  ![Alt text](../images/printing-and-slicing/exporting-sliced-model.gif){ width="1000" }
  <figcaption>Image caption</figcaption>
</figure>
