---
swagger: "2.0"
info:
  title: Tyk Gateway REST API
  description: The API for managing the Tyk API management gateway, allowing API control
    over the operation of a variety of APIs.
  termsOfService: https://tyk.io/terms-and-conditions/
  version: "1.9"
host: '{baseURL}'
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tyk/reload/:
    get:
      summary: Reload Gateway
      description: |
        Will reload the targetted gateway
      operationId: will-reload-the-targetted-gateway
      parameters:
      - in: header
        name: x-tyk-authorization
        description: tyk gateway shared secret
      responses:
        200:
          description: OK
      tags:
      - api reload
definitions:
  OAuthClient:
    properties:
      client_id:
        description: This is a default description.
        type: delete
      secret:
        description: This is a default description.
        type: delete
      redirect_uri:
        description: This is a default description.
        type: delete
  AccessRights:
    properties:
      api_name:
        description: This is a default description.
        type: delete
      api_id:
        description: This is a default description.
        type: delete
      versions:
        description: This is a default description.
        type: delete
  SessionObject:
    properties:
      allowance:
        description: This is a default description.
        type: delete
      rate:
        description: This is a default description.
        type: delete
      per:
        description: This is a default description.
        type: delete
      expires:
        description: This is a default description.
        type: delete
      quota_max:
        description: This is a default description.
        type: delete
      quota_renews:
        description: This is a default description.
        type: delete
      quota_remaining:
        description: This is a default description.
        type: delete
      quota_renewal_rate:
        description: This is a default description.
        type: delete
      access_rights:
        description: This is a default description.
        type: delete
      org_id:
        description: This is a default description.
        type: delete
  EndpointMethodMeta:
    properties:
      action:
        description: This is a default description.
        type: delete
      code:
        description: This is a default description.
        type: delete
      data:
        description: This is a default description.
        type: delete
      headers:
        description: This is a default description.
        type: delete
  EndPointMeta:
    properties:
      path:
        description: This is a default description.
        type: delete
      method_actions:
        description: This is a default description.
        type: delete
  TemplateMeta:
    properties:
      template_data:
        description: This is a default description.
        type: delete
      path:
        description: This is a default description.
        type: delete
      method:
        description: This is a default description.
        type: delete
  HeaderInjectionMeta:
    properties:
      delete_headers:
        description: This is a default description.
        type: delete
      add_headers:
        description: This is a default description.
        type: delete
      path:
        description: This is a default description.
        type: delete
      method:
        description: This is a default description.
        type: delete
  VersionDefinition:
    properties:
      name:
        description: This is a default description.
        type: delete
      expires:
        description: This is a default description.
        type: delete
      global_headers:
        description: This is a default description.
        type: delete
      global_headers_remove:
        description: This is a default description.
        type: delete
      global_size_limit:
        description: This is a default description.
        type: delete
      override_target:
        description: This is a default description.
        type: delete
      use_extended_paths:
        description: This is a default description.
        type: delete
      extended_paths:
        description: This is a default description.
        type: delete
  MiddlewareDefinition:
    properties:
      name:
        description: This is a default description.
        type: delete
      path:
        description: This is a default description.
        type: delete
      require_session:
        description: This is a default description.
        type: delete
  ServiceDiscoverConfiguration:
    properties:
      use_discovery_service:
        description: This is a default description.
        type: delete
      query_endpoint:
        description: This is a default description.
        type: delete
      use_nested_query:
        description: This is a default description.
        type: delete
      parent_data_path:
        description: This is a default description.
        type: delete
      data_path:
        description: This is a default description.
        type: delete
      port_data_path:
        description: This is a default description.
        type: delete
      use_target_list:
        description: This is a default description.
        type: delete
      cache_timeout:
        description: This is a default description.
        type: delete
      endpoint_returns_list:
        description: This is a default description.
        type: delete
  APIDefinition:
    properties:
      id:
        description: This is a default description.
        type: delete
      name:
        description: This is a default description.
        type: delete
      slug:
        description: This is a default description.
        type: delete
      api_id:
        description: This is a default description.
        type: delete
      org_id:
        description: This is a default description.
        type: delete
      use_keyless:
        description: This is a default description.
        type: delete
      use_oauth2:
        description: This is a default description.
        type: delete
      oauth_meta:
        description: This is a default description.
        type: delete
      auth:
        description: This is a default description.
        type: delete
      use_basic_auth:
        description: This is a default description.
        type: delete
x-collection-name: Tyk
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---