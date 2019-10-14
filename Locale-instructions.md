If you are interested in contributing to the locale files follow these instructions. Failure to do so will result in rejection.

---

### Creating a new locale from scratch

 - The file name must be `messages.json` in a folder with the following format `xx_XX` where `xx_XX` is the respective locale code, for example `en_US`.  
 - The respective locale code for the language you are translating must be exactly the same as the one being used by YouTube.  
 - To find which code YouTube is using for the language file follow these steps:  
   - Open YouTube  
   - Change to the respective language if it isn't already selected
   - Open your browser console
   - Enter the following code `yt.config_.GAPI_LOCALE` or `yt.config_.PLAYER_JS_URL.match(/[a-z]{2}_[A-Z]{2}/g)[0]`
   - You should get a string with the following format `xx_XX`. For example, if you have selected the `English (US)` language then the console will show the locale code `en_US`  
 - When translating the labels avoid translating names and identifiers. For example `Iridium settings` should keep `Iridium` intact because this is the name of the extension and `HFR (60fps)` should be kept intact because this is an identifier.  
 - The `message` value inside `locale-id` must be exactly the same as the language name present in YouTube in its original form. If the language is `Russian` then the `message` value has to be `Русский`. 
 - Keep the current spacing format. The extra spaces are present to make maintenance and readability easier.  

---

### Merge request  
 - Descriptions are not required to be filled in

---

### Additional note  
 - **Do not include feature descriptions in the labels**. Each feature is already linked to a detailed explanation available in the wiki. **The labels should be as short as possible** with enough information necessary for basic understanding. If users do not find that information sufficient they can click on the wiki link and read about the feature in more detail.
  

You can find all the locales currently available here: https://github.com/ParticleCore/Iridium/tree/master/src/_locales/

I always try to credit everyone that has contributed to the locales here: https://github.com/ParticleCore/Iridium/wiki

