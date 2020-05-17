# Freebies
How to remove bloat apps from any Android / Samsung device

The following guide aims to assist you in removing unnecessary apps in your Android device and I set Samsung as an example.

Before you proceed you must understand that by using the following method it'll remove the app from your user folder in Android NOT your system folder, which means you can do factory reset to restore back all the apps.

Other than resetting your device to factory settings you can restore some of the apps by going to the Play Store and install it back check out the id in this link:

https://play.google.com/store/apps/details?id=com.facebook.orca

com.facebook.orca = Facebook messenger

Let's say you input the uninstall command:
pm uninstall -k --user 0 com.facebook.orca

But after a while you want it back, if it appears in the Play Store you can install it back and no harm's done BUT if you attempt to install this APK from a 3rd party link that won't work & you'll have to reset factory your device to get it back so know what you're doing!

I'll NOT be held responsible for any damages you may cause to your device so proceed with caution and read it all out to understand what you're doing!

How to remove bloat apps from any Samsung device:

1. Go to settings and tap on About Phone > Software Information > tap on Build Number 3 times to enable developer options 

In Developer Options enable USB debugging

2. Download adb:
https://developer.android.com/studio/releases/platform-tools#downloads

3. Plug in your device and on mac/windows drag the adb app to the terminal window but DON'T press enter yet!

These are the actions you can do:

shell (next to adb path name) 
Will enter your device and from there you can input uninstall commands

devices (next to adb path name) 
Will list your phone's name

pm list packages -f
Will list all the apps on your phone

4. Once you entered adb shell and see your device in the prompt line copy & paste to the terminal all of the following code to do the uninstalling automatically:

pm uninstall -k --user 0 com.facebook.appmanager
pm uninstall -k --user 0 com.facebook.system
pm uninstall -k --user 0 com.facebook.katana
pm uninstall -k --user 0 com.facebook.services

pm uninstall -k --user 0 com.microsoft.office.excel
pm uninstall -k --user 0 com.microsoft.office.powerpoint
pm uninstall -k --user 0 com.microsoft.office.word
pm uninstall -k --user 0 com.microsoft.skydrive
pm uninstall -k --user 0 com.skype.raider

pm uninstall -k --user 0 com.google.android.apps.docs
pm uninstall -k --user 0 com.google.android.tts
pm uninstall -k --user 0 com.google.android.apps.tachyon
pm uninstall -k --user 0 com.google.android.youtube
pm uninstall -k --user 0 com.google.android.marvin.talkback
pm uninstall -k --user 0 com.google.android.apps.books
pm uninstall -k --user 0 com.google.android.videos
pm uninstall -k --user 0 com.google.android.music
pm uninstall -k --user 0 com.google.android.webview
pm uninstall -k --user 0 com.google.android.apps.messaging

pm uninstall -k --user 0 com.samsung.privilege
pm uninstall -k --user 0 com.samsung.th.galaxyappcenter
pm uninstall -k --user 0 com.samsung.android.app.galaxyfinder
pm uninstall -k --user 0 com.samsung.android.app.notes
pm uninstall -k --user 0 flipboard.boxer.app
pm uninstall -k --user 0 com.samsung.android.slinkcloud
pm uninstall -k --user 0 com.rsupport.rs.activity.rsupport.aas2
pm uninstall -k --user 0 com.samsung.android.game.gametools
pm uninstall -k --user 0 com.samsung.android.weather
pm uninstall -k --user 0 com.monotype.android.font.cooljazz
pm uninstall -k --user 0 com.monotype.android.font.foundation
pm uninstall -k --user 0 com.monotype.android.font.rosemary
pm uninstall -k --user 0 com.monotype.android.font.chococooky
pm uninstall -k --user 0 com.sec.android.app.shealth
pm uninstall -k --user 0 com.samsung.android.spayfw
pm uninstall -k --user 0 com.samsung.android.spay
pm uninstall -k --user 0 com.samsung.playback
pm uninstall -k --user 0 com.samsung.android.calendar
pm uninstall -k --user 0 com.sec.android.app.popupcalculator
pm uninstall -k --user 0 com.sec.android.app.clockpackage
pm uninstall -k --user 0 com.samsung.knox.securefolder
pm uninstall -k --user 0 com.samsung.knox.securefolder.setuppage
pm uninstall -k --user 0 com.opera.max.oem
pm uninstall -k --user 0 com.opera.max.preinstall
pm uninstall -k --user 0 com.sec.android.app.sbrowser
pm uninstall -k --user 0 com.sec.android.widgetapp.samsungapps
pm uninstall -k --user 0 com.samsung.android.messaging
pm uninstall -k --user 0 com.samsung.android.weather
pm uninstall -k --user 0 com.samsung.android.scloud
pm uninstall -k --user 0 com.samsung.android.rubin.app
pm uninstall -k --user 0 com.dsi.ant.plugins.antplus
pm uninstall -k --user 0 com.dsi.ant.sample.acquirechannels
pm uninstall -k --user 0 com.dsi.ant.server
pm uninstall -k --user 0 com.dsi.ant.service.socket


--->>>> Optional apps to remove <<<<-----


Samsung galaxy gift:
pm uninstall -k --user 0 com.samsung.privilege

Install GBoard then remove samsung keyboard:
pm uninstall -k --user 0 com.sec.android.inputmethod

samung device maintenance:
pm uninstall -k --user 0  com.samsung.android.lool

Chrome browser:
pm uninstall -k --user 0 com.android.chrome

Google Assistant:
pm uninstall -k --user 0 com.google.android.googlequicksearchbox



--->>>> May break basic functions <<<<-----


pm uninstall -k --user 0 com.samsung.android.app.colorblind
pm uninstall -k --user 0 com.samsung.android.app.simplesharing
pm uninstall -k --user 0 com.samsung.android.app.soundpicker
pm uninstall -k --user 0 com.samsung.android.app.watchmanagerstub
pm uninstall -k --user 0 com.samsung.android.game.gamehome
pm uninstall -k --user 0 com.sec.android.widgetapp.webmanual
pm uninstall -k --user 0 com.sec.android.app.dictionary
pm uninstall -k --user 0 com.sec.android.app.voicenote
pm uninstall -k --user 0 com.samsung.android.allshare.service.fileshare
pm uninstall -k --user 0 com.samsung.android.allshare.service.mediashare
pm uninstall -k --user 0 com.samsung.android.providers.context
pm uninstall -k --user 0 com.samsung.android.smartcallprovider
pm uninstall -k --user 0 com.samsung.android.dhr
pm uninstall -k --user 0 com.samsung.aasaservice
pm uninstall -k --user 0 com.sec.enterprise.mdm.services.simpin
pm uninstall -k --user 0 com.samsung.android.beaconmanager
pm uninstall -k --user 0 com.samsung.ucs.agent.ese
pm uninstall -k --user 0 com.samsung.android.bbc.bbcagent
pm uninstall -k --user 0 com.samsung.android.voc
pm uninstall -k --user 0 com.samsung.android.sm.policy
pm uninstall -k --user 0 com.enhance.gameservice
pm uninstall -k --user 0 com.android.wallpaper.livepicker
pm uninstall -k --user 0 com.samsung.android.keyguardwallpaperupdator
pm uninstall -k --user 0 com.samsung.android.da.daagent
pm uninstall -k --user 0 com.samsung.knox.rcp.components
pm uninstall -k --user 0 com.sec.knox.switcher
pm uninstall -k --user 0 com.sec.enterprise.knox.cloudmdm.smdms
pm uninstall -k --user 0 com.sec.knox.knoxsetupwizardclient
pm uninstall -k --user 0 com.samsung.knox.appsupdateagent
pm uninstall -k --user 0 com.sec.knox.foldercontainer
pm uninstall -k --user 0 com.sec.android.app.billing
pm uninstall -k --user 0 com.samsung.android.email.provider
pm uninstall -k --user 0 om.sec.enterprise.knox.attestation
pm uninstall -k --user 0 com.sec.android.mimage.gear360editor
pm uninstall -k --user 0 com.samsung.android.sdk.professionalaudio.app.audioconnectionservice
pm uninstall -k --user 0 com.sec.android.service.health
pm uninstall -k --user 0 com.sec.android.app.wfdbroker
pm uninstall -k --user 0 com.sec.android.app.safetyassurance
 com.sec.android.mimage.photoretouching
pm uninstall -k --user 0 com.samsung.android.unifiedprofile
pm uninstall -k --user 0 com.sec.android.easyMover.Agent
pm uninstall -k --user 0 com.sec.location.nsflp2
pm uninstall -k --user 0 com.samsung.ucs.agent.boot
pm uninstall -k --user 0 com.sec.android.widgetapp.easymodecontactswidget
pm uninstall -k --user 0 com.sec.android.app.wlantest
pm uninstall -k --user 0 com.sec.android.AutoPreconfig
pm uninstall -k --user 0 com.sec.android.app.soundalive
pm uninstall -k --user 0 com.sec.android.provider.badge
pm uninstall -k --user 0 com.samsung.android.securitylogagent
pm uninstall -k --user 0 com.samsung.android.communicationservice
pm uninstall -k --user 0 com.samsung.hs20provider
pm uninstall -k --user 0 com.samsung.android.messaging
pm uninstall -k --user 0 com.samsung.android.location
pm uninstall -k --user 0 com.sec.bcservice
pm uninstall -k --user 0 com.sec.android.uibcvirtualsoftkey
pm uninstall -k --user 0 com.sec.knox.switcher
pm uninstall -k --user 0 com.samsung.android.svcagent
pm uninstall -k --user 0 com.sec.mldapchecker
pm uninstall -k --user 0 com.samsung.android.rlc
pm uninstall -k --user 0 com.sec.epdgtestapp
pm uninstall -k --user 0 com.sec.spp.push
pm uninstall -k --user 0 com.samsung.android.fmm
pm uninstall -k --user 0 com.samsung.android.mdm
pm uninstall -k --user 0 com.sec.android.app.SecSetupWizard
pm uninstall -k --user 0 com.samsung.android.video
pm uninstall -k --user 0 com.android.providers.partnerbookmarks
pm uninstall -k --user 0 com.android.bookmarkprovider
pm uninstall -k --user 0 com.samsung.android.sdk.professionalaudio.utility.jammonitor
pm uninstall -k --user 0 com.android.dreams.phototable
pm uninstall -k --user 0 com.android.providers.userdictionary
pm uninstall -k --user 0 com.samsung.app.newtrim
