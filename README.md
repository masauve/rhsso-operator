# rhsso-operator

This repository define how to use the RH-SSO operator and create a basic instance.

Currently, one overlay is defined.  That overlay allow to specify a custom image location for the RHSSO deployment

``` oc apply -k overlays/customimage ```
