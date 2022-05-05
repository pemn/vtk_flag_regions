## 📌 Description
flag solid regions in a block model. export points inside solids.  
Does not require vulcan or any other proprietary software.  
## 📸 Screenshot
![screenshot1](https://github.com/pemn/assets/blob/main/vtk_flag_regions1.png?raw=true)  
## 📝 Parameters
|Name|optional|description|
|---|---|---------|
block_model||input block model in vtk or csv format<br/>Also accepts a generic grid schema, as detailed in notes.
regions||closed meshes which will flag the blocks inside
flag_var||field that will be create with the region name in each block
flag2d||instead of using meshes as 3d volumes consider only the 2d footprint
output||path to save the modified block model
display||show the meshes in a 3d window
## 📓 Notes
### Grid schema format
Instead of a block model file you can input a grid schema string with the syntax:  
`<xlength>,<ylength>,<zlength>;<rotation in cartesian degrees>`  
Ex.:  
 * `50,50,50` blocks of 50 meters with no rotation  
 * `10,10,10;45` blocks of 10 with a 45 degree rotation  

## 📚 Examples
![screenshot2](https://github.com/pemn/assets/blob/main/vtk_flag_regions2.jpg?raw=true)  
## 💎 License
Apache 2.0
