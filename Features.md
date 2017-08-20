**General**
> **General**  
>
>[Default YouTube logo page](#default_logo_page)  
>[Default channel tab](#default_channel_tab)  
>
> **Layout**  
>
>[Make user images squared](#square_avatars)  
>
> **Thumbnails**  
>
>[Play videos by hovering the thumbnails](#thumbnail_preview)  
>[Shift key toggles audio on video thumbnail playback](#thumbnail_preview_mute)  
>
> **Blacklist**  
>
>[Enable blacklist](#enable_blacklist)  

**Video**
> **General**  
>
>[Display uploaded videos number](#channel_video_count)  
>[Display how long the video was uploaded](#channel_video_time)  
>[Enable quick controls](#player_quick_controls)  
>
> **Player**  
>
>[Default video quality](#player_quality)  
>[Play videos automatically](#player_auto_play)  
>[Allow annotations on videos](#player_annotations)  
>[Allow subtitles on videos](#player_subtitles)  
>[Allow loudness normalization](#player_loudness)  
>[Allow ads on videos](#player_ads)  
>[Allow ads only on videos of subscribed channels](#subscribed_channel_player_ads)  
>[Allow HFR (60fps) streams](#player_hfr)  
>[Memorize player size](#player_memorize_size)  
>[Memorize player volume](#player_memorize_volume)  
>[Player shortcuts always active](#shortcuts_always_active)  
>[Change volume using the mouse wheel](#player_volume_wheel)  
>[Video stays always visible while scrolling](#player_always_visible)  
>[Video keeps playing when changing pages](#player_always_playing)
>
> **Channel**  
>
>[Play channel trailers automatically](#channel_trailer_auto_play)  

**Settings**
>
> **Settings**  
>
>[Use dark theme](#iridium_dark_mode)  
  
  
---
### <a name="default_logo_page"/>Default YouTube logo page

Defines which page to go to when clicking on the YouTube logo located on the top left corner.  

---
### <a name="default_channel_tab"/>Default channel tab

Defines which channel tab to load when clicking on a channel link or user link.  

---
### <a name="square_avatars"/>Make user images squared

Removes the circle style forced around the user and channel images which hides the corner of the images.  

---
### <a name="thumbnail_preview"/>Play videos by hovering the thumbnails

Enables full video playback while the mouse is over the thumbnail of a specific video.  

---
### <a name="thumbnail_preview_mute"/>Shift key toggles audio on video thumbnail playback

Allows audio control using the Shift key while playing videos by hovering the thumbnails. Pressing the Shift key will toggle the audio of the video. The audio always defaults to mute when a video thumbnail playback begins.
The default volume for the video thumbnail playback is set to 50%.  

---
### <a name="enable_blacklist"/>Enable blacklist

Blocks all videos from a channel on main pages, with the exception of Subscriptions and Channel pages. When enabled a cross button will become available on the video thumbnails, pressing it will automatically add the channel of that video to the blacklist and remove any videos belonging to that channel.  
It is possible to remove channels individually via the "Edit" button located below the setting.  

---
### <a name="channel_video_count"/>Display uploaded videos number

Displays the total number of uploaded videos in front of the video author name. This also links directly to the list of videos of that channel.  

---
### <a name="channel_video_time"/>Display how long the video was uploaded

Displays in front of the published date how long ago the video has been uploaded. 

---
### <a name="player_quick_controls"/>Enable quick controls

Displays a section containing quick controls. This section is located above the video description and is closed by default. Opening it will reveal a list of options to interact with:

 - Autoplay: Allows quick control to the autoplay feature
 - Thumbnails: Displays a small gallery with all qualities. Some qualities might not exist, in which case a grey icon will be displayed
 - Full browser: Expands the player to fill the browser only during video playback, exiting automatically when the video ends. To exit during playback press the "Esc" key.
 - Screen shot (not working yet) 

---
### <a name="player_quality"/>Default video quality

Sets which quality the video player should play. If the quality does not exist it will select the one closest to it.  

_Notice: Due to a bug in the YouTube video player that is yet to be fixed by the YouTube team, the quality option might appear empty when the selected quality does not exist, however the closest quality is being selected correctly._

---
### <a name="player_auto_play"/>Play videos automatically

Controls whether or not videos on the video page should play automatically. 

---
### <a name="player_annotations"/>Allow annotations on videos

Controls whether or not annotations can be displayed on the video. 

---
### <a name="player_subtitles"/>Allow subtitles on videos

Controls whether or not subtitles can be displayed on the video. 

---
### <a name="player_loudness"/>Allow loudness normalization

YouTube provides loudness normalization on the client side, but this does not work well most of the time resulting in plenty of videos playing too low to enjoy. With this option disabled the videos will play at the volume the video author intended to play.  

---
### <a name="player_ads"/>Allow ads on videos

Controls whether or not ads can be displayed on the video page. 

---
### <a name="subscribed_channel_player_ads"/>Allow ads only on videos of subscribed channels

Controls whether or not ads can be displayed only on videos from subscribed channels. 

_Notice: This option overrides the option [Allow ads on videos](#player_ads)_

---
### <a name="player_hfr"/>Allow HFR (60fps) streams

Controls whether or not videos can play HFR (High Frame Rate) streams when available.

_Notice: There might be cases when disabling HFR streams might not be possible due to YouTube not offering the equivalent quality streams. If such is the case the HFR streams will not be disabled for that video_


---
### <a name="player_memorize_size"/>Memorize player size

The extension will remember the last player size the user changed to and enforce that size when YouTube tries to reset it.  

---
### <a name="player_memorize_volume"/>Memorize player volume

The extension will remember the last player volume the user changed to and restore that volume when YouTube tries to reset it.  

---
### <a name="shortcuts_always_active"/>Player shortcuts always active

Allows control over the video player shortcuts from anywhere on the page which would otherwise require the player to be active or selected in order to work.

For a complete list of global and local YouTube shortcuts go to the following link: [YouTube shortcuts](https://github.com/ParticleCore/Iridium/wiki/YouTube-shortcuts)

---
### <a name="player_volume_wheel"/>Change volume using the mouse wheel

When enabled the volume of the video can be controlled using the mouse wheel while the mouse cursor is over the video player. By default the volume changes up and down by 5%.

---
### <a name="player_always_visible"/>Video stays always visible while scrolling

When enabled the player will minimize into the bottom right corner of the screen once the original position is less than half visible. The player will restore it's size and position when more the original position is more than half visible.

_Notice: For the moment the size and position of the mini player cannot be changed, but it will be possible in future versions of the extension._

---
### <a name="player_always_playing"/>Video keeps playing when changing pages

When enabled the player will minimize into the bottom right corner of the screen and keep playing while navigating to different pages. Two buttons located at the top are available in this mode that allows the return to the original video page or close the mini player.

_Notice: For the moment the size and position of the mini player cannot be changed, but it will be possible in future versions of the extension._

---
### <a name="channel_trailer_auto_play"/>Play channel trailers automatically

Controls whether or not the trailer video on the channel page should play automatically. 

---
### <a name="iridium_dark_mode"/>Use dark theme

Switches the theme of the Iridium settings page from light to dark. 

---