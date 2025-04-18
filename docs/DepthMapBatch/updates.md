# Updates

### v2.6.4 (04/18/2025)
- **Added automatic cleanup:** Now removes all objects in the "dm_batch" collection and deletes the collection itself after processing completes.

### v2.6.3 (04/16/2025)
- **Issue Fixed:** When you enable the Use Input Directory option, run the process, and then disable it afterward, the addon would continue to save images to the input directory instead of the newly specified output location.

### v2.6.2 (03/30/2025)
- **Added reminder message in Preferences of Addon:** A new reminder message has been added in the Optional Packages section at the very bottom of the addon in the Preferences window to remind people to close out and reopen Blender after installing optional python libraries to be recognized. 

### v2.6.1 (03/27/2025)
- **Fixed 16-bit depth map generation issue:** Resolved a problem affecting GPU processing for different image dimensions. CPU processing remains unchanged.

### v2.6.0 (03/26/2025)
- **GPU Acceleration Support:** Now available across all operating systems.

### v2.5.5_beta (03/04/2025)
- **Introducing Utility Tools – Basic Video Compiler:** Allows video creation from a directory of images.

### v2.5.3_beta (02/25/2025)
- **Fixed Output Type handling in Blender 3.6 (Mac):** New UI for Output Type now functions properly.

### v2.5.2_beta (02/20/2025)
- **Improved Output Type Functionality:** Redesigned UI for selecting multiple output types or "All Types" with one click.

### v2.5.1 (02/18/2025)
- **New Support for Depth Pro:** The required Python library is now included in the "Optional Packages" section in Preferences.

### v2.4.1 (02/14/2025)
- **New Info Message for Depth Map Style:** UI message reminder for render engine settings when using the "16_BIT" option.

### v2.4.0 (02/12/2025)
- **Extract Original Frames from Video:** A new Output Type, "Original Frames/Images," extracts frames from video files.

### v2.3.9 (01/30/2025)
- **Improved Normal Map Quality:** Enhancements for the Output Type option.

### v2.3.7 (01/26/2025)
- **Experimental Depth Mapping Option: Depth Pro:** Test version available for current customers.

### v2.3.6 (01/24/2025)
- **Renamed "Image" option to "Image Directory":** Updated terminology in the Input Method section.

### v2.3.5 (01/08/2025)
- **Added support for all model weights in Depth Anything V2.**

### v2.3.4 (12/31/2024)
- **Expanded model max resolution options:** Now supports 256, 512, 1024, 1100, 1200, 1300, 1400, 1500, and 1600.

### v2.3.3 (12/26/2024)
- **Fixed Input Directory handling issue:** Resolved a problem using the Input Directory as the Output Directory path.

### v2.3.2 (12/24/2024)
- **Enhanced Output Path Options:** Allows selecting the Input Directory for the Output Directory path.

### v2.3.1 (12/13/2024)
- **New 16-BIT Depth Map Style:** Enables generating 16-bit depth maps.

### v2.2.1 (12/07/2024)
- **Fixed new installation issues and video output of normals.**

### v2.2.0 (12/06/2024)
- **Higher Quality Depth Maps:** Added "Max Resolution" options (512, 1024, 1600) and new Model Weights UI.

### v2.1.0 (11/30/2024)
- **New Path-Saving Feature:** Saves model weights file path and adds compatibility with Blender 4.3.

### v2.0.9_Beta (11/19/2024)
- **Midas 3.1 Model Fix:** Resolved issues with inconsistent image dimensions.

### v2.0.8_Beta (11/04/2024)
- **Introduced 16-Bit Depth Map Generation.**

### v2.0.7 (10/31/2024)
- **PNG Export Fix:** Corrected DPI handling for PNG exports.

### v2.0.6 (10/28/2024)
- **DPI Handling Enhancement:** Improved DPI processing for both JPEGs and PNGs.

### v2.0.5 (10/25/2024)
- **Alpha Channel Support:** Retains transparency in images.

### v2.0.4 (10/20/2024)
- **Two new grayscale styles:** "Close White" (white closer) and "Close Black" (black closer).

### v2.0.3 (10/19/2024)
- **Filename and File Type Updates:** Added `_depth` to output filenames and automatic renaming to prevent overwriting.

### v2.0.2 (10/19/2024)
- **Fixed OneDrive Support issue.**

### v2.0.0 (10/16/2024)
- **New Depth Map Models:** Added Depth Anything V2 and Midas 3.1, replacing Midas 3.0.

### v1.0.6 (10/13/2024)
- **Renamed "Images" Output Type to "Depth Maps".**

### v1.0.5 (10/11/2024)
- **New Feature:** Added a new input method for using a single image.

