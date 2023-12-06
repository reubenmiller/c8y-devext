# c8y-devext

:warning: This is just an example project only Please fork it and modify as required

go-c8y-cli extension to managed software on a device. This uses the newer [Software Management v2 microservice](https://cumulocity.com/guides/reference/device-management-library/#adding-software-packages) API in Cumulocity IoT.

## Prerequisites

* go-c8y-cli >= 2.38.1 (due to support for json array bodies)

## What is included?

**Note**

Use ✅ or 🔲 indicates if the extension includes the given functionality or not.


|Type|Included|Notes|
|----|:-:|-----|
|Commands|✅|Commands to manage the software on a device (e.g. add/remove/set software in the c8y_SoftwareList property|

## Install

The extension can be installed using the following command.

```sh
c8y extension install reubenmiller/c8y-devext
```
