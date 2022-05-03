# Overdue Notifications in Mobile Application

---

- [Overdue Notifications in Mobile Application](#overdue-notifications-in-mobile-application)
  - [Description](#description)
  - [PSW Maintenance](#psw-maintenance)
    - [Transmission Text](#transmission-text)
      - [Actions](#actions)
      - [Elapsed Days](#elapsed-days)
      - [Task Scheduler](#task-scheduler)
      - [Data Import](#data-import)
    - [Opened with Combo](#opened-with-combo)
    - [Opened with Selection Tool](#opened-with-selection-tool)

## Description

From version 6.5 onward `Overdue Notifications` content will be removed from `Data Dictionary` and merged with  `Transmission Text` feature.

`Overdue Notification` will be sent as single push and/or email notification (grouped by `Transaction Type` or `Document Type` if selected)

## PSW Maintenance

### Transmission Text

There is new set of items in `Actions` combo selection:


#### Actions

- for overdue timesheets:

  - Overdue Timesheet for Authorisation
  - Overdue Timesheet
  - Overdue Timesheet (Proxy)
  - Overdue TImesheet for Confirmation

- for overdue forms:

  - Overdue Form In Progress
  - Overdue Form In Progress (Proxy)
  - Overdue Form for Authorisation
  - Overdue Form for Review
  - Overdue Form for Confirmation

#### Elapsed Days

There is a new textbox `Elapsed Days` which can contain any value in range 0 - 365, representing number of days elapsed before overdue notificiation is sent.

#### Task Scheduler

Items/checkboxes in `Task Scheduler` `Notification` task remain unchanged.

These checkboxes will trigger new items from `Actions` list in `Transmission Text`

#### Data Import

PSW Runtime Parameters groups are opened using following controls:

### Opened with Combo

- __Inquiry Profiles__
  - Accounting Period
  - Current Approval Status

### Opened with Selection Tool
