---
name: Tyk
x-slug: tyk
description: Tyk - Open Source API Gateway, API Management Platform, Developer Portal
  and Analytics - Tyk
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
x-kinRank: "9"
x-alexaRank: "489034"
tags: Tyk
created: "2018-05-22"
modified: "2018-05-22"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/apis.md
specificationVersion: "0.14"
apis:
- name: Tyk API Management Get Keys
  x-api-slug: tyk-api-management
  description: Gets a list of *key* IDs (will only work with non-hashed installations)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/keys/
  tags: API Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykkeys-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykkeys-get-openapi.md
- name: Tyk API Management Create Key
  x-api-slug: tyk-api-management
  description: Create a new *API token* with the *session object* defined in the body
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/keys/create
  tags: API Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykkeyscreate-post-openapi.md
- name: Tyk API Management Update Key
  x-api-slug: tyk-api-management
  description: Update an *API token* with the *session object* defined in the body,
    this operatin overwrites the existing object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/keys/{keyId}
  tags: API Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykkeyskeyid-put-openapi.md
- name: Tyk API Management Add Custom Key
  x-api-slug: tyk-api-management
  description: Add a pre-specified *API token* with the *session object* defined in
    the body, this operatin creates a custom token that dsoes not use the gateway
    naming convention for tokens
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/keys/{keyId}
  tags: API Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykkeyskeyid-post-openapi.md
- name: Tyk API Management Remove Key
  x-api-slug: tyk-api-management
  description: Remove this *API token* from the gateway, this will completely destroy
    the token and metadata associated with the token and instantly stop access from
    being granted
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/keys/{keyId}
  tags: API Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykkeyskeyid-delete-openapi.md
- name: Tyk API Management Get APIs
  x-api-slug: tyk-api-management
  description: Gets a list of *API Definition* objects that are currently live on
    the gateway
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/apis/
  tags: API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykapis-get-openapi.md
- name: Tyk API Management Create API
  x-api-slug: tyk-api-management
  description: Create an *API Definition* object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/apis/
  tags: API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykapis-post-openapi.md
- name: Tyk API Management Get API
  x-api-slug: tyk-api-management
  description: Gets an *API Definition* object, if it exists
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/apis/{apiID}
  tags: API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykapisapiid-get-openapi.md
- name: Tyk API Management Delete API
  x-api-slug: tyk-api-management
  description: Deletes an *API Definition* object, if it exists
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/apis/{apiID}
  tags: API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykapisapiid-delete-openapi.md
- name: Tyk API Management Update API
  x-api-slug: tyk-api-management
  description: Updates an *API Definition* object, if it exists
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/apis/{apiID}
  tags: API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykapisapiid-put-openapi.md
- name: Tyk API Management Check Health
  x-api-slug: tyk-api-management
  description: Gets the health check values for an API if it is being recorded
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/health/
  tags: API Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykhealth-get-openapi.md
- name: Tyk API Management Reload Gateway
  x-api-slug: tyk-api-management
  description: Will reload the targetted gateway
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/reload/
  tags: API Reload
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykreload-get-openapi.md
- name: Tyk API Management Reload Group
  x-api-slug: tyk-api-management
  description: Will reload the cluster via the targeted gateway
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/reload/group
  tags: API Reload
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykreloadgroup-get-openapi.md
- name: Tyk API Management OAuth Create Client
  x-api-slug: tyk-api-management
  description: Create a new OAuth client
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/oauth/clients/create
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykoauthclientscreate-post-openapi.md
- name: Tyk API Management Delete Client
  x-api-slug: tyk-api-management
  description: Delete the OAuth client
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/oauth/clients/{apiId}/{clientId}
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykoauthclientsapiidclientid-delete-openapi.md
- name: Tyk API Management OAuth Get Clients
  x-api-slug: tyk-api-management
  description: Get a list of OAuth clients bound to this back end
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/oauth/clients/{apiId}
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykoauthclientsapiid-get-openapi.md
- name: Tyk API Management OAuth Authorize Client
  x-api-slug: tyk-api-management
  description: The final request from an authorising party for a redirect URI during
    the Tyk OAuth flow
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/oauth/authorize-client/
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykoauthauthorizeclient-post-openapi.md
- name: Tyk API Management Invalidate Key
  x-api-slug: tyk-api-management
  description: Invalidate a refresh token
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/oauth/refresh/{keyId}
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/tykoauthrefreshkeyid-delete-openapi.md
- name: Tyk API Management
  x-api-slug: tyk-api-management
  description: Tyk - Open Source API Gateway, API Management Platform, Developer Portal
    and Analytics - Tyk
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}//
  tags: Tyk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tyk/master/_listings/tyk/openapi.md
x-common:
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
- type: x-website
  url: http://tyk.io/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---