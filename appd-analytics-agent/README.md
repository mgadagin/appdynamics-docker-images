### Analytics Agent Image

* Download the latest agent bundle from https://download.appdynamics.com/download/

* Make a note of sha256 checksum value and the full version of the agent (e.g. 4.5.9.2096)

* Run ./build.sh passing the version and the checksum. The checksum can be left blank to avoid validation. It is a best practice to validate the package integrity.

An example yaml spec `deploy/java-init-analytics.yaml` is provided to demonstrate how to deploy the analytics agent as a sidecar 
to an application instrumented with the AppDynamics java agent.



