---
name: Demolition Permit
about: For demolition orders
title: 'DEMO / address'
labels: 'Received, Type: Demoliton'
assignees: benlk
body:
- type: input
  id: portal_link
  attributes:
    label: Permit portal link
  validations:
    required: true
- type: input
  id: parcel_number
  attributes:
    label: Parcel number
  validations:
    required: true
- type: input
  id: parcel_link
  attributes:
    label: Auditor link
    value: "https://audr-apps.franklincountyohio.gov/redir/Link/Parcel/"
    description: "e.g. https://audr-apps.franklincountyohio.gov/redir/Link/Parcel/01008375900"
  validations:
    required: true
- type: input
  id: zoned
  attributes:
    label: Zoned as
    description: https://gis.columbus.gov/zoning/
  validations:
    required: true
- type: input
  id: received
  attributes:
    label: Received date
  validations:
    required: true
- type: input
  id: due
  attributes:
    label: Automatic issue date
  validations:
    required: true
- type: checkbox
  id: issued
  attributes:
    label: "Has this already been issued?"
- type: checkbox
  id: emergency
  attributes:
    label: "Is this demolition an emergency?"
- type: markdown
  attributes:
    label: "Description of demolition:"
---


Attach:

- [ ] application
- [ ] notice form

Process steps:

- [ ] Reply to notification email
- [ ] Request copy of application if not downloadable from the portal
- [ ] Add involved parties to Mailchimp list
- [ ] Add item to next agenda in Mailchimp
- [ ] Hearing
- [ ] Reply to notification email with comments
