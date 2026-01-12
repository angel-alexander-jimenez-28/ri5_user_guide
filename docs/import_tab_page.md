# Rig In 5 (Import Tab) **[watch in Youtube](https://www.youtube.com/).**

Once you have installed the addon this is the panel you'll see by default, The **import** Tab<br>
is active logically because this is the first step we need to do to start any car rigging process,<br>
if you are working on your own model instead or make another importation using the blender files<br> 
imports like, **FBX, OBJ, USD**... and so on!! you can skip this tab... and start your process on **Reset** Tab.

![Ri5_Guide_Images](images/First_View.png)

## Import from PC

to import from our PC activate the PC Sub tab. there we just have one Operator<br>
call **import model ( glb / gltf ) formats** as shown below

![Ri5_Guide_Images](images/from_pc.png)<br>
when clicked! this launch a blender's **Import Helper Windows** where we can choose our Downloaded car model<br>

as you can see below.
![Ri5_Guide_Images](images/imports_pc.png)<br>

in this case i've import the [Police Raptor](https://sketchfab.com/3d-models/ford-f150-raptor-police-840ede58ed40499a9cf332e25129f0b2) car which i've downloaded earlier from sketchfab page<br>
<iframe title="Ford F150 Raptor Police" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/840ede58ed40499a9cf332e25129f0b2/embed"> </iframe><br>

inside Blender this is what we get.
![Ri5_Guide_Images](images/imported_pc.png)<br>

## Import using Sketchfab API

by clicking the Sub-Tab "Sketchfab" as shown below , we can see more tools to make our car imports
here i reimplement another **sketchfab API** **to connect your sketchfab account with blender** i kept
mostly the same GUI that we can see on the [**Sketchfab Addon**](https://github.com/sketchfab/blender-plugin). the main difference is that here on Rig In 5
we just can search and import car models by default, if you want to download other type of model you need
to **deactivate** the property **Is s Car** we found on the **Clean Tab**, this will explained in details there.

**Is a Car** property on the Clean Tab
![Ri5_Guide_Images](images/Is_aCar_prop.png)<br>

as you can see in the image below activating the **sketchfab** option we have many options
like activate the addon, import from URL, a search text field to type whatever we want to search
![Ri5_Guide_Images](images/from_sketchfab.png)<br>

before to do anything we need to activate the addon clicking the corresponding Operator 

pressing "Activate add-on"
![Ri5_Guide_Images](images/sketchfab_activated.png)<br>

once you do that you can Used **two ways** to connect your Sketchfab account with Rig In 5<br>
and start download model from the sketchfab platform within blender directly to you Scene<br>
by default to property **"Use mail/password"** is activated so you can provide your sketchfab<br>
Login Email and Password here to connect.

![Ri5_Guide_Images](images/login_type_1.png)<br>

if property **"Use mail/password"** is deactivated you are telling the add-on to used other way to connect<br>
which is Using "Api Token" that sketchfab create for us when we make a new account.<br> 
the Api Token can be found this way go to **My Settings -> password & api -> API token** <br>
![Ri5_Guide_Images](images/api_token_on_sf.png)<br>

copy that API Token from the sketchfab page and paste here them press **Log in**<br>
![Ri5_Guide_Images](images/login_type_2.png)<br>

Once you logged this is what you get, so now you can search the car you want to Rig!<br>
to keep this guide aligned let's used the URL import type.
![Ri5_Guide_Images](images/when_loged.png)<br>

### Sketchfab imports by URL

to use URL imports we need to activate **"import from url"**

import from url deactivated<br>
![Ri5_Guide_Images](images/import_by_url_1.png)<br>

as you can see above while **"import from url"** is **deactivated** the addon shows us a full<br>
features to search with that can display thumbnails of the model provided from internet<br>
even details like Name, Author, Licensing, Geometry Data which is cool because we can<br>
see what we are downloading with ease just in Blender UI.<br>

now if import from url is **activated** we only get a URL textfield to be fill<br>
![Ri5_Guide_Images](images/import_by_url_2.png)<br>

so in our browser, we need to copy the URL of the model we we to import to our scene in blender<br>
just like shown below:<br>
![Ri5_Guide_Images](images/import_by_url_3.png)<br>

and paste it here, and when you press import button you done,<br>
now that model would be downloaded directly from sketchfab page to you blender scene.<br>
![Ri5_Guide_Images](images/import_by_url_4.png)<br>

Result:<br>
![Ri5_Guide_Images](images/import_by_url_5.png)<br>

### Sketchfab imports by Search

now lets make an import using from blender itself without the need to go to a browser<br>
for we make sure to deactivate **"import from url"** to see panel we saw before:

this one from here:<br>
![Ri5_Guide_Images](images/search_import.png)<br>

Steps Followed on above images:<br>

1) deactivate **Import from url**

2) type the of the model you are looking for like this example **"raptor police"**, then clean search button

3) if you want can use the filtering features shown to get a more accurate result. pick **"cars-vehicles"**

this are all the filtering option available:<br>
![Ri5_Guide_Images](images/filtering_options.png)<br>

as you can see a model thumbnail that will help us to recognize the model we want<br>
if you click the thumbnail a list will popup showing us more options if these ones exist<br>
as searching result like are shown here:<br>
![Ri5_Guide_Images](images/looking_loaded_list.png)<br>

3.1) the button with chain icon will open your web browser taking you to the exact model on the sketchfab page<br>

4) pressing **import model (file weight)**. start downloading the **"raptor police"** model to your blender scene,<br>
keep in mind depending the model size or weight this process can take some time.

## Great Free Car Resources on Sketchfab

i want to shear some of the best sketchfab Car Artist that you need to know.

[**Ddiaz Design**](https://sketchfab.com/ddiaz-design/models), here you can find really good car model<br>
that are **really easy to rig with Rig In 5**. i just love rig his cars for that.<br>
![Ri5_Guide_Images](images/ddiaz.png)<br>

[**ᗩᒪE᙭. Kᗩ.**](https://sketchfab.com/Alex.Ka./models),<br>
![Ri5_Guide_Images](images/alexka.png)<br>

[**Outlaw Games™**](https://sketchfab.com/Outlaw_Games/models),<br>
![Ri5_Guide_Images](images/OutLaw.png)<br>

[**OUTPISTON**](https://sketchfab.com/outpiston/models),<br>
![Ri5_Guide_Images](images/Outpiston.png)<br>

[**SDC PERFORMANCE**](https://sketchfab.com/Lambo_SC04/models),<br>
![Ri5_Guide_Images](images/SDC%20PERFORMANCE.png)<br>

[**vecarz**](https://sketchfab.com/heynic/models),<br>
![Ri5_Guide_Images](images/vecarz.png)<br>


