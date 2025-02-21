# Getting Started with Snowflake Native Apps

### This repository contains the sample code for the [Getting Started with Snowflake Native Apps Quicsktart](https://quickstarts.snowflake.com/guide/getting_started_with_native_apps/). 

https://app.snowflake.com/QIQZSRY/hv39958/#/apps/application/NATIVE_APP_QUICKSTART_PACKAGE_RIYAM/schema/APP_INSTANCE_SCHEMA/streamlit/STREAMLIT


![Snowflake Native Apps](https://quickstarts.snowflake.com/guide/getting_started_with_native_apps/img/edcfa4000a03ae36.png)
nowflake Native Apps are a new way to build data intensive applications. Snowflake Native Apps benefit from running inside Snowflake and can be installed from the Snowflake Marketplace, similar to installing an app on a smart phone. Snowflake Native Apps can read and write data to a user's database (when given permission to do so). Snowflake Native Apps can even bring in new data to their users, providing new insights.

When discussing Snowflake Native Apps, there are two personas to keep in mind: Providers and Consumers.

Providers: Developers of the app. The developer or company publishing an app to the Snowflake Marketplace is an app provider.
Consumer: Users of an app. When a user installs an app from the Snowflake Marketplace, they are a consumer of the app.


#### Additional resources

- [Snowflake Native App Developer Toolkit](https://www.snowflake.com/snowflake-native-app-developer-toolkit/?utm_source=github&utm_medium=github&utm_campaign=na-us-en-eb-developer-toolkit-github)
![Screenshot 2025-02-21 092145](https://github.com/user-attachments/assets/134093de-bc07-446d-b6e7-31ead6c6dfb5)
Click on the app to launch it and give it a few seconds to warm up.

When running the app for the first time, you'll be prompted to do some first-time setup by granting the app access to certain tables (i.e., create object-level bindings). The bindings link references defined in the manifest file to corresponding objects in the Snowflake account. These bindings ensure that the application can run as intended.

Upon running the application, you will see this:
Once we have created the necessary tables in the provider and consumer side, the next step is to load the csv files to the corresponding tables. A stage is available and directly linked to every table created in Snowflake, so we are going to take advantage of that dedicated stage and upload the files directly to the table associated stage. You can find more information about stages types here That is accomplished using the snow stage copy command:

# loading shipping data into table stage
![Screenshot 2025-02-21 090419](https://github.com/user-attachments/assets/6f591942-5882-4d2f-aa3e-9bbc00a15a3a)


![Screenshot 2025-02-21 090439](https://github.com/user-attachments/assets/17b1f3de-f394-4a95-88f8-e40ed76fb288)

