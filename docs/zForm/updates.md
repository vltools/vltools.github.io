# Updates

### v2.3.0 (03/22/2025)
The newest version of zForm is packed with new features and improvements.

- **Aesthetic UI Improvements**:  
  The Input Type is now a dropdown, enabling the addition of more input type options in the future, especially for scaling.

- **Deform Mesh**:  
  A new feature in the Mesh Properties section that allows you to bend, twist, taper, and stretch the mesh with several options to give you more control.

- **Texture Properties**:  
  A brand-new section filled with loads of features such as:  
    - Control over contrast and brightness of depth maps  
    - Presets for quick template adjustments to the mesh  
    - Cropping, mapping extension, and color space  
    - Depth Map Painting for editing the depth map in Paint mode  

- **Utility Tools**:  
  A new section at the bottom that includes an **Export Animation** feature, allowing you to export animations as GLB/GLTF files for Video and Directory input types. I’ve also added some basic instructions for exporting a single mesh.


### v2.2.4 (02/18/2025)
- **Lingering fix with normals:** One more fix to correct facing normals when the background removal feature isn't being used.

### v2.2.3 (01/20/2025)
- **Another fix for Normal Corrections:** Resolves an issue with normals that occurred after applying all modifiers.

### v2.2.2 (01/12/2025)
- **Recalculate Normals:** A fix to recalculate normals after applying all modifiers.

### v2.2.1 (01/09/2025)
- **Handle inverted grayscale images:** Now supports negative Depth Strength values for depth map images with inverted grayscale colors.

### v2.2.0 (01/06/2025)
- **New Feature to remove entire backside of a mesh:** Allows you to remove the entire backside of a mesh for a clean, smooth cut.

### v2.0.9 (12/26/2024)
- **Fixed Normals:** Resolved an issue where normals were flipped immediately after clicking “Apply Depth Map.”

### v2.0.8 (12/08/2024)
- **"Apply All Modifiers" for Directory:** Fixed an issue where the material would change frame by frame instead of staying static.
- **Error Handling for Directory:** Added error handling when some images in a directory didn't have corresponding depth maps.

### v2.0.7 (11/27/2024)
- **UI improvements:** Added an "Expand All" button to expand or collapse all sections at once.

### v2.0.6 (11/26/2024)
- **UI improvements:** Each main section now includes collapse/expand functionality to keep the interface clean.

### v2.0.5 (11/25/2024)
- **Improve file path handling:** Fixed cases where file paths weren't handled correctly.

### v2.0.4 (11/24/2024)
- **Compatible with Blender 4.3:** zForm is now fully compatible with Blender 4.3.

### v2.0.3 (11/23/2024)
- **Resolved Rotation and Mesh View Issues:** Fixed rotation and mesh view compatibility issues.
- **Modular Code Rebuild:** Reorganized and rebuilt the project code for better scalability and future development.

### v2.0.2 (11/21/2024)
- **Enhanced Handling of Missing Depth Maps:** Added error handling for images missing associated depth maps while still processing images that do.

### v2.0.1 (11/20/2024)
- **New functionality for Video and Image Sequences:** Generate 3D meshes from videos and image sequences. (Full product page updates are in progress.)

### v1.0.4 (11/01/2024)
- **Alpha Transparency Support Added:** Implemented support for images with alpha channels (PNG files only).

### v1.0.3 (10/31/2024)
- **Solidify Option Added:** Introduced mesh thickness control via a new Solidify modifier, with adjustable thickness from 0 to 10 units (default 0.02).

### v1.0.2 (10/25/2024)
- **Stay in your view:** zForm now maintains your preferred mesh view instead of resetting to Front View.
- **Increased max Smooth Factor:** Raised the maximum Smooth Factor from 2 to 6.
- **Applied rotation and scale:** Automatically applies rotation and scale to the mesh for a smoother workflow.

### v1.0.1 (10/13/2024)
- **NEW FEATURE:** Added an option to apply all modifiers within the tool.

