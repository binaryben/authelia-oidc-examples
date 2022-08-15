# authelia-oidc-outline
MVC of OAuth implementation with Outline and Authelia

The Traefik implementation is almost verbatim from [this guide by Rigaut-Luczak Lola](https://medium.com/@Lola_Dam/guide-for-installing-outline-with-authelia-as-an-openid-provider-129a141f6090). The main differences include:

* Usage of file based secrets
* Addition of NPM scripts to make getting started faster
* Separating reverse proxy config into separate file

> In production, use proper certificates!