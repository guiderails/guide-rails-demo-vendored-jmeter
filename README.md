# Shared Jmeter Resource

This is intended to be a shared resource to be used across non-build segments in Guide-Rails&#174;.

## Onboarding This Tepository

1. Copy this repository to your to your prefered source code manager server
2. Onboard the repo and let it run to completion
	- When onboarding the component, set the Tool Alias appropriately
	- The Job Image should be JAVA
	- Add the correct SSH clone URL
	- Select the master branch
3. Validate the below properties

### Additional Properties

| Name | Type | Value | Description |
| ---- | ---- | ----- | ----------- |
| vendor.version | string | 5.1.1 | [Jmeter Version](https://jmeter.apache.org/download_jmeter.cgi) |
| consul.tag | string | ((application.shortsha)) | |
| consul.servicename | string | ((application.name)) | |
