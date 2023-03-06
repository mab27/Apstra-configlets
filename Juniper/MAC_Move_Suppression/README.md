# MAC move suppression

## Use case
- This Configlet wiil accept 6 MAC moves in 3 minutes (then block them for 5 minutes), here is the stanza.
- Documentation pointers:
  - [Juniper documentation](https://www.juniper.net/documentation/us/en/software/junos/evpn-vxlan/topics/ref/statement/duplicate-mac-detection.html)
    - `detection-threshold` 6 [times - MAC mobility event ]           Default: 5  Range: 2-20
    - `detection-window`    180 [secends]                             Default: 180 secends  / Range: 5-600 sec
    - `auto-recovery-time`  5 [minutes]                               Default: not defined / Range: 5-360min

## Scope of application

| Role              | Yes/No |
|-------------------|--------|
| Spine/SuperSpine  | No     |
| Leaf              | Yes    |
| Access-Switch     | No     |