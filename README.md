# HA-Roller

## my personal forked version:


- Version with a lot weaker ULN2003 stepper:
    - or with a bit stronger drop-in replacement of Toshiba TBD62003A (worked enough for me)
        - https://toshiba.semicon-storage.com/info/datasheet_en_20150724.pdf?did=29886
- One ESP is controlling 2 steppers with the help of the ESPHome Packages
- be careful with the PIN bindings, this was working on one dev board and not in another
    - needs more testing from my side


Motorized blinds extremely cheap (IKEA Fridans)

all information is at: https://www.thingiverse.com/thing:4889111

![Optional PCB](https://github.com/R34LiAM/HA-Roller/blob/main/pcb/PCB.png?raw=true)
![Home Assistant](https://github.com/R34LiAM/HA-Roller/blob/main/pcb/HA.png?raw=true)


Integrates with:

+ Home Assistant through ESPHome integration.

+ MQTT (HomeKit/HomeBridge and more).

+ HTTP Requests/REST API.

+ Standalone w/o home automation integration.

+ plus more


Should integrate with pretty much anything...


https://www.thingiverse.com/thing:4889111

