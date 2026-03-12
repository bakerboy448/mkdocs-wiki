# Jellyseerr

!!! question "jellyseerr notifications"
    If you have any issues setting up notifications for jellyseerr refer to this [wiki](https://docs.jellyseerr.dev/using-jellyseerr/notifications)

---

## Trigger options

![instructions2.png](../../assets/screenshots/integrations/jellyseerr/trigger-channel.png)

1. Triggers
    - `Pending` - Receive a notification when a new request is pending
    - `Approved` - Receive a notification when a request is approved
    - `Auto approved` - Receive a notification when a request is automatically approved
    - `Declined` - Receive a notification when a request is declined
    - `Available` - Receive a notification when requested media becomes available
    - `Failed` - Receive a notification when a request fails
    - `Issues` - Receive a notification when an issue is reported
1. Channel
    - Pick the channel for each trigger's notifications

---

### Channel Picker

![instructions3.png](../../assets/screenshots/integrations/jellyseerr/channel-picker.png)

1. List of channels `Dropdown menu`
2. Test bot channel permissions
3. Copy Channel to all

---

## Configuration

![instructions4.png](../../assets/screenshots/integrations/jellyseerr/configuration.png)

1. Enable triggers and pick colors for each trigger
1. Expand the notification content settings via the customize button

Each trigger (except `Issues`) has the following notification content options:

- `Thumbnail` - Show the media poster
- `Requester` - Show who requested the media
- `Request Id` - Show the request ID
- `Overview` - Show the media overview/summary
- `Status` - Show the request status
- `Network` - Show the network/studio
- `Links` - Show links to external sites
- `Rating: IMDb` - Show the IMDb rating
- `Rating: TMDb` - Show the TMDb rating
- `Rating: TVDb` - Show the TVDb rating
- `Rating: RT` - Show the Rotten Tomatoes rating
- `Rating: MC` - Show the Metacritic rating
- `Awards` - Show award information
- `Ping requester` - Ping the requester in the notification
- `Background` - Show a background image
- `Runtime` - Show the media runtime

The `Available` trigger also has:

- `Seasons requested` - Show which seasons were requested
- `Content Rating` - Show the content rating

The `Failed` trigger also has:

- `Content rating` - Show the content rating

The `Issues` trigger has:

- `Thumbnail` - Show the media poster
- `Background` - Show a background image

!!! note
    **Be sure to save settings**

---

## Instructions

![instructions1.png](../../assets/screenshots/integrations/jellyseerr/instructions.png)

1. Notifications Settings
2. Webhook
3. Enable the webhook agent
4. Add the notification URL `https://notifiarr.com/api/v1/notification/jellyseerr/api_key_here` - Make sure to make an API key specific to Jellyseerr
5. Notification types you want to receive
6. Save changes and enable the webhook
