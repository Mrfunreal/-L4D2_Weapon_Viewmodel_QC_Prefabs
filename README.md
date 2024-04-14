# L4D2 Weapon Viewmodel QC Prefabs

This is a set of weapon viewmodel QC files for Left 4 Dead 2.<br>
All the important bits that you need to change for every weapon mod are already set up.<br>
The only strings you need to edit now are:
- $Model
- $CdMaterials
- IkRules in $sequences (maybe, depends on your anim)
- Sound and particle events in $sequences
- FPS, if you animate on higher framecount.
- Dupe the $animation block and change their prefix.

The $Sequences are all set up to load their respective $Animation.<br>
Non-Layer sequences use animations with an A prefix, while layer sequences use those with the AL Prefix.<br>
This is set up to prevent animations from breaking when decompiling.<br>
I could have set these up for you beforehand, but i myself always edit the FPS, so i would always need to edit two lines for that. Just duping and renaming is quicker.
