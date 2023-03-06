# LACP Force Up

## Use case
- This is a requirement for PXE boot.
- The configlet will require to be tag driven. Assign a tag to the interfaces where you want to see this configlet be applied then use the `Tags query` section during the configlet application to select the tag.

## Scope of application

| Role              | Yes/No |
|-------------------|--------|
| Spine/SuperSpine  | No     |
| Leaf              | Yes    |
| Access-Switch     | Yes    |
