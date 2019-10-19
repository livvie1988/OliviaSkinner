**The feature list for versions prior to 1.0.0 can be found in the [archive page](https://github.com/ParticleCore/Iridium/wiki/Features-archive)**

---


**General**  
>
>[Dark theme](#darkTheme)  
>[Quick controls](#quickControls)  

**Player**  
>
>[Play videos automatically](#autoPlayVideo)  
>[Force max thumbnail resolution](#maxResThumbnail)  
>[Allow HFR (60fps)](#hfrOn)  

**Download**  
>
>Coming soon    

**Channels**  
>
>Coming soon 

**Blacklist**  
>
>Coming soon   

**Settings**  
>
>[Sync settings](#syncSettings)  
>[Show settings button in YouTube](#iridiumLogo)  
  
  
---
### <a name="darkTheme"/>Dark theme
###### added in 1.0.0  

Forces the dark theme state to either enabled or disabled.  
Changes are propagated live throughout any opened YouTube pages.  

---
### <a name="quickControls"/>Quick controls
###### added in 1.2.0  

Displays a set of quick controls below the video player to quickly toggle the respective option.  
At the moment only [Play videos automatically](#autoPlayVideo) is available in the quick controls  
The video page must refresh for the change to take effect if this setting was modified while a video page was already loaded.  

---
### <a name="autoPlayVideo"/>Play videos automatically
###### added in 1.0.0

Allows the automatic video playback in the video and channel page to be enabled or disabled.  
This setting is not related with YouTube's _Auto Play Next Video_ feature.  

---
### <a name="maxResThumbnail"/>Force max thumbnail resolution
###### added in 1.0.0

The max thumbnail resolution will be displayed when the [Play videos automatically](#autoPlayVideo) is turned off.  
Some videos might not have a max thumbnail resolution available, in which case the default thumbnail will be used.  

---
### <a name="hfrOn"/>Allow HFR (60fps)  
###### added in 1.1.0

Controls whether or not videos with HFR (High Frame Rate - 30+fps) streams should be available in the player quality selection list.  
The video must restart for the change to take effect if this setting was modified while a video was already loaded.  

---
### <a name="syncSettings"/>Sync settings  
###### added in 1.2.3

Allows the extension to save its settings either locally ( only the current browser has these settings ) or synced ( extension settings will be shared across Firefox browsers where the user is signed in and has "Sync addons" enabled in its Firefox account preferences ).  

---
### <a name="iridiumLogo"/>Show settings button in YouTube   
###### added in 1.2.3

Places a button on the top right corner of the YouTube web pages that opens the extension settings for users with minimalist browser setups that might not show the toolbar or users that don't want another button on their toolbar.  

---