## Use of this StarterKit is Deprecated
It is now possible to create a project with the same configuration as this StarterKit using our new project template for Visual Studio or the .NET CLI, as explained in the [Introduction](https://www.cloudscribe.com/docs/introduction)
With the new project template there are even more configurable options. This StarterKit is still maintained as a reference but it is much better to start new projects with the project template.

# Using cloudscribe Core and Entity Framework Core - MySql

This sample uses [cloudscribe Core](https://github.com/joeaudette/cloudscribe) for user authentication and Entity Framework/MySql storage for content and data.

[cloudscribe Core](https://github.com/joeaudette/cloudscribe) is a multi-tenant web application foundation. It provides multi-tenant identity management for sites, users, and roles.

Due to a known issue, the migrations won't work if you set the connection string to an existing MySql database. However, if you use a database name that does not exist and a user with sufficient permission to create a database, then it will create a database and migrations will work. After that you can change the connection string to a less priviledged user.

You can login with admin@admin.com as the username and admin as the password

Be sure to update the credentials before deployment.

[![Join the chat at https://gitter.im/joeaudette/cloudscribe](https://badges.gitter.im/joeaudette/cloudscribe.svg)](https://gitter.im/joeaudette/cloudscribe?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)




