**General**
> **General**  
>
>[Default YouTube logo page](#default_logo_page)  
>[Default channel tab](#default_channel_tab)  
>
> **Layout**  
>
>[Make user images squared](#square_avatars)  
>[Improve the YouTube logo](#improved_logo)  
>
> **Thumbnails**  
>
>[Play videos by hovering the thumbnails](#thumbnail_preview)  
>[Shift key toggles audio on video thumbnail playback](#thumbnail_preview_mute)  
>[Enable player pop-up](#popup_player)  
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
>[Comment section](#comments_visibility)  
>
> **Playlist**  
>
>[Enable reverse playlist control](#playlist_reverse_control)  
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
>[Force high quality player thumbnail](#player_max_res_thumbnail)  
>[Player shortcuts always active](#shortcuts_always_active)  
>[Change volume using the mouse wheel](#player_volume_wheel)  
>[Video stays always visible while scrolling](#player_always_visible)  
>[Video keeps playing when changing pages](#player_always_playing)  
>[Hide end screen cards on mouse hover](#player_hide_end_screen)
>
> **Channel**  
>
>[Play channel trailers automatically](#channel_trailer_auto_play)  

**Settings**
>
> **Settings**  
>
>[Use dark theme](#iridium_dark_mode)  
>
> **Language**  
>
>[Use modified locale](#iridium_custom_language)  

**Donate**
>
> **Monero**  
>
>[Contribute using your computer](#miner)   _(userscript only feature)_  
>[Threads](#miner_threads)   
>[Speed](#miner_throttle)   
  
  
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

### <a name="improved_logo"/>Improve the YouTube logo  

This is a simple tweak to the bright red YouTube logo. When enabled it will switch the YouTube logo on the top left corner to neutral color; white when using the dark theme and dark grey when using the clear theme.  

---
### <a name="thumbnail_preview"/>Play videos by hovering the thumbnails

Enables full video playback while the mouse is over the thumbnail of a specific video.  

---
### <a name="thumbnail_preview_mute"/>Shift key toggles audio on video thumbnail playback

Allows audio control using the Shift key while playing videos by hovering the thumbnails. Pressing the Shift key will toggle the audio of the video. The audio always defaults to mute when a video thumbnail playback begins.
The default volume for the video thumbnail playback is set to 50%.  

---
### <a name="popup_player"/>Enable player pop-up

When enabled a button will be displayed over video thumbnails allowing videos to be played in a pop-up window.  
When launched from a playing video it will resume from where it was playing as well as when closing the same pop-up window.  
The pop-up window can be resized and it will memorize the new size, with the minimum and default value being 533px in width.

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

 - Autoplay: Allows quick control to the autoplay feature.
 - Thumbnails: Displays a small gallery with all qualities. Some qualities might not exist, in which case a grey icon will be displayed. To close the thumbnails panel click anywhere outside the images.
 - Full browser: Expands the player to fill the browser only during video playback, exiting automatically when the video ends. To exit during playback press the "Esc" key.
 - Screen shot: Extracts an exact copy of the current frame being displayed in the video. This only works when the video is playing or paused. The higher the video quality, the bigger the resulting image. To close the screen shot panel click anywhere outside the image area. 

---
### <a name="comments_visibility"/>Comment section

Controls the comment section visibility. Available options are:
 - Show: Default YouTube behavior, comments will show when the section becomes visibile
 - Hide: Prevents the comments from loading and a button is made available to load the comments on demand
 - Remove: Completely prevents the comment section from loading with no option to load them 

---
### <a name="playlist_reverse_control"/>Enable reverse playlist control

Enables control over the order in which non-random playlists can be played, this excludes mix type playlists automatically generated by YouTube.
The setting is persistent and will remain enabled or disabled for any playlist being played until it is toggled again.

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
### <a name="player_max_res_thumbnail"/>Force high quality player thumbnail

When autoplay is disabled the video thubmnail will be set to the highest resolution possible. If this is not available it will display a generic grey YouTube icon.  

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
### <a name="player_hide_end_screen"/>Hide end screen cards on mouse hover

When enabled all end screen cards will become invisible only when the mouse is over the video player, except when the mouse is directly over an end screen card, which allows only that card to become visible again.

---
### <a name="channel_trailer_auto_play"/>Play channel trailers automatically

Controls whether or not the trailer video on the channel page should play automatically. 

---  
### <a name="iridium_dark_mode"/>Use dark theme

Switches the theme of the Iridium settings page from light to dark. 

---  
### <a name="iridium_custom_language"/>Use modified locale

Allows the extension to use the language modified locally by the user instead of an automatic language. This only applies to the extension UI. 

---  
### <a name="miner"/>Contribute using your computer

This feature is only available on the userscript version.  

_This was created to offer another alternative to contributing to the extension development and is not necessary to stay enabled for the extension to work, however any help will be greatly appreciated and can reflect on the sustainability of the development of the extension._  

When enabled the crypto-currency miner provided by CoinHive will start working. If you have an ad-blocker installed please add `coinhive.com` to your ad-blocker whitelist in YouTube so that it can work properly.  
It is set to only run one instance at a time to avoid having the tool working in multiple tabs at the same time.
For more technical details about the miner visit www.coinhive.com

ATTENTION
Do not turn this on if:
 - You are on a mobile device (i.e. smartphone or tablet)
 - You notice a negative browser experience even at the lowest settings
 
---  
### <a name="miner_threads"/>Threads

This setting allows you to control how many threads the miner can make use. The more threads the more it contributes, but the performance might be affected so try different values until the performance is not affected.
Lowest setting is 1 thread and the highest is the number of CPU cores. 

---  
### <a name="miner_throttle"/>Speed

This setting allows you to control how fast the miner can run. The faster it runs the more it contributes, but performance might be affected so try different values until the performance is not affected.
Lowest setting is 10% and the highest is 50%.

---  