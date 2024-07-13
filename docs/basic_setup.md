## Basic Set Up 
> Refer to some excellent walkthrough videos by Blackheart_six here: https://www.youtube.com/@blackheart_six

1. Create a local directory structure where you'll clone this repository and work on the ShadowScenarioTemplate. 
Here is an example directory structure:
-MyProjects 
--ArmaReforgerProjects
---Released
---shadow_dev (this repo)
---WIP

2. Start Arma Reforger, go into Workshop, and download the mods you want to work with or use as dependencies. At minimum, recommend downloading RHS Status Quo. 
> This will download the mods in MyGames > ArmaReforger > addons > mods directories. 

3. Start Arma Reforger Tools, select +Add Project, add existing project, point to the above addons directory and select RHS. 
> This will now load RHS with a locked symbol into your Projects browser. 

4. Close Arma Reforger Tools. Clone this github repository (shadow_dev) to your local ArmaReforgerProjects directory (see #1 above). 
5. Start Arma Reforger Tools, click on +Add Project, add existing project, navigate to your ArmaReforgerProject > shadow_dev directory, click open. 


To be continued, need someone to test the above. 

- To create a new project, create the following directories: ProjectName: Missions, worlds, images.
- Navigate to ArmaReforger directory > worlds, open up a Arland.ent world, click on new world, save world > save as new-sub scene > in your worlds > create a folder called Eden and save it there. 
- With Eden.ent still open, click on plugins, select Game Mode Set Up > choose Scenario Framework > go thorugh the prompts. When completed, remove the default loaded managers with the following: 
  - FactionManager_Editor 
  - LoadoutManager_Base

- Under GameModeSF > fine SCR_RespanSystemComponent > change SpawnLogic (select returning arrow to clear default) > then type, and find SCR_MenuSpawnLogic. 

> ### To get custom uniforms, any duplicate or overriden custom soldiers (find a soldier in RHS, right click > override to get that version in your local working directory). Note once you customize the soldier, add to the config/entitiy catalogue (duplicate to have in local directory, add custom soldier).
> Otherwise they will be overriden by default setting from entity catalogue. Make sure to provide change the names by adding _shadow at the end of edites entities/components. 
