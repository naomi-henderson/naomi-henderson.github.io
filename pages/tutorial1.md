---
layout: page
title: Pangeo CMIP6
description: 
---

### Quick tutorial for using the Pangeo CMIP6 Repo directly on JupyterHub running in Google Cloud

#### GOALS: 
- Log onto Google **Cloud Compute Engine**  
- Start interacting with the CMIP6 Google **Cloud Storage**

#### PROCEDURE:
- Step 1. Go to the [Pangeo Jupyter Hub](https://ocean.pangeo.io){:target="_blank_"}
and "Sign in with GLOBUS"

Once you click on this button, you can either log in with your Columbia UNI (this is easiest) but you can also sign in with your [ORCID](https://orcid.org/register), see the lower right hand side of the screen.

-------------
- Step 2. Now you will need to choose one. For now, pick the middle one to get the Hackathon packages pre-loaded.

<p align="center"><img src="/assets/SpawnerOptions.png" width="500"></p>

-------------
- Step 3. Wait. for. it.  A JupyterHub environment should eventually show up. Congratulations! You are on Google Cloud.

-------------
- Step 4. Note that there is only one kernel - `Python 3`, but you can `conda/pip install` other packages. The tutorials do not require any other packages. Open a terminal and enter a few `unix` commands (`pwd`, `ls`, `whoami`).

-------------
- Step 5. Next you can download some short tutorials in this terminal. 

```
wget http://haden.ldeo.columbia.edu/notebooks/tutorial-Intake.ipynb
wget http://haden.ldeo.columbia.edu/notebooks/tutorial-noIntake.ipynb
```
-------------
- Step 6. Start working through either tutorial.

-------------
- Step 7. **IMPORTANT:** When you are finished, go to >File >Hub Control Panel >Stop My Server >Logout (upper righthand corner)


