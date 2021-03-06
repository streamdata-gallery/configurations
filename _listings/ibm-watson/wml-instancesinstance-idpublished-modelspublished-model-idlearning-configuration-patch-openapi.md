---
swagger: "2.0"
x-collection-name: IBM Watson
x-complete: 0
info:
  title: IBM Watson Machine Learning Patch Wml Instances Instance Published Models
    Published Model Learning Configuration
  description: Patch wml instances instance published models published model learning
    configuration.
  version: 1.0.0
basePath: v3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: ibm-watson-ml.mybluemix.net
paths:
  /wml_instances/{instance_id}/published_models/{published_model_id}/learning_configuration:
    put:
      summary: Put Wml Instances Instance Published Models Published Model Learning
        Configuration
      description: Put wml instances instance published models published model learning
        configuration.
      operationId: creates-learning-configuration
      x-api-path-slug: wml-instancesinstance-idpublished-modelspublished-model-idlearning-configuration-put
      parameters:
      - in: body
        name: learning_configuration
        description: The model deployment Id
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Wml
      - Instances
      - Instance
      - Id
      - Published
      - Models
      - Published
      - Model
      - Id
      - Learning
      - Configuration
    patch:
      summary: Patch Wml Instances Instance Published Models Published Model Learning
        Configuration
      description: Patch wml instances instance published models published model learning
        configuration.
      operationId: updates-the-learning-configuration-partially
      x-api-path-slug: wml-instancesinstance-idpublished-modelspublished-model-idlearning-configuration-patch
      parameters:
      - in: body
        name: learning_configuration_patch
        description: Input For Patch
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Wml
      - Instances
      - Instance
      - Id
      - Published
      - Models
      - Published
      - Model
      - Id
      - Learning
      - Configuration
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