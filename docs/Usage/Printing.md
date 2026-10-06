# Printing

> TODO: images / gifs

In this guide we will show you simplified process of importing your model, positioning it on the bed, slicing it and exporting the g-code so that it can be loaded the printer and at the end printed.

## Configuring the printer

If you haven`t configured your printer yet, please follow the [Adding printers](./Adding%20printers.md) guide.

If you have added your printer but did not configure it for hte printing follow [Configuring](./Configuring.md).

### Quick start up

For the quick set up form 0 to configuring your printer follow those simple steps:

??? tip "Fast star-up guide"

    - click on the printer selection drowp down and select `-- Select/Remove printer (from system presets) --`

    - type `FELIX` into the search bar

    - select printer/s to use in the orca

    - press `Next`

    - under the `Filament` tab press filament's drop down menu and select `-- Add/Remove filament -- `.

    - in the pop-up look for hte correct nozzle / filament type combination provided by FELIX Printers.

    - select filament(s) you want to use

    - in the process tab select the quality process you would like to use. More detailed prints take longer to finish and vice versa.

    - you are all set !

## Importing the model

Orca slicer support various 3D models which it can slice into the instructions for the printer.

There are various ways to impot model you want to print into the orca, but the most straight forward way is by pressing littel cube with a plus next to it inside the top-tool bar panel.

This will bring file explorere dialog which you can use to browes all files in the computer. Use the file browser to navigate to location where you model is downloaded and ither double click on it or select it and press `Open`.

This should close the file broswer window and show you your model inside the orca.

## Position your model.

Positioning your model on the printing bed is done via several controls also available thought the top tool bar menu.

### Translation (Move)

There are multiple ways how one can position their model on the printing mat.

**Drag and drop** - model can be simply dragged around the printing bed this operation **is default** when the model is selected. While convenient, precision of the placement is not the best.

**Movement tool**

!!! tip

    use `M` on your keyboard to quickly enable the move tool

Another way to translate the model on the printing plate is through the **move tool**. You can enable movement tool through the top tool box. It has an icon of little square with small arrows pointing to each of the world directions.

One movement tool is active you will see movement gizmo (three arrows, one pointing to one of the base coordinate system direction `X, Y , Z`)

Through the gizmo you can position the model as accurately as possible.

<figure markdown="span">
  ![Alt text](../images/filename.png){ width="1000" }
  <figcaption>Showcase of different ways to move your model on the printing mat.</figcaption>
</figure>

**Local vs world coordinate space**

You most likely want to use world coordinate system.

??? Optional "What are coordinate systems"

    Every point in 3D world needs to be expressed relative to some coordinate system.

    When 3D model is being created it is expressed in the `local` coordinate system.

    However this coordinate system is only useful when one wishes to create the model. The situation changes when you want to place this model to the world. As it happens one coordinate system can be expressed in relation to another coordinate system.

    When altering the position of hte model you most likely always going to use world coordinate system, since as the name suggests this the coordinate system which represents your world AKA where your print will be executed .

### Rotation

Rotation can be enabled by selecting little square with an arrow orbiting around it.

Once you do, rotation gizmos will appear. They will allow you to rotate your object in one of the 3 main axis of rotation. That is

- yaw (around the object`s up direction X)
- pitch (around the object`s right direction Z)
- roll (around the forward direction, in our case positive Y )

to rotate the object simply drag the desired gizmo in the direction you want to rotate into.

<figure markdown="span">
  ![Alt text](../images/filename.png){ width="1000" }
  <figcaption>Video demonstrating rotation </figcaption>
</figure>

### Scale

As the name suggests, with this option you can make the smaller smaller or bigger.

To enter scaling mode, select the icon with small square enclosed by bigger square with dashed line with arrows connection corners of those two squares.

Gizmos for the scaling operation is resembling ones from the 2D image editors. That is, if you drag the corners of the gizmo you will scale the model uniformly in all directions, or you can choose to scale only in one direction (`X` or `Y`).

<figure markdown="span">
  ![Alt text](../images/filename.png){ width="1000" }
  <figcaption>Uniform scaling by using gizmos</figcaption>
</figure>

<figure markdown="span">
  ![Alt text](../images/filename.png){ width="1000" }
  <figcaption>Non-uniform scaling by using gizmos</figcaption>
</figure>

!!! note

    Uniform scaling is scaling operation which affects the model in each directions equally

In the small pop-up you can also scale the model as expressed by percentage. By default model is in 100% scale.

If you want model which is half as small you can simply type 50 to the `X`, `Y`, and `Z` boxes. If younifrom scaling is enabled you can type your scale to any of teh 3 boxes and the scale will be applied to the model as a whole .

<figure markdown="span">
  ![Alt text](../images/filename.png){ width="1000" }
  <figcaption>Uniform scaling by using percentage</figcaption>
</figure>

### Lay on face

As the name suggests this tool is used to lay model on one of its faces. Orca detects possible faces you can lay your model onto in case of a pentahedron, for example you can select one of hte five faces on which it will lay.

<figure markdown="span">
  ![Alt text](../images/filename.png){ width="1000" }
  <figcaption>Using demonstartion of the lay on the face tool </figcaption>
</figure>

There are also a bit more advanced tools you can use. Such as:

- cutting whose main job is to cut the selected model just as you would with knife

- mesh boolean operations, allows you to preform mesh boolean operations which is basically cutting holes in to the objects with another objects

- painting supports, allows you to paint supports in case automatic supporting did not work for you

- and more

For the full list of features consult orca [wiki page](https://www.orcaslicer.com/wiki/print_prepare/prepare_basic.html)

!!! Tip

    Best way to learn each of those tools is to simply experiment with them
