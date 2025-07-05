### Blender on Google Colab

### Video generation

[This Jupyter Notebook](https://github.com/ZygoOoade/Blender_python/blob/main/make_a_360_surround_video_from_a_BLEND_file.ipynb) downloads a file named `file.blend`, installs Blender, and renders 360 images in PNG format at 1280 x 720 pixels. A Python code generates a 30-second video from all these numbered PNG images.

Note that the process is **very long** (as it stands, with our large `blend` file, the process took 2 hours). We will test again on Kaggle by activating a P 100 card, which may speed things up.

The resulting video is available at this link: https://youtu.be/-X_Jl6wwCO4

### Conversion from OBJ to BLEND
The second cell in [this Jupyter Notebook](https://github.com/ZygoOoade/Blender_python/blob/main/Visualisation_d'un_visage_3D_sur_Blender.ipynb) install Blender on Colab and convert the file `/content/file.obj` to `/content/file.blend`
The third cell in this same Jupyter Notebook generates five different renderings to give an idea of the position parameters to be modified (camera position vector and orientation position vector). It would be a good idea to create a **clickable button** to select the best perspective on the object.

Here an output example :
![Visage](https://github.com/ZygoOoade/Blender_python/blob/main/3D%20renderings/visage.png "Titre de l'image").
