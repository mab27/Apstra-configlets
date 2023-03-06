# Port Mirroring

## Use case
- Select an ingress and egress interfaces and ask for port mirroring of the traffic towards either anther interface on the switch (Local miroring) or an ip address (remote mirroring).
- Leverage the Property-Sets to define the intent in terms of ingress/egress interfaces and type of mirroring. 
- Documentation pointers:
  - [Juniper documentation](https://www.juniper.net/documentation/us/en/software/junos/network-mgmt/topics/topic-map/port-mirroring-local-and-remote-analysis.html#id-configuring-port-mirroring-s).


## Scope of application

| Role              | Yes/No |
|-------------------|--------|
| Spine/SuperSpine  | Yes    |
| Leaf              | Yes    |
| Access-Switch     | Yes    |
