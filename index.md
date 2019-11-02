---
layout: page
title: Naomi Henderson
tagline: current projects
description: a way to share my current projects
---

### Pangeo CMIP6 Google Cloud Repository

- Go to the [Pangeo Jupyter Hub](https://ocean.pangeo.io) and "Sign in with GLOBUS"

Once you click on this button, you can either log in with your Columbia UNI (this is easiest) but you can also sign in with your [ORCID](https://orcid.org/register), see the lower right hand side of the screen.

- Now you will need to choose one of the sizes (doesn't really matter which)
![Spawner Choices](assets/SpawnerOptions.png)

- This is JupyterHub - there is only one kernel - `Python 3`, but you can `conda/pip install` other packages. The tutorials do not require any other packages.

- Next you can download some short tutorials, using either the notebook (put ! at the beginning of the line) or a terminal:

``` 
wget http://haden.ldeo.columbia.edu/notebooks/tutorial-Intake.ipynb
wget http://haden.ldeo.columbia.edu/notebooks/tutorial-noIntake.ipynb
```

- Start working through either tutorial.

- There is also a CatalogViewer notebook
``` 
wget http://haden.ldeo.columbia.edu/notebooks/ViewCatalog.ipynb
```

- When you are finished, go to >File >Hub Control Panel >Stop My Server >Logout (upper righthand corner)
