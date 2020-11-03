# Pitches

* [GitPitch Project](https://gitpitch.com/baloise/pitches/oidc-digitaltage#/), Slides to edit
* Presentation: [https://gitpitch.com/baloise/pitches/oidc-digitaltage](https://gitpitch.com/baloise/pitches/oidc-digitaltage)

# Storybook

## Responsibilities
* *Motivation*: Arthur
* *Example Domain*: Markus
* *OAuth2*:Dane
* *OIDC*: Arthur
* *Live-Demo*: Roland 10' min

## Introduction/ Motivation

* four fearless musketeers started
  * to do REST on CC 2020
  * OIDC did turn out to be a key spot
* We therefore:
  * played through an OIDC tutorial (2 days)
  * did setup docker image with Keycloak, Apache DS and MySQL
  * created a library sample application based on that tutorial and springboot
  * configured and customized Keycloak (Federated User Service, Github)
  * added swagger
  * provisioned everything on OpenShift (co-operation with )
  * provided an excellent **jump start** for everybody to start with
* currently Baloise only - but could be public?
   
## OIDC

### Definition
* stands for "OpenID Connect"
* Layer on top of OAuth 2.0
* Allow clients to verify identity of End-Users
  * based on authentication
  * performed by authorization server
* Allows also obtaining basi profile information
* interoperable, REST-like manner
* final spec 02/26/2014

### Workflow
* End-user creates an identity with an *ID-Provider*
* Calling a resource using an identity URL he/ she will be
  rerouted to that ID-Provider to login
* after successful login the ID provider reroutes back to the
  URL it was called before
* calling this or (other services using same authentication)
  now no longer forces logins

### Advantages
* Single Sign on to several (web) resources
* based completely on OAuth 2.0
* only little effort to become a resource provider
* End-user has not to deal with too much digital identities
  (using too many user names and passwords)
* Password change/ reset easier and faster (only one)
* propagation also of further person related data
  (address, phone, etc.) relevant for resource owner
  
## Summary

* What did you learn today?

* 5 Days CC: Focus on a topic!
* Awsome cross-team cooperation - although we had Corona
* a broader understanding of how OIDC, OAuth2, Keycloak, etc work and can be used
* side-effects: IntelliJ, Springboot, and much more.
* Thus: CodeCamp, Gold Cards, Innovation - dare it and carry innovation!
  
### Bibliography
* [OIDC CH](https://www.openid.ch/what-is-openid/)
* [OIDC Home Page](https://openid.net/connect/)

## 10/30/2020, Feedback
* all on camera
* outstanding Demo
* merge slides and URls
* check camera position/ focus
* disable all notification
* some spice into the presentation? Story telling, joke, analogies

### Feedback
* Azure Integration!
* open Browser network Tab, preserve logs
* JWT token