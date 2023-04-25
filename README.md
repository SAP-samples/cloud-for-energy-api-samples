# SAP-samples/repository-template
This default template for SAP Samples repositories includes files for README, LICENSE, and .reuse/dep5. All repositories on github.com/SAP-samples will be created based on this template.

# Containing Files

1. The LICENSE file

2. The .reuse/dep5 file

3. The README.md file

4. The User Guide

# SAP Cloud for Energy Sample API Requests

<!--- Register repository https://api.reuse.software/register, then add REUSE badge:
[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/REPO-NAME)](https://api.reuse.software/info/github.com/SAP-samples/REPO-NAME)
-->

## Description

This is a collection of sample API requests for *SAP Cloud for Energy*. 
These sample API requests for the *Energy Data Services* API endpoints can help you to gain a better understanding about how the API works. 
 
*SAP Cloud for Energy* is a cloud application for storing and managing energy and water measurement data. This data is collected by smart meters that are installed in the homes of the utility’s customers. Measurement data and related device master data are ingested and can be retrieved using the *Energy Data Services* API. Many business processes rely on the data managed with *SAP Cloud for Energy*: The utilities, for example, bill and invoice their customers’ energy or water consumption based on the measurement data stored in *SAP Cloud for Energy*.

For more information about *SAP Cloud for Energy*, refer to the User Assistance on the [SAP Help Portal](https://help.sap.com/docs/SAP_Cloud_for_Energy). 
Most information there is only accessible to SAP customers with support user ID (S-User ID).

The *Energy Data Services* API is published with the *SAP Cloud for Energy* API package on the [SAP API Business Hub](https://api.sap.com/package/SAPC4EEDSAPIs/overview).

The API’s basic concepts, the endpoints, the structure of the request messages, as well as the validations and replacement value procedures carried out during the ingestion process are described in the [Energy Data Services API Guide](https://help.sap.com/docs/SAP_Cloud_for_Energy/960d94470c744a1fa72121ac63fa9d04/3077eb89ea66478c941246afb2b4192c.html?version=CLOUD). 
To access the information, you need a support user ID (S-User ID).

## Requirements
These are the prerequisites for using the sample API requests:
 
1. You have access to a licensed edition of *SAP Cloud for Energy*.

2. You have the rights to access the *Energy Data Services* API.

3. You have access to a Postman API Client application (available for download on the [Postman website](https://www.postman.com)).

## Download and Installation
Complete the following steps:

1. Download the collection files to your computer.

2. Import the Postman environment file to Postman.

	This is a *.json file containing the Postman environment. The environment defines the username, password, and further information that the sample API requests use to access the API. 

3. Adapt the values for the environment variables.

4. Import the Postman collection file to Postman.

	This is a *.json file containing the Postman collection with the sample API requests.
 
## Known Issues
No known issues.

## How to obtain support
As a customer or partner, please use your usual channels for any questions or feedback.
 
## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSE) file.
