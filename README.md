
[Try Restcomm Cloud NOW for FREE!](https://www.restcomm.com/sign-up/) Zero download and install required.


All Restcomm [docs](https://www.restcomm.com/docs/) and [downloads](https://www.restcomm.com/downloads/) are now available at [Restcomm.com](https://www.restcomm.com).




# Restcomm Maven DU Plugin

The Maven DU Plugin can be used to manage build lifecycle of JAIN SLEE 1.1 Deployable Units (DUs) jars. It provides the following goals:

1. **copy-dependencies** - copies artifacts declared as dependencies to the deployable unit, assuming these are JAIN SLEE component (sbb,events,etc.) jars.
2. **generate-descriptor** - generates the deployable unit XML descriptor, taking as input specific directories as sources of SLEE component jars and service XML descriptors.
3. **generate-ant-management-script** - generates an Apache Ant script, which can be used to (un)deploy the deployable unit jar, using file copy/delete or JMX.

_Note: parameters and properties will be represented by its name between ${}. For instance, the parameter X, when referred, will be through ${X}_
