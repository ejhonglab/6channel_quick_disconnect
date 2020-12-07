
`6channel_quick_disconnect.FCStd` produced with FreeCAD `0.19`. All parts
besides `release_bar` were derived from McMaster-Carr supplied 3D models.

To generate `release_bar.stl`:
1. Open `6channel_quick_disconnect.FCStd` in FreeCAD
2. Select `release_bar` in the tree view at the left. May need to expand
   `6channel_quick_disconnect` first.
3. `File->Export`. Under the `Files of type:` menu at the bottom, select
   `STL Mesh (*.stl *.ast)`. Rename file to `release_bar.stl`. Press `Save`.

I used PrusaSlicer `2.2.9.1` to slice the `.stl` to the `.gcode` file.

Only use `release_bar_0.15mm_PLA_MK3S_29m.gcode` if printing with PLA on a Prusa
i3 MK3S / MK3S+ printer. Otherwise, slice `release_bar.stl` with settings
specific to your 3D printer.

