# Changelog

## v1.17

- Deprecated: This policy is no longer being updated.

## v1.16

- updated README.md rightscale documentation links with docs.flexera documentation links

## v1.15

- Added default_frequency "daily"

## v1.14

- Modified escalation label and description for consistency

## v1.13

- Updated escalation block

## v1.12

- Adding incident resource table

## v.1.11

- Included README link in the policy template

## v1.10

- Updated the metadata

## v1.9

- add request_approval to delete volume escalation
- remove param_delete parameter

## v1.8

- Adds option to snapshot on volume delete

## v1.7

- Improved handling of volume delete failures. If a delete volume action is not allowed, say, due to the volume being locked, the volume will be tagged with the cloud exception error message and the policy will continue on to the next volume in the list.
- Subsequent runs of the applied policy will retry the delete (if that option was selected).

## v1.6

- Show volume tags in incident report.

## v1.5

- Update email subject with account name and ID, and change actions and/or resolution name to be more descriptive. Issues #75 & #83

## v1.4

- Use "Email and Delete" instead of "EMAIL AND DELETE" for the parameter and related delete volume logic.

## v1.3

- Added support for "exclusion" tags.

## v1.2

- Adding the count of volumes detected in the incident summary and details.

## v1.1

- Updating email from string to list

## v1.0

- initial release
