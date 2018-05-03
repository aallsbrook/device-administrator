
# ipm package: device-administrator

## Overview

The device administrator allows for end users to manage device types and schemas within a solution, provides device add, edit, update, and delete capability, and allows for sending as, receiving from and deleting historical messages on status and control.

This is an ipm package, which contains one or more reusable assets within the ipm Community. The 'package.json' in this repo is a ipm spec's package.json, [here](https://docs.clearblade.com/v/3/6-ipm/spec), which is a superset of npm's package.json spec, [here](https://docs.npmjs.com/files/package.json).

[Browse ipm Packages](https://ipm.clearblade.com)

## Setup

1. Modify the library called devadm_constants to include the platform url you are using
2. Save and Test the service called devadmSetup to create the user@clearblade.com and devadm_portaleditor@clearblade.com user


## Usage

Begin by opening the portal devadm Device Administration and log in as user@clearblade.com  From the portal view select devices in the menu flyout and edit them as needed.

### Code Services

- devadmGetAllUsers		
- devadmMessageUtil		
- devadmSetup		
- devadmTypeUtil		
- devadmUpdateDevice		

### Code Libraries

- devadm_constants		
- devadm_util_lib

### Portals

devadm Device Administration

### Collections

devadm_device_types

## Thank you

Powered by ClearBlade Enterprise IoT Platform: [https://platform.clearblade.com](https://platform.clearblade.com)
