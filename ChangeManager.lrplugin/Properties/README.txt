DefaultProperties.lua will be copied to {Lightroom-app-data}/com.robcole.Shared/Properties.lua if it does not yet exist, and if shared properties are accesed by this plugin.
Once copied there, or before for that matter, you can edit to your hearts content - it will never be overwritten without your permission.
I recommend comparing new versions in plugins (Properties folder) to what you're already running (in com.robcole.Shared folder), and consider a manual synchronization of worthwhile enhancements.
It contains properties which may be shared by multiple plugins.
This plugin (ChangeManager) uses shared properties to determine if photo is finished editing, and is consequently eligible for locking.
Said function is also used by Exportant to determine export eligibility.

Example Lightroom-app-data folder: C:\Users\{username}\AppData\Roaming\Adobe\Lightroom