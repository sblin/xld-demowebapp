
## Simple Demo web app for XL Deploy.

In dar/pom.xml set the application name and the package version:
```
    <applicationName>PetPortal</applicationName>
    <packageVersion>1.0</packageVersion>
```

Run the following command to deploy the dar file in your XL Deploy server:
```
mvn clean package xldeploy:import
```

