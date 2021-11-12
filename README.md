# Red Hat Middleware EAP-Operator usage examples

There are multiple ways we can configure continuous deployment(CD) strategies 
to deploy Java EE applications using Red Hat Middleware EAP operator in Openshift.

### 1. Using buildConfigs in Openshift
In this approach, we expect that you have already created a container image 
according to your needs.

👉🏽 [Follow this guide for bc(build-config) approach](artifacts-with-build-configs/)

### 2. Using s2i-cli (source-to-image) with artifacts
In this approach, we expect that you to have the artifacts(.ear file) of your 
Java EE application to start with.

👉🏽 [Follow this guide for s2i approach with artifacts](artifacts-with-s2i-cli/)

### 3. Using s2i-cli (source-to-image) with source code
In this approach, we expect that you to have the source code of your 
Java EE application to start with.

👉🏽 [Follow this guide for s2i approach with source code](source-code-with-s2i-cli/)
