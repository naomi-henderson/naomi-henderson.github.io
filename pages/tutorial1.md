---
layout: page
title: All in the Cloud
tagline: Pangeo JupyterHub for Pangeo Data
description: 
---

### Quick tutorial for using the Pangeo CMIP6 Data Collection directly on the Pangeo JupyterHub running in Google Cloud

#### GOALS: 
- Log onto Google **Cloud Compute Engine**  
- Start interacting with the CMIP6 Google **Cloud Storage**

#### PROCEDURE:
- Step 1. Go to the [Pangeo Jupyter Hub](https://ocean.pangeo.io){:target="_blank_"}
and "Sign in with GLOBUS"

Once you click on this button, you can either log in with your Columbia UNI (this is easiest) but you can also sign in with your [ORCID](https://orcid.org/register), see the lower right hand side of the screen.

-------------
- Step 2. You need to choose one. For now, pick the middle one to get the Hackathon packages pre-loaded.

<p align="center"><img src="/assets/SpawnerOptions.png" width="500"></p>

-------------
- Step 3. Wait. for. it.  A JupyterHub environment should eventually show up. Congratulations! You are on Google Cloud.

-------------
- Step 4.  Open a terminal and enter a few `unix` commands (e.g., `pwd`, `ls`, `w`, `whoami`, `lastlog`). 

-------------
- Step 5. Next, you can download some short tutorial notebooks using this terminal. Copy and paste the following in the terminal.

```
wget http://haden.ldeo.columbia.edu/notebooks/tutorial-Intake.ipynb
wget http://haden.ldeo.columbia.edu/notebooks/tutorial-noIntake.ipynb
```
-------------
- Step 6. The new notebooks should show up in the file browser on the left. Double click a notebook (ends in .ipynb) to open. Start working through tutorial-Intake.ipynb (recommended) or tutorial-noIntake.ipynb (for pythonistas who don't need/want to use the new `intake-esm glossy methods)

-------------
- Step 7. Ask here: [Questions, Comments](/pages/issues.html){:target="_blank_"}. These should be public, so we can all learn from each other. 

-------------
- Step 8. **IMPORTANT:** When you are finished, go to >File >Hub Control Panel >Stop My Server >Logout (upper righthand corner)


