# Mods for the LGX Lite Stealthburner

I forked the repo from [Eytecz's LGX Lite Stealthburner](https://github.com/Eytecz/LGX_Lite_Stealthburner_CW2_style_mount) and added some mods for mounting the [Huvud v.61](https://github.com/bondus/KlipperToolboard) CAN-BUS toolhead board.

## Files

## CAD Files for Designers

* **LGX_Lite_Stealthburner with Huvud v30**: Fusion 360 archive of all the mods, based on the Eytecz' original.
* **Huvud v.61 v7**: Accurate F360/STEP model of the Huvud v.61 PCB including all of the connectors. Pulled from the original Kicad files.
* **Huvud Cover Mount**: This model is a cover that integrates the mounting holes for the Huvud board into the cover. Requires supports to print, untested.

## 3MF Files for Printing

The 3MF folder contains files you can print - PrusaSlicer/SuperSlicer/Cura can all open 3MF files.

Print the files in the orientations they're shown as.

* **Huvud Cover Mount**: Cover with integrated Huvud mounting spots. Requires supports to print, I recommand adding Support Enforcer columns under the overhang and the mounting brackets. Mounts to the top hole on the LGX Lite body, with M3 square nuts inside the LGX Lite. 2nd mount point on the back of the extruder, where the hinged cover normally mounts. Screws in through the front of the extruder body.
* **LGX Lite SB Rear Tool Board Mount**: This is a mount that will fit over the back of the NEMA14 stepper. Requires M3 heat inserts in the two posts, and longer screws through the NEMA 14 mounting holes. Optionally, you can drill out the threaded holes in the NEMA14 stepper and thread into the heat inserts. May require a few M3 washers to space the board off the back of the plate to clear the stepper.
* **LGX Lite SB Side Huvud Mount**: This is a mounting plate that fits onto the side of the LGX Lite extruder, using M3 Flat Head Countersunk Screws (FHCS) and threads into square M3 nuts that you insert into the LGX Lite Body. Attach the Huvud board to the plate with short M3 screws threaded into the plastic posts.
