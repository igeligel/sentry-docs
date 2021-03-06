---
# This file is automatically generated from the API using `api-docs/generate.py`
# Do not manually this file.
{
  "api_path": "/api/0/projects/{organization_slug}/{project_slug}/keys/", 
  "authentication": "", 
  "description": "Return a list of client keys bound to a project.", 
  "example_request": "GET /api/0/projects/the-interstellar-jurisdiction/pump-station/keys/ HTTP/1.1\nHost: sentry.io\nAuthorization: Bearer {base64-encoded-key-here}", 
  "example_response": "HTTP/1.1 200 OK\nContent-Length: 908\nX-XSS-Protection: 1; mode=block\nX-Content-Type-Options: nosniff\nContent-Language: en\nVary: Accept-Language, Cookie\nLink: <https://sentry.io/api/0/projects/the-interstellar-jurisdiction/pump-station/keys/?&cursor=4:0:1>; rel=\"previous\"; results=\"false\"; cursor=\"4:0:1\", <https://sentry.io/api/0/projects/the-interstellar-jurisdiction/pump-station/keys/?&cursor=4:100:0>; rel=\"next\"; results=\"false\"; cursor=\"4:100:0\"\nAllow: GET, POST, HEAD, OPTIONS\nX-Frame-Options: deny\nContent-Type: application/json\n\n[\n  {\n    \"browserSdk\": {\n      \"choices\": [\n        [\n          \"latest\", \n          \"latest\"\n        ], \n        [\n          \"4.x\", \n          \"4.x\"\n        ]\n      ]\n    }, \n    \"browserSdkVersion\": \"4.x\", \n    \"dateCreated\": \"2018-09-20T15:48:07.397Z\", \n    \"dsn\": {\n      \"cdn\": \"https://sentry.io/js-sdk-loader/cfc7b0341c6e4f6ea1a9d256a30dba00.min.js\", \n      \"csp\": \"https://sentry.io/api/2/csp-report/?sentry_key=cfc7b0341c6e4f6ea1a9d256a30dba00\", \n      \"minidump\": \"https://sentry.io/api/2/minidump/?sentry_key=cfc7b0341c6e4f6ea1a9d256a30dba00\", \n      \"public\": \"https://cfc7b0341c6e4f6ea1a9d256a30dba00@sentry.io/2\", \n      \"secret\": \"https://cfc7b0341c6e4f6ea1a9d256a30dba00:a07dcd97aa56481f82aeabaed43ca448@sentry.io/2\", \n      \"security\": \"https://sentry.io/api/2/security/?sentry_key=cfc7b0341c6e4f6ea1a9d256a30dba00\"\n    }, \n    \"id\": \"cfc7b0341c6e4f6ea1a9d256a30dba00\", \n    \"isActive\": true, \n    \"label\": \"Fabulous Key\", \n    \"name\": \"Fabulous Key\", \n    \"projectId\": 2, \n    \"public\": \"cfc7b0341c6e4f6ea1a9d256a30dba00\", \n    \"rateLimit\": null, \n    \"secret\": \"a07dcd97aa56481f82aeabaed43ca448\"\n  }\n]", 
  "method": "GET", 
  "parameters": null, 
  "path_parameters": [
    {
      "description": "the slug of the organization the client keys belong to.", 
      "name": "organization_slug", 
      "type": "string"
    }, 
    {
      "description": "the slug of the project the client keys belong to.", 
      "name": "project_slug", 
      "type": "string"
    }
  ], 
  "query_parameters": null, 
  "sidebar_order": 12, 
  "title": "List a Project's Client Keys", 
  "warning": null
}
---
