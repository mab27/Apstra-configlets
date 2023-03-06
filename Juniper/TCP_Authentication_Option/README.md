# TCP Authentication Option (TCP-AO)

## Use case
- The concept is to replace TCP-MD5 auth on BGP sessions with TCP-AO. TCP-AO supports multiple keys *up to 64* and time based key rollover. The benefit is that you could set up multiple keys for a single connection and as a new key start date becomes active the keys will rollover to the next key therefore keeping your keys fresh.
- Documentation pointers:
  - [Juniper documentation](https://www.juniper.net/documentation/us/en/software/junos/transport-ip/topics/topic-map/tcp-configure-ao-bgp-ldp.html). 
  - [RFC5925](https://datatracker.ietf.org/doc/html/rfc5925).
  - [APNIC article](https://blog.apnic.net/2021/07/28/its-time-to-replace-md5-with-tcp-ao/).

## Scope of application

| Role              | Yes/No |
|-------------------|--------|
| Spine/SuperSpine  | Yes    |
| Leaf              | Yes    |
| Access-Switch     | Yes    |