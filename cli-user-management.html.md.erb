---
title: Creating and Managing Users with the cf CLI
---

_This page assumes you are using cf v6._

Using the `cf` Command Line Interface (CLI), an administrator can create users
and manage organization and space roles.

**Note**: To manage users, organizations, and roles, you must log in with the
_UAA Administrator user credentials_.

## <a id='roles'></a>Creating and Deleting Users ##

* To create a new user, run: `cf create-user USER_NAME PASSWORD`

    Example:

    <pre class="terminal">
    $ cf create-user IamAuser pa55w0rd

    Creating user IamAuser as admin...
    OK
    </pre>

* To delete a user, run: `cf delete USER_NAME`

    Example:

    <pre class="terminal">
    $ cf delete-user IamAuser

    Really delete user IamAuser?> yes
    Deleting user IamAuser as admin...
    OK
    </pre>

## <a id='orgs-spaces'></a>Organizations and Spaces ##

_Organizations_ and _Spaces_ are the main organizational units in which
applications, services, domains, routes, and users are contained.
An account may include more than one organization, and an organization typically
contains more than one space.

### <a id='org-roles'></a>Organization Roles ###

An organization is the top-most meta object within the Cloud Foundry
infrastructure.

You can manage organization roles using `cf`.
The available roles are _OrgManager_, _BillingManager_, and _OrgAuditor_.

* To view the organizations in an account, run: `cf orgs`

    Example:

    <pre class="terminal">
    $ cf orgs

    Getting orgs as admin...

    name
    example-org
    my-department
    </pre>

* To see all users in an organization by role, run: `cf org-users ORGANIZATION_NAME`.

    Example:

    <pre class="terminal">
    $ cf org-users example-org

    Getting users in org example-org as admin...

    ORG MANAGER
      alice
      cybelle

    BILLING MANAGER
      bertram

    ORG AUDITOR
    </pre>

* To assign an organization role to a user, run: `cf set-org-role USER_NAME ORGANIZATION_NAME ROLE`

    Example:

    <pre class="terminal">
    $ cf set-org-role IamAuser example-org OrgManager

    Assigning role OrgManager to user IamAuser in org example-org as admin...
    OK
    </pre>

* To remove an organization role from a user, run: `cf unset-org-role USER_NAME ORGANIZATION_NAME ROLE`

    Example:

    <pre class="terminal">
    $ cf unset-org-role IamAuser example-org OrgManager

    Removing role OrgManager to user IamAuser in org example-org as admin...
    OK
    </pre>

### <a id='space-roles'></a>Space Roles ###

An organization can contain multiple spaces.
The defaults for a standard Cloud Foundry installation are **development**,
**test**, and **production**.

You can manage space roles using `cf`.
The available roles are _SpaceManager_, _SpaceDeveloper_, and _SpaceAuditor_.

* To view the spaces in an organizations, run: `cf spaces`

    Example:

    <pre class="terminal">
    $ cf spaces

    Getting spaces in org example-org as admin...

    name
    development
    production
    test
    </pre>

* To see all users in a space by role, run: `cf space-users ORGANIZATION_NAME SPACE_NAME`

    Example:

    <pre class="terminal">
    $ cf space-users example-org development

    Getting users in org example-org / space development as admin

    SPACE MANAGER
      admin
      alice

    SPACE DEVELOPER
      admin
      delucia

    SPACE AUDITOR
    </pre>

* To assign a space role to a user, run: `cf set-space-role USER_NAME ORGANIZATION_NAME SPACE_NAME ROLE`

    Example:

    <pre class="terminal">
    $ cf set-space-role IamAuser example-org development SpaceAuditor

    Assigning role SpaceAuditor to user IamAuser in org example-org / space development as admin...
    OK
    </pre>

* To remove a space role from a user, run: `cf unset-space-role USER_NAME ORGANIZATION_NAME SPACE_NAME ROLE`

    Example:

    <pre class="terminal">
    $ cf unset-space-role IamAuser example-org development SpaceAuditor

    Removing role SpaceAuditor to user IamAuser in org example-org / space development as admin...
    OK
    </pre>

[Return to the Getting Started Guide](../getstarted/index.html)