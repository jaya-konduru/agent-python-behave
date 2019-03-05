# agent-python-behave
Python Behave integration. Step and Scenario based implementation.

Required packages:
* `behave==1.2.6` or relevant version
* `pytest-reportportal`


# `step_based` parameter
Is responsible for Scenario or Step based logging

example: `>behave -D step_based=True` in this case Step based logging will be applied.

Note: Scenario based logging applied by default


#`behave.ini` file
In your `behave.ini` file you will have to add `[report_portal]` block
* `rp_endpoint =` report_portal_url
* `rp_project =` your report portal project name
* `rp_token =` your UUID (can found in your profile of Report portal)
* `rp_launch_name =` 'Your default launch name'
* `rp_launch_description =` 'Your default launcher description'

#`rp_enable` parameter