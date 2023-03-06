# BGP Graceful Restart

## Use case
- Add Grarceful Restart on the default VRF and the non-default VRF.
- Caution: Applying this configlet will cause BGP and BFD sessions to flap.

## Scope of application

| Role              | Yes/No |
|-------------------|--------|
| Spine/SuperSpine  | Yes    |
| Leaf              | Yes    |
| Access-Switch     | Yes    |