# Pitches

* [GitPitch Project](https://gitpitch.com/baloise/pitches/oidc-digitaltage#/), Slides to edit
* Presentation: [https://gitpitch.com/baloise/pitches/oidc-digitaltage](https://gitpitch.com/baloise/pitches/oidc-digitaltage)

# Storybook

## Responsibilities
* *Motivation*: Arthur
* *OAuth2*:Dane
* *OIDC*: Arthur
* *Problem Domain*: Dane
* *Live-Demo*: Roland 10' min
  
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
  
### Bibliography
* [OIDC CH](https://www.openid.ch/what-is-openid/)
* [OIDC Home Page](https://openid.net/connect/)
