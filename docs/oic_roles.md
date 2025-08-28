# OIC Service Roles

Once the OIC instance has been provisioned, in order for anyone to access that environment, users will need to be assigned to one or more service roles by an OCI Security Administrator.

## Service Roles

- ServiceViewer
    - Users can navigate to all integration resource pages
    - Users have limited access to read-only APIs
    - Users **cannot** navigate to the administrative setting pages
    - Users **cannot** invoke any integrations at runtime
- ServiceInvoker
    - Users can invoke any integration flow that is exposed through SOAP or REST APIs or to trigger a scheduled integration run
    - Users **cannot** access the OIC console
- ServiceUser
    - Combine the privileges of both the viewer and the invoker
- ServiceMonitor
    - Users can monitor everything provisioned in an OIC instance from a runtime perspective
    - Users **cannot** access or view any design time information
    - USers **cannot** invoke any integrations
- ServiceDeveloper
    - Users can develop and run any of the resources associated with creating, activating, monitoring, and troubleshooting integrations
    - Users **cannot** navigate to the administrative settings pages in the console, nor invoke any administrative APIs
- ServiceAdministrator
    - Users can manage and administer everything using the OIC Service Console or REST apis
    - Users can develop and test integrations themselves since they have full developer access as well
