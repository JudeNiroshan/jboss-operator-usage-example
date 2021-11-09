# JBoss-EAP-Operator Usage Examples

There are multiple ways we can configure continuous deployment(CD) strategies 
to deploy Java EE applications using EAP operator in Openshift.

### 1. Using buildConfigs in Openshift
In this approach, we expect you have already created a container image 
according to your needs.

👉🏽 [Follow this guide for bc(build-config) approach](./with-build-configs/README.md)

### 2. Using s2i-cli (source-to-image)
In this approach, we expect that you to have the source code of your 
Java EE application to start with.

👉🏽 [Follow this guide for s2i approach](./with-s2i-cli/README.md)
