# Control plane protection filter against DDoS for VxLAN

## Use case
- Implemeting a control plane protection filter to defend against DDoS for VxLAN interfaces. According to Juniper's the default value should be set at `300` with a busrt value at `10`.
- Documentation pointers:
  - [Juniper documentation](https://www.juniper.net/documentation/us/en/software/junos/security-services/topics/example/ddos-example-qfx-series.html).
  - [Juniper documentation - Security Services Administration Guide](https://www.juniper.net/documentation/us/en/software/junos/security-services/topics/ref/statement/protocols-edit-ddos-qfx-series.html).

## Scope of application

| Role              | Yes/No |
|-------------------|--------|
| Spine/SuperSpine  | Yes    |
| Leaf              | Yes    |
| Access-Switch     | Yes    |