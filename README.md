# music-taster

Repo for Department of Computer Science open day taster session about music processing.

Prepared by Eamonn Bell (Durham University), April 2023.

**BEFORE YOU BEGIN**: Please ensure that the volume control on your headphones is at the lowest possible setting, and is correctly connected to the headphone jack of the computer you will use to work on these materials.

# First steps

1. Ensure your computer is booted to the Linux desktop 
2. Login in using the credentials provided
3. Open up a browser window (in the top left corner of the screen, Applications > Internet > Firefox ESR)
4. Visit this url: https://github.com/eamonnbell-dur/music-taster
5. Follow the steps under "Preferred option"

# Preferred option

To begin click on this badge:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eamonnbell-dur/music-taster/HEAD?labpath=taster.ipynb)

Or, equivalently, visit this URL:

### [https://mybinder.org/v2/gh/eamonnbell-dur/music-taster/HEAD?labpath=taster.ipynb](https://mybinder.org/v2/gh/eamonnbell-dur/music-taster/HEAD?labpath=taster.ipynb)

---

## Backup option

Tested on Durham Linux Desktop (Debian). These steps are to be followed if the myBinder.org solution does not work. You can use this approach at home, too, if you have access to a Linux environment. 


1. Open up a terminal window
2. Copy, paste, and run the following commands in order into the terminal window
    - `pip install librosa numpy==1.19.0 pretty_midi ipywidgets==8.0.4 ipywebrtc yt-dlp jupyterlab`
        - If a window pops up relating to a keychain/wallet, click `Cancel`.
    - `git clone https://github.com/eamonnbell-dur/music-taster`
    - `cd music-taster`
    - `jupyter lab`
3. At this point, a browser window should open and you will shortly see the Jupyter Lab interface. Navigate to the `taster.ipynb` file to begin.

If you are trying this at home, you may also need some libraries and tools provided by the following packages on Linux (Ubuntu 18.04), which will be automatically installed if you use myBinder.org or the Durham Linux Desktop.

- `libsndfile-dev`
- `ffmpeg`


## Using `conda`

Alternatively, you can use Anaconda to create a new `conda` environment that includes the dependencies required to execute the notebook.

For instructions, [see here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file).

The software dependencies for this notebook can be found in `environment.yml` in the root directory of this repository. 

You may also need some libraries and tools provided by the following packages on Linux (Ubuntu 18.04), which will be automatically installed if you use myBinder.org.

- `libsndfile-dev`
- `ffmpeg`
