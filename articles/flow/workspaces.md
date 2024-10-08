# Workspaces

A Workspace contains Flows and artifacts, such as [Workspace Variables](workspaces/workspace-variables.md) and [Workspace Objects](workspaces/workspace-objects.md). Workspace Variables and Workspace Objects are resources that can be shared by all Flows in the Workspace. A Workspace also defines user access.

## Workspace Objects

Workspace Objects are reusable objects that consist of multiple values, for example a SQL Server connection having a server name, database name, username, and password. This means that, instead of defining a different connection for every SQL Server action in a Flow, you can reuse an existing connection definition and manage its settings in one central location.  

A Workspace object _property_, such as a user name in a SQL Server connection, may be a [Workspace variable](workspaces/workspace-variables.md). This means that a Workspace object may be configured to be dynamic based on which [Environment](environments.md) the Flow is in.

[Read more about Workspace Objects](workspaces/workspace-objects.md)

## Workspace Variables

Workspace Variables are simple values that can be shared by all Flows in a Workspace. Examples of Workspace variables include connection strings, usernames, database names, urls, numeric values, etc. Workspace Variables also can be used in Workspace Objects.

Environments and Workspace Variables are closely related. Each Workspace variable can hold one distinct value pr environment. For example, you may define a _ConnectionString_ variable that points to different databases for Development and Production. This functionality enables you to deploy a Flow to different environments without having to make manual changes to the configuration of the Flow when it's deployed to the target environment.

[Read more about Workspace Variables](workspaces/workspace-variables.md)  
[Read more about Environments](../flow/environments.md)

## Access control
By default, only Tenant administrators have access to a Workspace. In order for non-admin users to get access to a Workspace or Flows in the Workspace, they must be granted access to the Workspace by adding them to the list of allowed users. You can do this from the Workspace details screen in the Flow Portal.  

[Read more about configuring Workspace access control](../flow/workspaces/workspace-access-control.md)
