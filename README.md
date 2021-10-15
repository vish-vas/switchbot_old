# switchbot_old

Forking and updating this [repo (cagnulein
/
switchbot_press)](https://github.com/cagnulein/switchbot_press) post HA 2021.10 release to restore the old switchbot plugin function where the entity would remember the state of the device in press mode.

A simple configuration could be:
```yaml
switch:
  - platform: switchbot_old
    name: deviceName
    mac: 'DD:A6:10:22:11:33'
    password: devicePassword

```
