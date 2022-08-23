# Overview

This project attempts to simplify the process of creating realistic looking animations of the Earth and global datasets. It outputs either widescreen 4K video or [equirectangular projections](https://en.wikipedia.org/wiki/Equirectangular_projection) designed to be wrapped around [Science On a Sphere](https://sos.noaa.gov/).

![Default Globe](Screenshots/default-globe.jpg)

Example output is available in many of the products on the [GSL visualization page](https://gsl.noaa.gov/focus-areas/data-visualization).

# Usage

This project has been tested on [Adobe After Effects](https://www.adobe.com/products/aftereffects.html) version 17.1.2 or later. In addition, it requires the installation of the free "[Orb](https://www.videocopilot.net/orb/)" plugin. The project should be cloned and After Effects configured to use this project as a template.  Information on how to do this can be found [here](https://helpx.adobe.com/after-effects/using/projects.html#template_projects_and_example_projects).

Much of the configuration can be done inside the "// Controller" composition. Here you can set the time range seen in the animation that controls the timestamp label and the sun position. You can also change the visibility of certain layers and the light settings.

Add global data assets to the "data" composition as new layers. Localized data can be added to the magnifier compositions replacing the A and B compositions.

# Troubleshooting

This project requires GPU acceleration for rendering. Depending on the GPU in your computer you may have to use After Effects built in rendering tool rather than the Adobe Media recorder.

Support is limited, but sos.explorer@noaa.gov with any questions or concerns.  

