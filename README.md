# Pushover-LogScale-alert-action
[Falcon LogScale](https://www.crowdstrike.com/products/observability/falcon-logscale/) Alert action template to [Pushover](https://pushover.net) notifications.

Refer to the Pushover API (https://pushover.net/api#messages) for details on Pushover fields.
Refer to the Falcon LogScale Message Templates and Variables https://library.humio.com/falcon-logscale/automated-actions-message-template.html for details on LogScale alert variables that can be included in Pushover messages.

To make use of this LogScale alert action:
 * Download the [Pushover.yaml](https://github.com/bgraabek/Pushover-LogScale-alert-action/blob/main/Pushover.yaml) file.
 * Enter the LogScale repository where you wish to make use of the Pushover alert action.
 * Click on "Alerts"
 * Click on "Actions" in the left-hand menu
 * Click "+ New action"
 * Enter an action name
 * Click "From template"
 * Load the Pushover.yaml file
 * Click Continue
 * Modify the "token" and "user" values in the "Message body template"
 * Modify the "message" so your alerts fit your requirements
 * Once you've modified at least the "token" and "user" values, click "Save action"
