# scc-ckc-api-examples
This repo contains short example scripts that demonstrate and exmplain aspects of the Cisco Kinetic for Cities Platform APIs.

Examples
There are currently three example Python scripts in this repo:

ckc101_python_example.py - Authentication and API Requests

This sample script demonstrates logging into the Cisco Kinetic for Cities Platform and making an additional request. All Cisco Kinetic for Cities APIs (except authentication) requires an access token. In this example, those access token is obtained through the /token API and used to make another API request.

ckc102_python_example.py - Retrieving Information from the Cisco Kinetic for Cities Platform

This sample script demonstrates making several Cisco Kinetic for Cities API calls. In this example, additional information about the locations available to the current user and about the capabilities of the Cisco Kinetic for Cities instance itself is retrieved.

ckc103_python_example.py - Requesting Real Time Data from the Cisco Kinetic for Cities Platform

This sample script demonstrates getting Real Time Data from the Cisco Kinetic for Cities Platform. In this example, real time device information for lighting is retrieved and visualized as a simple pie chart.
