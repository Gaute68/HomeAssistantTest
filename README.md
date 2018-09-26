<h1 align="center">
  Home Assistant Config by Gaute68 - originally by ntalekt
</h1>


#### Platform
* Hardware
  * [Raspberry PI 3 Model B](https://www.amazon.com/gp/product/B01CD5VC92/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B01CD5VC92&linkCode=as2&tag=ntalekt0c-20&linkId=a47341c555e64a096e2d9eb9af323626)
  * [SanDisk Ultra 32GB microSDHC](https://www.amazon.com/gp/product/B073JWXGNT/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B073JWXGNT&linkCode=as2&tag=ntalekt0c-20&linkId=efa468860daf18e843eadc5ee34729c7)
  * [Aeotec Z-Stick Gen5](https://www.amazon.com/gp/product/B00X0AWA6E/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B00X0AWA6E&linkCode=as2&tag=ntalekt0c-20&linkId=04f4c7bf8438a9dee6e4e2ad273405d0)
* Software
  * [Home Assistant Hassbian v1.31 (Python 3.5.3)](https://www.home-assistant.io/docs/installation/hassbian/installation/)
    * Home Assistant Version: 0.78.3
  * [NGNIX proxy](https://home-assistant.io/docs/ecosystem/nginx/)
  * SSL via [SSLs](https://www.ssls.com/)

## Devices

#### Lighting


#### Sensor / Switch

* [Multisensor](https://github.com/bruhautomation/ESP-MQTT-JSON-Multisensor)


#### Camera
* [TBA](https://www.amazon.com/gp/product/B01I01Z1M2/ref=as_li_tl?

#### Media
* [Google Assistant](https://www.amazon.com/gp/product/B01DFKC2SO/ref=as_li_tl?)
* [Sonos TBA](https://www.amazon.com/gp/product/B00EWCUK1Q/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B00EWCUK1Q&linkCode=as2&tag=ntalekt0c-20&linkId=b90ba9470832833ea363027daabf948a) x3


#### Network
* [Asus router](https://www.amazon.com/gp/product/B0192911RA/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B0192911RA&linkCode=as2&tag=ntalekt0c-20&linkId=bf3232d8d723b45e0c75a0f6455f9ad0)

* [Aeotec Z-Stick Gen5](https://www.amazon.com/gp/product/B00X0AWA6E/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B00X0AWA6E&linkCode=as2&tag=ntalekt0c-20&linkId=04f4c7bf8438a9dee6e4e2ad273405d0)

#### Location
* [Life360 Location Tracking App](https://www.life360.com/)

## Automations
### Notification Audio
* [TTS](https://home-assistant.io/components/tts.google/) notification when _User_ arrives at specific [Zones](https://home-assistant.io/components/zone/).
* [TTS](https://home-assistant.io/components/tts.google/) notification when _User_ leaves specific zones which includes travel time home.
* [TTS](https://home-assistant.io/components/tts.google/) notification if the door has been open for 30 minutes with no motion in kitchen.
* [TTS](https://home-assistant.io/components/tts.google/) test notification

### Notification Text
* [Pushbullet](https://home-assistant.io/components/notify.pushbullet/) notification when new Home Assistant version is available on PyPI.
* [Pushbullet](https://home-assistant.io/components/notify.pushbullet/) notification when [Nest thermostats](https://www.amazon.com/gp/product/B0131RG6VK/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B0131RG6VK&linkCode=as2&tag=ntalekt0c-20&linkId=07e1a8fdb9abf017c692614b74df561d) go into Home/Away modes.
* [Pushbullet](https://home-assistant.io/components/notify.pushbullet/) notification when critical network devices go offline.
* [Pushbullet](https://home-assistant.io/components/notify.pushbullet/) notification if the garage door is left open after we left the house.
* [Pushbullet](https://home-assistant.io/components/notify.pushbullet/) notification if the garage door is opened and no one is home.
* [Pushbullet](https://home-assistant.io/components/notify.pushbullet/) notification if the garage door has been open for 30 minutes with no motion in garage.
* [Pushbullet](https://home-assistant.io/components/notify.pushbullet/) notification test.
* [Pushbullet](https://home-assistant.io/components/notify.pushbullet/) when SSL certificate expiration sensor <= 10 days.
* [Pushbullet](https://home-assistant.io/components/notify.pushbullet/) when any battery sensor falls below 20%
* [Pushbullet](https://home-assistant.io/components/notify.pushbullet/) for a failed login attempt.
* [Pushbullet](https://home-assistant.io/components/notify.pushbullet/) if new network device is detected.

### Notification Visual


### Lights
* Exterior lights ([GE Z-Wave Plus Dimmer 14294](https://www.amazon.com/gp/product/B01MUCZA1C/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B01MUCZA1C&linkCode=as2&tag=ntalekt0c-20&linkId=0dfbcad4a9df3b81570623f0e23b562a)) on 5 minutes before sunset.
* Exterior lights ([GE Z-Wave Plus Dimmer 14294](https://www.amazon.com/gp/product/B01MUCZA1C/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B01MUCZA1C&linkCode=as2&tag=ntalekt0c-20&linkId=0dfbcad4a9df3b81570623f0e23b562a)) off 30 minutes after sunrise.
* Holiday interior lighting leveraging [Google Calendar Event](https://home-assistant.io/components/calendar.google/) to define the holiday.
* Holiday interior lighting using [Amazon Echo Dot](https://www.amazon.com/gp/product/B01DFKC2SO/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B01DFKC2SO&linkCode=as2&tag=ntalekt0c-20&linkId=bb902528d5689ae4e1163dd31b7c646d) via [Emulated Hue Bridge](https://home-assistant.io/components/emulated_hue/).


### Doorbell
* Exterior lights to 100% if [Ring Pro Doorbell](https://www.amazon.com/gp/product/B01DM6BDA4/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B01DM6BDA4&linkCode=as2&tag=ntalekt0c-20&linkId=5faec88af320aeb157fbb45fa954efc3) detects motion or is pressed after 9:00pm.
* Exterior lights back to 35% after 30 minutes after doorbell motion or press.

### Media
* Turn on SleepTime mode if [Xiaomi Aqara Smart Wireless Switch](https://www.gearbest.com/access-control/pp_626695.html) is pressed.
* Pause [Deluge](https://home-assistant.io/components/switch.deluge/) if internet data usage > 90%.

### Sonos
* Reset/Regroup all [Sonos PLAY:1](https://www.amazon.com/gp/product/B00EWCUK1Q/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B00EWCUK1Q&linkCode=as2&tag=ntalekt0c-20&linkId=b90ba9470832833ea363027daabf948a) speakers at 6:00am every morning.
* Group all Sonos' button.

### Occupancy
* If motion is detected via [BRUH Automation multisensor](https://github.com/bruhautomation/ESP-MQTT-JSON-Multisensor) or [Amcrest  cameras](https://www.amazon.com/gp/product/B077DPWQCV/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B077DPWQCV&linkCode=as2&tag=ntalekt0c-20&linkId=ac62ed590e7bb7ab3e4aca12348c1db1) turn on `input_boolean` (used in `binary_sensor` for occupancy tracking).
* If no motion is detected after certain period of time turn off `input_boolean`.

### Sleep time
* Turn off master TV after 30 minutes via [Harmony Hub](https://www.amazon.com/gp/product/B00BQ5RYI4/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B00BQ5RYI4&linkCode=as2&tag=ntalekt0c-20&linkId=ef1edfe63776ff2e3b5b4e7fdf8e3488).

### System

* Clean the TTS cache weekly.

### Vacation/Climate
* Turn vacation mode on when household is gone for 24 hours.
* Put [Nest Thermostats](https://www.amazon.com/gp/product/B0131RG6VK/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B0131RG6VK&linkCode=as2&tag=ntalekt0c-20&linkId=07e1a8fdb9abf017c692614b74df561d) in away mode when vacation mode active.


## Scripts/Customizations
* Life360 integration via shell mqtt broker found [here](https://community.home-assistant.io/t/life-360-support/1690)
 Using the [SQL Sensor](https://home-assistant.io/components/sensor.sql/) now.

* WAN test script found [here](https://community.home-assistant.io/t/wan-test-script-quick-and-dirty/30699)

# Interface
![UI](images/home-screenshot.jpg)


# Grafana Monitoring Front-end
![UI](images/homeassistant_grafana.jpg)
