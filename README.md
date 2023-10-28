# quest-services-doc
Unofficial Meta com.oculus.* packages DOCs

# getting a list of com.oculous services

```
➜  ~ adb shell 'pm list packages | grep "com.oculus"

package:com.oculus.assetdelivery
package:com.oculus.avatareditor
package:com.oculus.updater
package:com.oculus.statscollector
package:com.oculus.systemdriver
package:com.oculus.websafety
package:com.oculus.captionservice
package:com.oculus.preshutdowntaskservice
package:com.oculus.browser
package:com.oculus.os.vrlockscreen
package:com.oculus.cvp
package:com.oculus.accountscenter
package:com.oculus.identitymanagement.service
package:com.oculus.vrshell.desktop
package:com.oculus.integrity
package:com.oculus.vrshell
package:com.oculus.os.vrusb
package:com.oculus.metacam
package:com.oculus.extrapermissions
package:com.oculus.horizon
package:com.oculus.systemutilities
package:com.oculus.deviceauthserver
package:com.oculus.firsttimenux
package:com.oculus.os.cm
package:com.oculus.store
package:com.oculus.linefrequencyservice
package:com.oculus.bugreportuploader
package:com.oculus.xrstreamingclient
package:com.oculus.socialplatform
package:com.oculus.qplservice
package:com.oculus.assistant
package:com.oculus.notification_proxy
package:com.oculus.systemresource
package:com.oculus.companion.server
package:com.oculus.backuptransportservice
package:com.oculus.MiramarSetupRetail
package:com.oculus.systempermissions
package:com.oculus.os.qrcodereader
package:com.oculus.vrcast
package:com.oculus.systemux
package:com.oculus.samples.firsthand
package:com.oculus.nux.ota
package:com.oculus.fitnesstracker
package:com.oculus.remotedesktop
package:com.oculus.q4bservice
package:com.oculus.bugreportservice
package:com.oculus.guidebook
package:com.oculus.gatekeeperservice
package:com.oculus.os.chargecontrol
package:com.oculus.os.clearactivity
package:com.oculus.ocms
package:com.oculus.yadi
package:com.oculus.appsafety
package:com.oculus.bodyapiservice
package:com.oculus.systemactivities
package:com.oculus.tv
package:com.oculus.userserver2
package:com.oculus.guardianresources
package:com.oculus.guardian
package:com.oculus.gamingactivity
package:com.oculus.explore
package:com.oculus.presence
package:com.oculus.helpcenter
package:com.oculus.externalstorage
package:com.oculus.preloader
package:com.oculus.maintenanceboot
package:com.oculus.micservice
package:com.oculus.mobile_mrc_setup
package:com.oculus.vralertservice
package:com.oculus.shellenv
```

# package:com.oculus.shellenv

```
➜  ~ adb shell dumpsys package com.oculus.shellenv | grep -i activity 
Activity Resolver Table:
        9da11eb com.oculus.shellenv/.ShellEnvActivity filter 9cacde1
        9da11eb com.oculus.shellenv/.ShellEnvActivity filter a116b48
```
