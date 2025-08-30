# OIC Projects

An **OIC Project** provides a single, unified workspace for you and your team to design, manage, and monitor integrations.

OCI Project includes the ability to define **project deployments**, where you can easily move integrations to other environments, such as testing or production. A project deployment represents a list of one or more specific integration versions that must be in the environment you're exporting to, which then makes managing releases much easier.

**Accelerators** provide pre-built integrations from Oracle or third-party integrators that you can easily customize. All newly developed accelerators will be available from the integration store to be installed as a project that contains one or more versioned deployments.

With OIC Projects, you can restrict those who are allowed to edit, view, and monitor your integrations using **Role-Based Access (RBA) control**. In fact, designing integrations within a project is really the only way to control access at this fine level.

Components (such as Connections, Integrations, Libraries, Lookups, and Events) are available to be included within an OIC project. Packages can be used instead of projects to organize one or more integrations and their dependencies.

## OIC Project RBAC Permissions

Notice that by default, the project will be private to only you unless you choose to make it public to everyone. However, whether your project starts off as public or private, you can later modify project sharing options at any time. 

While project permissions are similar to OIC service roles such as service developer or service monitor, project permissions are essentially a layer of permissions on top of those service roles. Therefore, project access is restricted based on a user's OIC service role plus their project permissions.

In other words, access to project resources requires the appropriate level permissions in both the OIC service role and the explicit project access permissions.

## OIC Project Views

- Design
- Deploy
- Observe

## OIC Project Deployment

An **OIC project deployment** as a snapshot of all the integrations that must be deployed together, and should be activated as a group. This way, when you export your project, you can specify the intended deployment version as well. 