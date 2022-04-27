# rhsso-operator

This repository define how to use the RH-SSO operator and create a basic instance.

Currently, one overlay is defined.  That overlay allow to specify a custom image location for the RHSSO deployment

``` oc apply -k operator/overlays/customimage ```

Before using, please modify the namespace to deploy and the target image value

to create an instance using the operator, simply do:

``` oc apply -k instance/overlays/default ```

Other possible environnement variables are defined here:

https://github.com/keycloak/keycloak-operator


