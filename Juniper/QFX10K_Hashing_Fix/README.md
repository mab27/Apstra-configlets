# Fix for Hashing on QFX10002

## Use case
- On the juniper QFX10K series switches, Junos ignores port data when determining flows. To include port data in the flow determination you include the family inet statement at the `forwarding-options hash-key` hierarchy level. 
- - Documentation pointers:
  - [Juniper documentation](https://www.juniper.net/documentation/us/en/software/junos/sampling-forwarding-monitoring/topics/concept/policy-configuring-per-packet-load-balancing.html).

## Scope of application

| Role              | Yes/No |
|-------------------|--------|
| Spine/SuperSpine  | Yes    |
| Leaf              | Yes    |
| Access-Switch     | Yes    |