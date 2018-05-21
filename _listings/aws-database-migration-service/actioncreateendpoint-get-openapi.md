---
swagger: "2.0"
x-collection-name: AWS Database Migration Service
x-complete: 0
info:
  title: AWS Database Migration Service API Create Endpoint
  version: 1.0.0
  description: Creates an endpoint using the provided settings.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddTagsToResource:
    get:
      summary: Add Tags To Resource
      description: Adds metadata tags to a DMS resource, including replication instance,
        endpoint, security group, and migration task.
      operationId: addTagsToResource
      x-api-path-slug: actionaddtagstoresource-get
      parameters:
      - in: query
        name: ResourceArn
        description: The Amazon Resource Name (ARN) of the AWS DMS resource the tag
          is to be added to
        type: string
      - in: query
        name: Tags
        description: The tag to be assigned to the DMS resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Resource Tags
  /?Action=CreateEndpoint:
    get:
      summary: Create Endpoint
      description: Creates an endpoint using the provided settings.
      operationId: createEndpoint
      x-api-path-slug: actioncreateendpoint-get
      parameters:
      - in: query
        name: CertificateArn
        description: The Amazon Resource Number (ARN) for the certificate
        type: string
      - in: query
        name: DatabaseName
        description: The name of the endpoint database
        type: string
      - in: query
        name: EndpointIdentifier
        description: The database endpoint identifier
        type: string
      - in: query
        name: EndpointType
        description: The type of endpoint
        type: string
      - in: query
        name: EngineName
        description: The type of engine for the endpoint
        type: string
      - in: query
        name: ExtraConnectionAttributes
        description: Additional attributes associated with the connection
        type: string
      - in: query
        name: KmsKeyId
        description: The KMS key identifier that will be used to encrypt the connection
          parameters
        type: string
      - in: query
        name: Password
        description: The password to be used to login to the endpoint database
        type: string
      - in: query
        name: Port
        description: The port used by the endpoint database
        type: string
      - in: query
        name: ServerName
        description: The name of the server where the endpoint database resides
        type: string
      - in: query
        name: SslMode
        description: The SSL mode to use for the SSL connection
        type: string
      - in: query
        name: Tags
        description: Tags to be added to the endpoint
        type: string
      - in: query
        name: Username
        description: The user name to be used to login to the endpoint database
        type: string
      responses:
        200:
          description: OK
      tags:
      - Endpoints
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