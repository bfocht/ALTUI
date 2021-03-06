# ALTUI

Alternative user interface for MCV Vera Home Automation controllers
- More information: http://forum.micasaverde.com/index.php/topic,33309.0.html
- Installation: from MCV app store on http://apps.mios.com/plugin.php?id=8246

##Value Proposition
  - improves standard UI5 UI7 user experience
  - add new functionalities to VERA controllers
    - Workflows (logical state machines)
    - Device watches to trigger scene
    - Ability to construct custom user panels
    - Integration with Cloud Data storage to store variable history ( thingspeak, emoncms )
    - Integration with pushingbox notification
  - works with openLuup ( open source Vera-like controller ) 

##Features
- Skinnable, localized user interface
- display and act on devices
- display all devices variables and UPNP actions
- display and act on scenes, ability to trigger scenes based on device variable changes
- display device variable history
- Ability to create custom user pages with widgets, drag and drop editor
- Ability to create Logical State Machines (workflows) to create complex sequence of home automation actions
- Various backend control features ( debug log )
- Remote access possible via the remote access servers ( MMS ) of Vera using the same credentials
- Automatic detection and update to new versions ( only for registered users )
- Multicontroller mode ( can work with several VERAs and display all in one user interface )
- graphical representation of your network/ routes
 
##Licensing
- open source for personal use
- optional registration & licensing fee ( 2 € per month ), order from within the application, available as 6m, 1y and 2y package
- commercial resseling requires a commercial contract with the author , amg0

##Backend Home Automation Controllers
ALTUI works with the following backend home automation controllers
- openLuup : OpenLuup is an opensource, Lua based, Vera like controller which runs most of the VERA plugins. More information here: https://github.com/akbooer/openLuup
- MCV Vera3, Vera Lite, Vera Edge, Vera Plus : http://getvera.com/
