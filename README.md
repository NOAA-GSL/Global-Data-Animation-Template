# Overview

This project attempts to simplify the process of creating realistic looking animations of the Earth and global datasets. It outputs either widescreen 4K video or [equirectangular projections](https://en.wikipedia.org/wiki/Equirectangular_projection) designed to be wrapped around [Science On a Sphere](https://sos.noaa.gov/). The easiest way to use this project is to grab a [release](https://github.com/NOAA-GSL/Global-Data-Animation-Template/releases).

![Default Globe](Screenshots/default-globe.jpg)
![SOS Output](Screenshots/sos-projection.jpg)

Example output is available in many of the products found on the [GSL visualization page](https://gsl.noaa.gov/focus-areas/data-visualization).

# Usage

**This template requires the installation of the free "[Orb](https://www.videocopilot.net/orb/)" plugin.**  The project should be cloned with [LFS](https://git-lfs.github.com/) enabled or a [release downloaded](https://github.com/NOAA-GSL/Global-Data-Animation-Template/releases). Unfortunately, the "Download ZIP" button will not work since it only includes pointers to the files rather than the files themselves.

Much of the configuration is done inside the Essential Graphics Window looking at the "Globe" compositions. You can change the visibility of certain layers, the location of magnifiers, and the light settings.

| Layer Controls | Magnifier Controls |
| ------------- | ------------- |
| ![Default Globe](Screenshots/layer-controls.jpg)  | ![Default Globe](Screenshots/magnifier-effects-controls.jpg)  |

Magnifier labels are controlled in the Essential Graphics Window from each respective composition. 

![Default Globe](Screenshots/magnifier-labels.jpg)

In the "//Controller" composition you can set the time range that controls the timestamp label and the sun position. 

![Default Globe](Screenshots/time-controls.jpg)

Add global data assets to the "Data" composition as new layers. Localized data can be added to the magnifier compositions replacing the "A" and "B" compositions.

# Screenshots

![Magnifier](Screenshots/magnifier-on-earth.jpg)

# Troubleshooting

Several of the effects used in this template require a high-end graphics card.  If after opening the project the "Globe" composition fails to render a frame your computer may have insufficent power.

This project has been tested on [Adobe After Effects](https://www.adobe.com/products/aftereffects.html) version 17.1.2 or later. This project requires GPU acceleration for rendering. Depending on the GPU in your computer you may have to use After Effects built in rendering tool rather than the Adobe Media encoder.

Support is limited, but sos.explorer@noaa.gov with any questions or concerns. Also feel free to start a discussion on GitHub.