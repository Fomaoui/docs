1. Enter a name for your runner group, and assign a policy for organization access.

    You can configure a runner group to be accessible to a specific list of organizations, or all organizations in the enterprise.{% ifversion ghec or ghes %} By default, only private repositories can access runners in a runner group, but you can override this. This setting can't be overridden if configuring an organization's runner group that was shared by an enterprise.{% endif %}
