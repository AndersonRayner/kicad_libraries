# ARCL KiCAD Libraries
KiCAD libraries for ARCL parts

# Installation
## Symbol Library
Add as a Global Library in
```
KiCAD > Preferences > Manage Symbol Libraries 
```

## Footprint Library
Add as a Global Library in
```
KiCAD > Preferences > Manage Footprint Libraries 
```

# 3D Models Library
For the libraries to find the 3D models, you'll need to add an environment variable that points to the 3D models folder.  Go to 
```
KiCAD > Preferences > Configure Paths
```
and add the variable
```
ARCL3DMOD
```
linking it to 'kical_libraries/3D_models'
