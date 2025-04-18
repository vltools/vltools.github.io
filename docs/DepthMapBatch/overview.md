# Depth Map Batch (DMB) Documentation

## <strong>Getting Started Guide</strong>

As a starting point, here's a quick getting started guide to using Depth Map Batch that covers all the key areas including installation and using key features. If you want to leverage <strong>GPU acceleration</strong>, please see instructions [here](#install-gpu-packages).

<strong>There are four main steps.</strong>

1. Install the add-on
2. Install the Python library packages using the "Install all Packages" button
3. Close Blender entirely and re-open
4. Download the Model Weights files [here](#download-model-weights-files) and store locally in a directory 

<iframe width="560" height="315" src="https://www.youtube.com/embed/E4hkXFAte88?si=tGQfrPCPKhb7TZ4v" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

And here's a quick demo of how to generate depth maps. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/s0vmL0DWwBY?si=5HO4uIx9o55S6O9X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Download Model Weights Files

If you have any questions on how to use the model weights files, feel free to message me directly or watch this brief video covering that here. You can also watch a video on how to use model weights files [here.](#model-weights)

### Depth Anything V2

#### Depth Anything V2 Small (home page)  
Download the model weights file in the page below:  
🔗 **URL:** [https://huggingface.co/depth-anything/Depth-Anything-V2-Small/blob/main/depth_anything_v2_vits.pth](https://huggingface.co/depth-anything/Depth-Anything-V2-Small/blob/main/depth_anything_v2_vits.pth)  

#### Depth Anything V2 Base (home page)  
Download the model weights file in the page below:  
🔗 **URL:** [https://huggingface.co/depth-anything/Depth-Anything-V2-Base/blob/main/depth_anything_v2_vitb.pth](https://huggingface.co/depth-anything/Depth-Anything-V2-Base/blob/main/depth_anything_v2_vitb.pth)  

#### Depth Anything V2 Large (home page)  
Download the model weights file in the page below:  
🔗 **URL:** [https://huggingface.co/depth-anything/Depth-Anything-V2-Large/blob/main/depth_anything_v2_vitl.pth](https://huggingface.co/depth-anything/Depth-Anything-V2-Large/blob/main/depth_anything_v2_vitl.pth)  

---

### MiDaS  

#### MiDaS 3.1 Large (home page)  
🔗 **URL:** [https://github.com/isl-org/MiDaS/releases/download/v3_1/dpt_beit_large_512.pt](https://github.com/isl-org/MiDaS/releases/download/v3_1/dpt_beit_large_512.pt)  

#### MiDaS 3.0 Large (home page)  
*Rename `dpt_large-midas-2f21e586.pt` to `midas_dpt_large.pth` before use.*  
🔗 **URL:** [https://github.com/intel-isl/DPT/releases/download/1_0/dpt_large-midas-2f21e586.pt](https://github.com/intel-isl/DPT/releases/download/1_0/dpt_large-midas-2f21e586.pt)  

---

### Depth Pro  

#### Depth Pro (home page)  
🔗 **URL:** [https://ml-site.cdn-apple.com/models/depth-pro/depth_pro.pt](https://ml-site.cdn-apple.com/models/depth-pro/depth_pro.pt)  
*Very large file at almost 2GB*  

## <strong>Video Tutorials</strong>

| **Title** | **Description** | **Video Link** |
|-----------|---------------|---------------|
| **Quick Getting Started Guide** | A quick guide to help you get started. | <a href="https://www.youtube.com/watch?v=E4hkXFAte88&feature=youtu.be" target="_blank">Quick Getting Started Guide (click here)</a> |
| **Playlist of Tutorials** | Here's where you can go to see all the latest tutorials. | <a href="https://www.youtube.com/playlist?list=PLGwcOaoVqVLpdcymabECBBkPEiVyFAQo6" target="_blank">All Tutorials (click here)</a> |
| **Installing the add-on** | Steps to install the add-on. | <a href="https://www.youtube.com/watch?si=lo3skr1bF7nDDbNb&v=k97fOj8659g&feature=youtu.be" target="_blank">Installing add-on (click here)</a> |
| **Installing dependencies** | Guide to installing necessary dependencies. | <a href="https://www.youtube.com/watch?v=X1eELz39EV4&feature=youtu.be" target="_blank">Installing dependencies (click here)</a> |
| **Referencing model weights** | How to reference the model weights file. | <a href="https://www.youtube.com/watch?v=QCJ_SBnRtzA" target="_blank">How to reference model weights file (click here)</a> |
| **Depth Map Styles** | Explanation of using Depth Map Styles. | <a href="https://www.youtube.com/watch?v=1s1QCg-gZ2E" target="_blank">Using Depth Map Styles (click here)</a> |
| **Uninstalling Python packages** | Steps to uninstall Python packages. | <a href="https://www.youtube.com/watch?v=b_MeyPJ0kcU" target="_blank">Uninstalling (click here)</a> |

## <strong>Install Add-On</strong>

Follow these steps to install Depth Map Batch in Blender:

1. **Open Blender**
2. Go to **Edit > Preferences**.
3. Select the **Add-ons** tab.
4. Click the **Install from Disk** in the dropdown icon at the top right. 

<img src="/images/dmb/install.jpg" alt="Alt text" width="500">

<img src="/images/dmb/install-from-disk.jpg" alt="Alt text" width="500">

Navigate to and select the downloaded addon ZIP file, then click **Install Add-on**. There is one version for <strong>Windows</strong> and a separate version for <strong>Mac/Linux</strong>, so make sure to choose the right version for your operating system.

In the list of add-ons, check the box next to your addon's name to enable it.

<img src="/images/dmb/enable-addon.jpg" alt="Alt text" width="500">

(Optional) Click **Save Preferences** to keep the addon enabled for future sessions.

<img src="/images/dmb/save-preferences-1.jpg" alt="Alt text" width="500">


<img src="/images/dmb/save-preferences.jpg" alt="Alt text" width="500">

## <strong>Install Python Packages</strong>

Now, expand out the add-on for Depth Map Batch and find the button that says "Install All Packages".  This will allow you to install all dependency libraries in one click. Please give it some time as it could take 3-5 minutes depending on your machine and internet connection.

<img src="/images/dmb/install-packages.jpg" alt="Alt text" width="500">


<strong>Close Out Blender Entirely and Reopen</strong>

Once you've installed all the library packages, close out Blender entirely so that Blender can recognize you have all the libraries ready to go. The add-on will not show up in the side panel unless all required libraries are installed first. 

You can always verify if all packages are installed by going into the add-on in the Preferences window and scrolling down to confirm all libraries say "Uninstall". 

<img src="/images/dmb/list-of-libraries.jpg" alt="Alt text" width="500">

## <strong>Install GPU Packages</strong>

<strong>GPU Support is Optional</strong>
 If you prefer to keep using CPU only, nothing changes—you’re not required to install GPU support for any future updates. This ensures stability for all users while giving you the flexibility to choose.

Scroll to the bottom of the Preferences window → Optional Packages section.

You’ll see a new option:
    "Optional torch with CUDA" (for NVIDIA GPUs)
    "Optional torch with MPS" (for Mac GPUs)

If everything is set, the button will say "Uninstall"; otherwise, click "Install" to enable GPU support.

Make sure to <strong>close out Blender</strong> and reopen before checking if the installation was successful. 

<img src="/images/dmb/install-gpu.jpg" alt="Alt text" width="500">

## <strong>Uninstall Add-on</strong>

<img src="/images/dmb/uninstall.jpg" alt="Alt text" width="500">

Follow these steps to uninstall Depth Map Batch:

1. Open **Blender 4.3**.
2. Go to **Edit > Preferences**.
3. Select the **Add-ons** tab.
4. Locate zForm in the list (you can use the search bar to search for "zForm").
5. Uncheck the box next to the addon’s name to disable it.
6. (Optional) Click **Remove** if available to uninstall the addon completely.
7. Click **Save Preferences** to confirm the changes.

<u><strong>IMPORTANT</strong></u>: You don't need to uninstall the Python library packages each time you upgrade to a new version of Depth Map Batch. They can be left as is. All you need to do is uninstall the actual add-on itself. 

## <strong>Upgrading to new version of DMB</strong>

If you'd like to upgrade to a new version of Depth Map Batch, make sure to first uninstall the old version and close out Blender entirely after. Then re-open Blender and install the new version.

<u><strong>IMPORTANT</strong>: </u>You don't need to uninstall python library packages, only uinstalling the actual add-on itself. Also, if you want to use GPU please follow the instructions [here.](#install-gpu-packages)

<iframe width="560" height="315" src="https://www.youtube.com/embed/Btw1rZ7fXbQ?si=w2juEFoxnilfAr5O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## <strong>User Interface</strong>

There are five main sections in Depth Map Batch including Inputs, Depth Map, Output Settings, Start, and Utility Tools. There is also another section called Last Run Results, but that isn't critical.

<img src="/images/dmb/main-sections.jpg" alt="Alt text" width="500">

### <strong>Inputs</strong>

Inputs is where you will specify what type of inputs you're providing to produce depth maps, whether it be a single image, video, or a directory of images. 

<img src="/images/dmb/inputs.jpg" alt="Alt text" width="500">


#### <strong>Input Method</strong>

There are three options for Input Method including Single Image, Video, and Directory. Currently it defaults to Directory if you don't specify. Currently only PNG, JPG, and JPEG are accepted image formats. 

<img src="/images/dmb/input-method.jpg" alt="Alt text" width="500">

#### <strong>Batch Size</strong>

Batch Size gives you the ability to increase how many parallel processes you want to run at one time to generate depth maps. This is always defaulted to 1, but if you have a powerful machine you could experiment increasing the batch size higher. Increasing the batch size makes it more difficult to stop processes early.

<img src="/images/dmb/batch-size.jpg" alt="Alt text" width="500">

I wouldn't recommend going higher than 3-5 unless you've got a top tier machine. And increasing the batch size doesn't always mean it will produce faster....there needs to be a balance that you'll need to experiment for yourself. 

In my workflow I almost always leave to 1.

#### <strong>Input Source</strong>

The Input Source is the actual image, video, or directory that will be used to generate depth maps for. Make sure if you're using an image or video to double click on the file just in case. 

<img src="/images/dmb/input-source.jpg" alt="Alt text" width="500">

### <strong>Depth Map Options</strong>

<img src="/images/dmb/depth-map-options.jpg" alt="Alt text" width="500">

#### <strong>Enable GPU</strong>

By default, GPU is enabled which means if your machine is set up correctly to generate depth maps levaraging GPU performance, it will do so. But, if your machine doesn't have the necesseary python packages to run GPU, even if your machine has GPU, it will revert back to using CPU.

For those that don't have GPU machines it will just use CPU and there's nothing you need to adjust here. 

<strong>IMPORTANT</strong>: If your machine is set up to use GPU, but you prefer CPU, make sure to uncheck this option before running Depth Map Batch for the first time in an opened file.

<img src="/images/dmb/enable-gpu.jpg" alt="Alt text" width="500">

#### <strong>Depth Map Style</strong>

There are twenty different depth map styles, three of which are pure grayscale including CLOSE_WHITE, 16_BIT, and CLOSE_BLACK. 

Most of the time I will use either CLOSE_WHITE or 16_BIT. But on occasion I might use one of the other color depth map styles for aesthetic purposes to visually show what depth maps look like, or to control RGB colors in texture properties of a displacement map. 

I rarely use CLOSE_BLACK, but it's there for those that prefer that objects closest to the camera view are black and those furthest away being white. 

<img src="/images/dmb/depth-map-style.jpg" alt="Alt text" width="500">


#### <strong>Model Weights</strong>

<iframe width="560" height="315" src="https://www.youtube.com/embed/QCJ_SBnRtzA?si=GM2QynwWImEH6_EE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

A critical section. The directory path you choose in this option is where you've placed all of your model weights files. I recommend saving the model weights files in a directory that's easy to remember for future reference.

<img src="/images/dmb/model-weights.jpg" alt="Alt text" width="500">

Then, once you've specified the directory you can choose which model to use in the dropdown. The only model options displayed are those that you've got model weights files in the directory. 

<img src="/images/dmb/select-model.jpg" alt="Alt text" width="500">

#### <strong>Model Options</strong>

The Model Options section is only used for Depth Anything V2 models to specify the Max Resolution size you want to use for the image being passed into the model. The larger the resolution size the longer it takes, but will typically also produce better quality depth maps.

Max resolution options go from 256 up to 1600 depending on if your machine can handle it.

I rarely go above 1200. If I'm generating depth maps for a sequence of frames for a video that might be 200-500 frames, I will use lower max resolution sizes because of the time it takes to generate depth maps.

<img src="/images/dmb/model-options.jpg" alt="Alt text" width="500">

### <strong>Output Settings</strong>

<img src="/images/dmb/output-settings.jpg" alt="Alt text" width="500">

#### <strong>Output Directory</strong>

The Output Directory section is where to save the depth maps. 

<img src="/images/dmb/output-directory.jpg" alt="Alt text" width="500">

If you would like to save depth maps in the same location as the input directory, just enable the <strong>Use Input Directory</strong> option. 

<img src="/images/dmb/use-input-directory-2.jpg" alt="Alt text" width="500">

#### <strong>Resize Options</strong>

By default, the image size is set to be the same dimensions as the original input files. At any time you can adjust relative or absolute size. 

<strong>IMPORTANT</strong>: 16-bit depth map generations are only possible when you maintain the original image sizes of input files. 

<img src="/images/dmb/resize-options.jpg" alt="Alt text" width="500">

#### <strong>Image Format</strong>

By default, the image format is PNG for depth map generations to keep the highest quality. But you also have the option to choose JPG, or instead generate both PNG and JPG. 

<img src="/images/dmb/image-format.jpg" alt="Alt text" width="500">

#### <strong>Output Type</strong>

By default, the only option selected in Output Type is <strong>Depth Maps</strong>, but there are many other options. If you choose <strong>All Types</strong> it will generate and save images for all types listed.  

If you only want to produce height maps or normal maps based on the original input files that's an option as well. The <strong>Original Frames/Images</strong> will extract individual frames of a video file. 

<img src="/images/dmb/output-type.jpg" alt="Alt text" width="500">

### <strong>Start</strong>

The last step is clicking the <strong>Start</strong> button. Once that's clicked on the entire process will start and you'll be able to monitor progress. 

<img src="/images/dmb/start.jpg" alt="Alt text" width="500">


### <strong>Last Run Results</strong>

If you want to view stats on the last process run time expand out this section. 

<img src="/images/dmb/last-run-time.jpg" alt="Alt text" width="500">

### <strong>Utility Tools</strong>

In the Utility Tools section, all tools are independent of what's being processed for depth maps. These are tools purely to help with workflows. At the moment there is only one tool to compile a directory of images in a directory, like a sequence of frames of a video, into an actual .mp4 file.

<img src="/images/dmb/utility-tools.jpg" alt="Alt text" width="500">

#### <strong>Compile Video</strong>

Steps are pretty straightforward. 

1. Specify the directory where all the images are located
2. Specify the output directory where to save the .mp4 file
3. Name the file in <strong>Output Filename</strong> section
4. Click on <strong>Compile Video</strong>

<img src="/images/dmb/compile-video-4.jpg" alt="Alt text" width="500">

## <strong>FAQ and Tips</strong>

### How to use 16-bit

To generate 16-bit depth maps you need to ensure two things, one is choosinge one of the Depth Anything V2 model weights options, and the other is selecting the 16_BIT depth map style. 

<img src="/images/dmb/16-bit.jpg" alt="Alt text" width="500">

### What are the benefits and drawbacks of using 16-bit?

One of the most unique features for DMB is the ability to generate 16-bit depth maps for 8-bit images, which is difficult to find as a feature in other tools or platforms out there. The biggest benefit of using 16-bit depth maps is the ability to minimize unwanted banding that can occur in 8-bit depth maps as well as be capable of handling higher Subdivision Levels in the mesh to produce more detail without unwanted artifacts. 

This can be beneficial for use-cases like 3D printing or for more accurate camera lighting effects.

There is one drawback that I've experienced though, which is the true depth isn't as good as 8-bit typically. 

### GPU - How can I generate depth maps using GPU instead of CPU? 

Scroll to the bottom of the Preferences window → Optional Packages section.

You’ll see a new option:
    "Optional torch with CUDA" (for NVIDIA GPUs)
    "Optional torch with MPS" (for Mac GPUs)

If everything is set, the button will say "Uninstall"; otherwise, click "Install" to enable GPU support.

Make sure to <strong>close out Blender</strong> and reopen before checking if the installation was successful. 

<img src="/images/dmb/install-gpu.jpg" alt="Alt text" width="500">

Then, make sure you have the "Enable GPU if available" is check on. 

<img src="/images/dmb/enable-gpu.jpg" alt="Alt text" width="500">

### Why don't I see DMB show up in the side-panel menu? 

The add-on will only show up in the side-panel if all necessary library packages are installed, otherwise you will only be able to see the add-on in the Preferences window. It's very possible you didn't close out Blender entirely after installing the packages for the first time, which is important. Otherwise it won't show for the first time in the side-panel until that very first time of closing and reopening Blender. 

The other possible reason could be you don't have all the libraries installed. Maybe you have most or almost all of them. Even if only one isn't installed, the addon will not show up in the side-panel. 

### What types of image formats can I use to generate depth maps?

At this time PNG, JPG, and JPEG

### <strong>Saving and Working with Existings Project Files</strong>

I discovered that the “Relative Paths” setting in Blender’s Preferences was causing problems when reusing saved projects. To fix this, please uncheck "Relative Paths" in the Save and Load window in Preferences. 

<img src="/images/zform/disable-relative-paths.jpg" alt="Alt text" width="500">

<strong>You can follow these steps:</strong>

1. Open Blender and go to Edit → Preferences.
2. In the Preferences window, navigate to the Save And Load section.
3. Uncheck the "Relative Paths" option in the Default To section.
4. In the bottom left of the Preferences window, click on the hamburger icon to save your preferences.
5. This change will be saved for all future project files. If you ever need to revert to the previous behavior, simply re-check the "Relative Paths" option.

Additional Note for zForm Users:
When reopening an older project in zForm, please note that the Mesh View option defaults to top view. You may need to adjust this setting manually.

## <strong>Newest Updates</strong>
Check out all the release and code updates [**here**](/DepthMapBatch/updates/)

