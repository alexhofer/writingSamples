# Pulling Timesheet Data

---
## Overview
---
Our application pulls timesheet data from your external provider automatically on two different schedules:
- Twice a day at midnight and noon it will pull and sync timesheets from now until two weeks in the past. 
- Every 30 minutes (previously 15 minutes) it will pull and sync changes made from now until the beginning of the current week. The week start day is configurable in your system settings.

If you have made changes to your timesheets you want synced that are older than two weeks there are two ways to go about this:
- Navigate to your integrations settings page, click on the integration to open the integration options, then click the "Sync" button. 
    - This will fully sync every unarchived project by pulling timesheets one month at a time until no more timesheets can be found. 
> **Warning**
>
> If there is more than one month of empty time in a project the timesheet data may be incomplete, if this happens please reach out to your Customer Success Representative. 
- Navigate to a specific project, click on the integrations tab, click the "Sync" button.

