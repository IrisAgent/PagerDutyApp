# PagerDuty + IrisAgent Integration Benefits

* Understand the customer support impact of incidents in your infrastructure
* Prioritize incidents that have a high customer support burden and resolve them quickly
* Know which customers are getting impacted by infrastructure incidents and proactive reach out to them to manage their expectations
* Incidents and escalations are synchronized across PagerDuty and Zendesk as they update

# How it Works
* IrisAgent app monitors incidents on PagerDuty in real time and using machine learning and figures out which customer support tickets in Zendesk have been caused by PagerDuty incidents.
* Once you install IrisAgent on your Zendesk platform and connect it with PagerDuty, you will see list of PagerDuty incidents causing support tickets in the Zendesk platform.

# Requirements
* PagerDuty integrations require an Admin base role for account authorization. If you do not have this role, please reach out to an Admin or Account Owner within your organization to configure the integration.
* Zendesk integrations require an Admin base role for account authorization. If you do not have this role, please reach out to an Admin or Account Owner within your organization to configure the integration.

# Support

If you need help with this integration, please contact [us](mailto:contact@irisagent.com) 

# Integration Walkthrough
## In PagerDuty

You will need a read-only API key/token from PagerDuty. Follow the steps [here](https://support.pagerduty.com/docs/generating-api-keys#section-generating-a-general-access-rest-api-key) to generate one.

## In Zendesk

* Login to your Zendesk account and go to [this app listing page](https://www.zendesk.com/apps/support/iris-support-insights/) on Zendesk
* Click on the Install button on the top
* Provide the PagerDuty API key/token on the installation page (generated by following [these steps](https://support.pagerduty.com/docs/generating-api-keys#section-generating-a-general-access-rest-api-key))
* Click on the Install button at the bottom
* Open any ticket with a link such as https://<your-domain>.zendesk.com/agent/tickets/3 to see the app in action

# How to Uninstall

* In Zendesk, click on Settings -> Manage to see the list of your installed apps
* Select this app and click on Delete to uninstall the app
