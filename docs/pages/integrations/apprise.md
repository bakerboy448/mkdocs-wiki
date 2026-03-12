# Apprise

!!! info
    This integration tracks notification history from [Apprise](https://github.com/caronc/apprise) apps. Apprise is a notification library that supports many notification services. When apps send notifications through Apprise to Notifiarr, the history is tracked and displayed here.

---

## Overview

Apprise does not use traditional triggers like other integrations. Instead, it passively tracks notifications received from Apprise-connected apps.

### App History

The integration displays a table of all apps that have sent notifications through Apprise:

| Column | Description |
|--------|-------------|
| **App** | The name of the application |
| **First** | When the first notification was received |
| **Last** | When the most recent notification was received |
| **Total** | Total number of notifications received |
| **Delete** | Remove the app from the history |

---

## Instructions

1. Configure Apprise to send notifications to your Notifiarr webhook URL
2. The Notifiarr website will automatically track notification history as apps send notifications
3. View the history table on the Apprise integration page
4. Use the delete checkbox to remove apps you no longer want to track
