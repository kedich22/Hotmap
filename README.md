[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kedich22/Hotmap/main?labpath=Hotmap_improved_2.ipynb)
# V-HOTMAP application
## The detection of thermal hotspots associated with volcanic activity based on thermal reflection derived from Sentinel-2

The repository includes the code of the modified V-HOTMAP algorithm to detect hotspots. 

It is based on the algorithm developed by and described in the paper of Murphy et al., 2016
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
In the further updates, the list of volcanoes will be broadened.
---
### How to use it?
1. The tool could be used in 2 ways: **on your local server** and through the **binder deployed application**. I strongly advise you to choose the second option.
If you still want to use it on your local computer in the file `requerements.txt` all used Python packages with their versions that should be installed in your python environment, the `runtime.txt` contains the used version of Python.
2. In the Binder-deployed application all packages are already installed and all data could be retrieved online.

### The tutorial
1. During the first access to the application you should authorize yourself through the Jupyter Notebook. Unfortunately, at this point, I have not managed how to include this part directly to GUI. 
2. Click on the binder badge at the top of the README file or [click here](https://mybinder.org/v2/gh/kedich22/Hotmap/main?labpath=Hotmap_improved_2.ipynb) to load the Jupyter Notebook. It might take some time to load the page (up to several minutes) due to the rendering process.
3. After the page is loaded if you are accessing the app for the first time you should authenticate yorself with Earth Engine to provide the access to this Notebook. For this purpose, your account should be already activated through the Google Earth Engine platform. 
Run the first chunk of code &rarr; follow the link &rarr; click "Generate Token" &rarr; Choose your Google account &rarr There will be a notification that Google has not verified this app, click `Continue` &rarr grant the access by ticking both boxes &rarr; copy the provided authorization code into the field in Jupyter Notebook and press enter &rarr; Congratulation! You are successfully authorized and could use the app!
![auth](https://user-images.githubusercontent.com/70434411/183929591-2a1d9d6f-62eb-422f-b38f-63e3e444988e.png)
![auth_token](https://user-images.githubusercontent.com/70434411/183929684-a87aa178-820b-46c1-9011-e2248fdc84e9.png)

4. After clicking on the viola rendering icon and wait until the application is rendered. After it is finally deployed and ready to use!
![voila](https://user-images.githubusercontent.com/70434411/183935707-ced0268c-56fb-4f51-b69b-fefe47df5190.png)

### What could you do
- App allows to monitor and detect hotspots over the selected volcano for a defined timeline. The background layer is visualized in SWIRNIR combination: bands 12, 8A, 5.
- The data could be exported in a series of tif images (`Export data`) (the export firstly is visible on the left in your local online repository, from where you could download it onto your computer) 
- The same way data could be exported in a summing table (`Export table`) that counts the number of hotspots for every available image.
- If you want to remove layers click `Clear`

The following animation shows the example of application implementation:
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/70434411/184100843-47391a64-b195-4fba-91ed-847578bca95f.gif)
### To do list!
- [ ] Improve the authentication process and implement this step inside the GUI
- [ ] Include new volcanoes to the list
- [ ] Make possible also to download satellite images for the area of interest
- [ ] Make a selection of different satellite bands visualization inside GUI
