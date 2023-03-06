# Disable unused interfaces

## Use case
- Access the device-context and navigate the `interface` dictionnary to look for any interface with a blank description. That will mean the interface is currently not used. Render a disable statement for that interface.

## Scope of application

| Role              | Yes/No |
|-------------------|--------|
| Spine/SuperSpine  | Yes    |
| Leaf              | Yes    |
| Access-Switch     | Yes    |