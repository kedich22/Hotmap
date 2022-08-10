[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kedich22/Hotmap/main?labpath=Hotmap_improved_2.ipynb)
# V-Hotmap application
## The detection of thermal hostspots associated with volcanic activity based on thermal reflection derived from Sentinel-2

The repository includes the code of modified v-Hotmap algorithm to detect hotspots. It is based on the paper of Murphy et al., 2016
Sam W. Murphy, Carlos Roberto de Souza Filho, Rob Wright, Giovanni Sabatino, Rosa Correa Pabon,
HOTMAP: Global hot target detection at moderate spatial resolution, Remote Sensing of Environment, Volume 177, 2016, Pages 78-88, ISSN 0034-4257,
[link click here](https://doi.org/10.1016/j.rse.2016.02.027)

The main changes are:

---
The developed tool is now applicable to the following volcanoes:
- Kilauea
- Nyiragongo 
- Nyamuragira Erta Ale
- Villarrica 
- Yasur 
- Stromboli
- Etna
In the further version the list of volcanoes will be broaden.
---
### How to use?
1. The tool could be used in 2 ways: **on your local server** and through the **binder deployed application** ==. I strongly advise to choose the second option.
If you still want to use it on your local computer in the file `requerements.txt` all used Python packages with their versions that should be installed in your python environment, the `runtime.txt` contains the used version of Python.
2. In Binder application all packages are already installed and all data could be retrieved online.

### The tutorial
1. During the first access to the application you should authorize yourself through the Jupyter Notebook. Unfortunately at this point I have nor managed how to include ths part directly to GUI. 
2. Click on the binder badge at the top of the README file or [click here](https://mybinder.org/v2/gh/kedich22/Hotmap/main?labpath=Hotmap_improved_2.ipynb) to load the Jupyter Notebook.
3. After the page loaded if you are accesing the app for the first time you should authentificate Earth Engine to provide the access to this Notebook. For this purposes your account should be already activated through the Google Earth Engine plarform. 
Run the first chunk of code &rarr; follow the link &rarr; cick "Generate Token" &rarr; Choose your Google account &rarr There will be an notification that Google hasn not verified this app, clcik `Continue` &rarr grant the access by ticking both boxes &rarr; copy the provided authorisation code into the field in Jupyter Notebook and press enter &rarr; Congratulation! You are succesfully authorised and could use the app!
![auth](https://user-images.githubusercontent.com/70434411/183929591-2a1d9d6f-62eb-422f-b38f-63e3e444988e.png)
![auth_token](https://user-images.githubusercontent.com/70434411/183929684-a87aa178-820b-46c1-9011-e2248fdc84e9.png)

4. After click on the viola rendering icon and wait until the application is rendered. After it is finally deployed and ready to use!





