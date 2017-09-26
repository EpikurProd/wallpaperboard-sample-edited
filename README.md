# Wallpaperboard-Sample Template (With Ads)

WallpaperBoard Library : https://github.com/danimahardhika/wallpaperboard

# Intstructions
Please follow this wiki : https://github.com/danimahardhika/wallpaperboard/wiki and for ads, use my sample template instead.

- After following the wiki and setting up your template, go to "dashboard_configurations.xml"
- Scroll down to line #44 (below "Allow to download wallpaper")
- Change "ca-app-pub-xxxxxxxxxxxxxxxx/xxxxxxxxxx" with your own ad unit

# Example 

From this
```
 <string name="admob_interstitial_id">ca-app-pub-xxxxxxxxxxxxxxxx/xxxxxxxxxx</string>
 ```
 to this
  ```
 <string name="admob_interstitial_id">ca-app-pub-8026912587060543/3365247488</string>
 ```
 
 # More info
 
The following template only supports Interstitial Ads as of now and banner ads will be implemneted in future but that requires me to work on library itself.

Ads will be invoked at :
- After splash screen and loading all wallpapers 
- Switching between black/white theme 

More support will be added in future.
Feel free to fork and apply your changes.
