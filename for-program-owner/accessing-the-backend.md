# Access CENTRAL Backend

### Accessing the backend

First, login to MaGIC CENTRAL through MaGIC Account.

{% page-ref page="../for-frontend-users/magic-account.md" %}

You will be able to see the backend link on the side menu if your account has admin access. 

or, you may access it directly from this URL: [https://central.mymagic.my/backend](https://central.mymagic.my/backend)

### Production vs Staging

Understand the concept between production and staging. Production is our live server where public users are using it all the time. Staging is our test server, where developers can use it to double-check whether their code is working in a server environment similar to production. Of course, different environments connect to different database servers. 

Production Backend: [https://central.mymagic.my/backend](https://central.mymagic.my/backend)  
Staging Backend: [https://hub.mymagic.my/backend](https://hub.mymagic.my/backend)

Make sure you log in to the correct one.

### Admin Access Control Limit

There are few type of admin roles in the system. These roles can be created dynamically and map to a specific access from backend. 

| Role | Description |
| :--- | :--- |
| Super Admin | Has access to everything in the backend |
| Admin | Limited access in the backend |
| Sensitive Data Admin | Able to access sensitive data like individual IC, Address, etc. |



