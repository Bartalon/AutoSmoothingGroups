# AutoSmoothingGroups

This standalone MEL script automatically defines smoothing groups according to UV texture borders exactly the same way smoothing groups are defined in 3ds Max.  This tool specifically ignores texture borders that fall inside polygonal shells, such as with spheres, tubes, and other cylinder bodies; things you would definitely want to be on a single smoothing group.

This one-button solution gives you the best configuration of hard/soft edges for baking normal maps.

- 100% accurate
- Respects custom vertex normals
- Works on multiple objects as once
- Option to skip objects with very high number of UV islands (UV island amount dictates processing speed)
- Works on all versions of Maya all the way back to 2013

(This tool is built in to my other free script, Material Manager)

----

# Change Log

### 1.3
- Script will now detect models that have all vertex normals locked (usually from model imports)
- Author and release details added to top of script
- Executing the tool will now always print the version in the command line

### 1.2
- Fixed a bug where an error would occur if nothing valid was selected.
- Improved how the script determines what version of Maya is being used.


### 1.1
- Added a version check for Maya 2017 Update 5


### 1.0
Initial Release
