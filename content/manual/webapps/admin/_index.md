---

title: 'Admin'
weight: 110

menu:
  main:
    identifier: "user-guide-admin"
    parent: "webapps"
    pre: "Web application for user management"
---


Along with the Operaton web applications we ship Admin, accessible via [http://localhost:8080/camunda/app/admin/](http://localhost:8080/camunda/app/admin/).
Admin is an application that allows you to configure users and groups via the engine's [Identity Service]({{< ref "/manual/user-guide/process-engine/identity-service.md" >}}) and authorizations via the engine's [Authorization Service]({{< ref "/manual/user-guide/process-engine/authorization-service.md" >}}). Furthermore, you can connect Operaton Admin to your [LDAP system]({{< ref "/manual/user-guide/process-engine/identity-service.md#the-ldap-identity-service" >}}).

{{< img src="img/admin-start-page-view.png" title="Admin Start Page" >}}
