---
@title[OIDC]

## OAuth2 und OIDC 

Arthur Neudeck, Markus Lindenmann, Roland Seidel, Dane Leube
![Logo](./img/oauth.jpg)

---
@title[Overview]
### Overview
* Why OAuth and OIDC?
* OAuth2 and OIDC
* Example Domain
* Live-Demo 

---

## Why OAuth and OIDC?

+++

### 10 years ago

![yelp](./img/yelp.png)

+++

### Use Cases

* Simple login
* Single Sign-on accross multiple sites 
* Mobile app login
* Delegates authorization


+++

### Delegates authorization

Give another site access to my data.

---

## OAuth2 and OIDC

+++

### OAuth2

OAuth 2.0 is the industry-standard protocol for authorization. OAuth 2.0 focuses on client developer simplicity while providing specific authorization flows for web applications, desktop applications, mobile phones, and living room devices. IETF OAuth Working Group developed this specification and its extensions.

+++

### OAuth2 grant flow

![oauth2](./img/oauth2.png)

+++

### OAuth2 terminology

* Resource owner
* Client
* Authorization server
* Resource server
* Authorization grant
* Access token
+++

### OAuth2 flows

* Authorization code
* Implicit (deprecated)
* Resource owner password credentials
* Client credentials

+++

### OIDC

How do we publish user infos (e.g. E-Mail, username, etc.)? No standard way to get this information.
No common set of scopes

+++

### OAuth and OIDC

* OpenID Connect is for **authentication**

* OAuth 2.0 is for **authorization**

+++

@snap[north]
## Open ID Connect
@snapend

@snap[west sidebar]
![oidc](./img/oidc.png)
@snapend

@snap[east sidebar]
@ul
- ID token
- User Info Endpoint
- OpenID Provider Configuration Information
@ulend
@snapend

+++

---

* 



