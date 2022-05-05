## 📌 Description
flag solid regions in a block model. export points inside solids.  
does not require vulcan or any other proprietary software  
## 📸 Screenshot
![screenshot1](/pemn/assets/vtk_flag_regions1.png?raw=true)
## 📝 Parameters
|Name|optional|description|
|---|---|---------|
||❎||
||☑️||
block_model||input block model in vtk or csv format
regions||closed meshes which will flag the blocks inside
flag_var||field that will be create with the region name in each block
flag2d||instead of using meshes as 3d volumes consider only the 2d footprint
output||path to save the modified block model
display||show the meshes in a 3d window
## 📓 Notes
## 📚 Examples
## 💎 License
Apache 2.0
