## 0.1.0
- Improved state icon and switch to a shield
- Allow for custom list of armed button state (based on what your alarm supports)

```yaml
- type: custom:alarm_control_panel-card
  entity: alarm_control_panel.ha_alarm
  title: My Alarm
  states:
    - arm_home
    - arm_away
    - arm_custom_bypass
```

## 0.0.3
Fixed buttons disabled for alarms with no codes and a few other cases

## 0.0.2
Fixed triggered state to display properly

## 0.0.1
Initial release that supports versioning