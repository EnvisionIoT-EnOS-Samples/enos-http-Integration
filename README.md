# enos-http-Integration
This is the sample codes to upload a file via an model attribute of a simulated device to an EnOS device.


## Techology stack
- Java, latest
- EnOS Platform
- https://mvnrepository.com/artifact/com.envisioniot/enos-http-integration/0.1.1

## Prerequitsites

### Get the organization unit id, save to .env file
Follow the instructions below to get the organization unit id:
- https://www.envisioniot.com/docs/enos/en/latest/iam/howto/managing_org_info_account.html?highlight=organization%20unit#editing-the-organization-profile

### Get the APIM token server url, device broker url, save to .env file
Follow the instructions below to get the apim token server, device broker url and port:
- https://www.envisioniot.com/docs/enos/en/latest/getting_started_with_enos/planning.html?highlight=environment%20information#getting-environment-information

### Create a product and subdevice, save the product, subdevice key, secret and asset id to .env file
Follow the instructions below to create a product and subdevice.
- https://www.envisioniot.com/docs/device-connection/en/latest/howto/device/manage/creating_product.html
- https://www.envisioniot.com/docs/device-connection/en/latest/howto/device/manage/creating_device.html

### Register an EnOS application, save the app access key and secret to .env file
Follow the instructions below to register an EnOS application:
- https://www.envisioniot.com/docs/app-development/en/latest/app_management/managing_apps.html#registering-an-application

## How to run
To run the demo, run the following command in a new terminal.
```bash
javac com.envisioniot.enos.FileAttributePostSample
java FileAttributePostSample
```
