# Sublender Panel

### Init
![Init](./images/panel1.jpg) \
As it says, it's best to save your blender project first, or at least
before import any sbsar. Sublender will generate texture in a folder at 
the same directory of your blender file

### Import
Click `Import Sbsar` after init, after selection, sublender will display 
a dialog, click ok to import the graph.

![Dialog](./images/dialog.jpg)
* Fake User \
by default the `Fake User` toggle is enabled, it will prevent blender
remove the material if the material is not used at anywhere
* Material Template/Workflow \
You can choose a template for your instance, current only `PBR Metallic/Roughness` and `PBR Metallic/Roughness/Height` is provided. There is a `Custom` option, if you select it, an empty material will be generated, also all texture will be marked as `render`, you can then customize your material

### Panel

![Panel](./images/details.jpg)

There is not much to talk about it actually. 
* Follow Selection \
with follow selection enabled, you can select an object, the the sublender will 
find the sbs material it's using, this will speed up your work.

![Follow Selection](./images/followselection.gif)

* Workflow
you can updathe the workflow here, and click the button next to it, it will re-generate
every thing.

* Live Update
With Live Update enabled, any changes in input parameters will trigger texture rendering except(output). **WARNING: do not undo! do not undo! do not undo!**