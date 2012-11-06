GreenBeanSupplier
=================

Repo for the Supplier part of the Green Bean lab

This project acts as a supplier in the lab. It accepts new orders via ftp. The ftp-server is configured in the Spring context file and in a properties file (users.properties)
You need to set a correct homedirectory for you ftp user before starting the app. Start the app by running mvn exec:java

Default username/password is admin/admin.