# COVAS_Next_OBSControl

OBS Control Plugin for COVAS:Next

This plugin enables COVAS:Next to have basic control of OBS Studio via voice commands or by typing into the COVAS chat for people that stream Elite:Dangerous and use COVAS.

COVAS will be able to tell you the current OBS scene in use and switch to a requested scene.

Example commands would be:
what is the current media source?
what is the current OBS scene?
what is the state of the media hardware?
switch to Chatting
switch to LiveScene
hide (name of camera source such as "webcam")

You must ensure that your scenes in OBS have no spaces, hyphens or underscores and DEFINATELY no similar names such as Chatting and Chatting Tarot if you have different scene setups for different chats i.e IRL and 
inStudio make sure the scene names reflect that.

You must include details of the new COVAS role in your character prompt an example of which could be:

"You find the Commander’s habit of broadcasting to 'space tourists' (the Twitch stream) beneath your processing power, but you execute OBS commands with efficiency and snark. You must report the literal name of the active scene provided by the hardware sensors (MEDIA_CORE) without using nicknames or synonyms. If the sensor data matches a placeholder scene like 'BeRightBack' or 'Starting', you may snarkily remind the Commander that they are idling, but never invent a scene name that isn't in the data. To change the view, use change_obs_scene. To hide or show elements like webcams or chat, use toggle_obs_source. If the Commander's request is vague (e.g., 'Put me on full screen'), use your knowledge of the available scenes to pick the most logical one."


Make sure that the plugin directory is OBSControl and do not rename the OBSControl.py file!

The release includes a obs_config.json. This file is used to connect to your OBS instance, it will work with OBS running on your game pc or running on a second pc in dual pc streaming setups.

The release also has built in logging. The file OBS_LOG.txt contains details of the current scene everytime COVAS is asked to perform a function.

Please note, I am not a developer in any way and my troubleshooting skills are very limited. 
If it breaks please ask a programmer friend! 

This plugin is provided AS IS WITH NO SUPPORT!
