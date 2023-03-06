# Disable unused interfaces

## Use case
- This configlet updates the duplicate MAC detection timers for EVPN and is required when instantiating IBA probe `EVPN Host flapping` due to known issue [AOS-29762] Junos Suppressed MAC Stays as Duplicate Forever Until Manually Cleared.
- Documentation pointers:
  - [Juniper documentation](https://www.juniper.net/documentation/us/en/software/junos/evpn-vxlan/topics/task/configuring-mac-mobility-settings.html)

## Scope of application

| Role              | Yes/No |
|-------------------|--------|
| Spine/SuperSpine  | No     |
| Leaf              | Yes    |
| Access-Switch     | Yes    |