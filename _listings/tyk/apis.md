---
name: Tyk
x-slug: tyk
description: Tyk - Open Source API Gateway, API Management Platform, Developer Portal
  and Analytics - Tyk
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
x-kinRank: "9"
x-alexaRank: "489034"
tags: Tyk
created: "2018-08-31"
modified: "2018-08-31"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/apis.md
specificationVersion: "0.14"
apis:
- name: Tyk Gateway REST API - Get Keys
  x-api-slug: tykkeys-get
  description: Gets a list of *key* IDs (will only work with non-hashed installations)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykkeys-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykkeys-get-openapi.md
- name: Tyk Gateway REST API - Create Key
  x-api-slug: tykkeyscreate-post
  description: Create a new *API token* with the *session object* defined in the body
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykkeyscreate-post-openapi.md
- name: Tyk Gateway REST API - Update Key
  x-api-slug: tykkeyskeyid-put
  description: Update an *API token* with the *session object* defined in the body,
    this operatin overwrites the existing object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykkeyskeyid-put-openapi.md
- name: Tyk Gateway REST API - Add Custom Key
  x-api-slug: tykkeyskeyid-post
  description: Add a pre-specified *API token* with the *session object* defined in
    the body, this operatin creates a custom token that dsoes not use the gateway
    naming convention for tokens
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykkeyskeyid-post-openapi.md
- name: Tyk Gateway REST API - Remove Key
  x-api-slug: tykkeyskeyid-delete
  description: Remove this *API token* from the gateway, this will completely destroy
    the token and metadata associated with the token and instantly stop access from
    being granted
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykkeyskeyid-delete-openapi.md
- name: Tyk Gateway REST API - Get APIs
  x-api-slug: tykapis-get
  description: Gets a list of *API Definition* objects that are currently live on
    the gateway
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykapis-get-openapi.md
- name: Tyk Gateway REST API - Create API
  x-api-slug: tykapis-post
  description: Create an *API Definition* object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykapis-post-openapi.md
- name: Tyk Gateway REST API - Get API
  x-api-slug: tykapisapiid-get
  description: Gets an *API Definition* object, if it exists
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykapisapiid-get-openapi.md
- name: Tyk Gateway REST API - Delete API
  x-api-slug: tykapisapiid-delete
  description: Deletes an *API Definition* object, if it exists
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykapisapiid-delete-openapi.md
- name: Tyk Gateway REST API - Update API
  x-api-slug: tykapisapiid-put
  description: Updates an *API Definition* object, if it exists
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykapisapiid-put-openapi.md
- name: Tyk Gateway REST API - Check Health
  x-api-slug: tykhealth-get
  description: Gets the health check values for an API if it is being recorded
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykhealth-get-openapi.md
- name: Tyk Gateway REST API - Reload Gateway
  x-api-slug: tykreload-get
  description: Will reload the targetted gateway
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykreload-get-openapi.md
- name: Tyk Gateway REST API - Reload Group
  x-api-slug: tykreloadgroup-get
  description: Will reload the cluster via the targeted gateway
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykreloadgroup-get-openapi.md
- name: Tyk Gateway REST API - OAuth Create Client
  x-api-slug: tykoauthclientscreate-post
  description: Create a new OAuth client
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykoauthclientscreate-post-openapi.md
- name: Tyk Gateway REST API - Delete Client
  x-api-slug: tykoauthclientsapiidclientid-delete
  description: Delete the OAuth client
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykoauthclientsapiidclientid-delete-openapi.md
- name: Tyk Gateway REST API - OAuth Get Clients
  x-api-slug: tykoauthclientsapiid-get
  description: Get a list of OAuth clients bound to this back end
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykoauthclientsapiid-get-openapi.md
- name: Tyk Gateway REST API - OAuth Authorize Client
  x-api-slug: tykoauthauthorizeclient-post
  description: The final request from an authorising party for a redirect URI during
    the Tyk OAuth flow
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykoauthauthorizeclient-post-openapi.md
- name: Tyk Gateway REST API - Invalidate Key
  x-api-slug: tykoauthrefreshkeyid-delete
  description: Invalidate a refresh token
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykoauthrefreshkeyid-delete-openapi.md
x-common:
- type: x-website
  url: http://www.tyk.io
- type: x-api-gallery
  url: http://twitter.api.gallery.streamdata.io
- type: x-api-stack
  url: http://tyk.stack.network
- type: x-blog
  url: https://tyk.io/news-2/
- type: x-blog-rss
  url: https://tyk.io/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/tyk-technologies-ltd
- type: x-github
  url: https://github.com/TykTechnologies
- type: x-twitter
  url: https://twitter.com/tyk_io
- type: x-webhook
  url: https://tyk.io/docs/report-monitor-trigger-events/webhooks/
- type: x-website
  url: http://tyk.io/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---