---
name: AWS Database Migration Service
x-slug: aws-database-migration-service
description: AWS Database Migration Service helps you migrate databases to AWS easily
  and securely. The source database remains fully operational during the migration,
  minimizing downtime to applications that rely on the database. The AWS Database
  Migration Service can migrate your data to and from most widely used commercial
  and open-source databases. The service supports homogenous migrations such as Oracle
  to Oracle, as well as heterogeneous migrations between different database platforms,
  such as Oracle to Amazon Aurora or Microsoft SQL Server to MySQL. It also allows
  you to stream data to Amazon Redshift from any of the supported sources including
  Amazon Aurora, PostgreSQL, MySQL, MariaDB, Oracle, SAP ASE and SQL Server, enabling
  consolidation and easy analysis of data in the petabyte-scale data warehouse. AWS
  Database Migration Service can also be used for continuous data replication with
  high-availability.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Database Migration Service
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Database Migration Service API Add Tags To Resource
  x-api-slug: aws-database-migration-service-api
  description: Adds metadata tags to a DMS resource, including replication instance,
    endpoint, security group, and migration task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=AddTagsToResource
  tags: Resource Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actionaddtagstoresource-get-openapi.md
- name: AWS Database Migration Service API Create Endpoint
  x-api-slug: aws-database-migration-service-api
  description: Creates an endpoint using the provided settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=CreateEndpoint
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actioncreateendpoint-get-openapi.md
- name: AWS Database Migration Service API Create Replication Instance
  x-api-slug: aws-database-migration-service-api
  description: Creates the replication instance using the specified parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=CreateReplicationInstance
  tags: Replication Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actioncreatereplicationinstance-get-openapi.md
- name: AWS Database Migration Service API Create Replication Subnet Group
  x-api-slug: aws-database-migration-service-api
  description: Creates a replication subnet group given a list of the subnet IDs in
    a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=CreateReplicationSubnetGroup
  tags: Replication Subnet Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actioncreatereplicationsubnetgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actioncreatereplicationsubnetgroup-get-openapi.md
- name: AWS Database Migration Service API Create Replication Task
  x-api-slug: aws-database-migration-service-api
  description: Creates a replication task using the specified parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=CreateReplicationTask
  tags: Replication Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actioncreatereplicationtask-get-openapi.md
- name: AWS Database Migration Service API Delete Certificate
  x-api-slug: aws-database-migration-service-api
  description: Deletes the specified certificate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DeleteCertificate
  tags: Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondeletecertificate-get-openapi.md
- name: AWS Database Migration Service API Delete Endpoint
  x-api-slug: aws-database-migration-service-api
  description: Deletes the specified endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DeleteEndpoint
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondeleteendpoint-get-openapi.md
- name: AWS Database Migration Service API Delete Replication Instance
  x-api-slug: aws-database-migration-service-api
  description: Deletes the specified replication instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DeleteReplicationInstance
  tags: Replication Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondeletereplicationinstance-get-openapi.md
- name: AWS Database Migration Service API Delete Replication Subnet Group
  x-api-slug: aws-database-migration-service-api
  description: Deletes a subnet group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DeleteReplicationSubnetGroup
  tags: Replication Subnet Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondeletereplicationsubnetgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondeletereplicationsubnetgroup-get-openapi.md
- name: AWS Database Migration Service API Delete Replication Task
  x-api-slug: aws-database-migration-service-api
  description: Deletes the specified replication task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DeleteReplicationTask
  tags: Replication Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondeletereplicationtask-get-openapi.md
- name: AWS Database Migration Service API Describe Account Attributes
  x-api-slug: aws-database-migration-service-api
  description: Lists all of the AWS DMS attributes for a customer account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DescribeAccountAttributes
  tags: Account Attributes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribeaccountattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribeaccountattributes-get-openapi.md
- name: AWS Database Migration Service API Describe Certificates
  x-api-slug: aws-database-migration-service-api
  description: Provides a description of the certificate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DescribeCertificates
  tags: Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribecertificates-get-openapi.md
- name: AWS Database Migration Service API Describe Connections
  x-api-slug: aws-database-migration-service-api
  description: Describes the status of the connections that have been made between
    the replication instance and an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DescribeConnections
  tags: Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribeconnections-get-openapi.md
- name: AWS Database Migration Service API Describe Endpoints
  x-api-slug: aws-database-migration-service-api
  description: Returns information about the endpoints for your account in the current
    region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DescribeEndpoints
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribeendpoints-get-openapi.md
- name: AWS Database Migration Service API Describe Endpoint Types
  x-api-slug: aws-database-migration-service-api
  description: Returns information about the type of endpoints available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DescribeEndpointTypes
  tags: Endpoint Types
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribeendpointtypes-get-openapi.md
- name: AWS Database Migration Service API Describe Orderable Replication Instances
  x-api-slug: aws-database-migration-service-api
  description: Returns information about the replication instance types that can be
    created in the specified region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DescribeOrderableReplicationInstances
  tags: Replication Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribeorderablereplicationinstances-get-openapi.md
- name: AWS Database Migration Service API Describe Refresh Schemas Status
  x-api-slug: aws-database-migration-service-api
  description: Returns the status of the RefreshSchemas operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DescribeRefreshSchemasStatus
  tags: Schemas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescriberefreshschemasstatus-get-openapi.md
- name: AWS Database Migration Service API Describe Replication Instances
  x-api-slug: aws-database-migration-service-api
  description: Returns information about replication instances for your account in
    the current region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DescribeReplicationInstances
  tags: Replication Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribereplicationinstances-get-openapi.md
- name: AWS Database Migration Service API Describe Replication Subnet Groups
  x-api-slug: aws-database-migration-service-api
  description: Returns information about the replication subnet groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DescribeReplicationSubnetGroups
  tags: Replication Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribereplicationsubnetgroups-get-openapi.md
- name: AWS Database Migration Service API Describe Replication Tasks
  x-api-slug: aws-database-migration-service-api
  description: Returns information about replication tasks for your account in the
    current region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DescribeReplicationTasks
  tags: Replication Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribereplicationtasks-get-openapi.md
- name: AWS Database Migration Service API Describe Schemas
  x-api-slug: aws-database-migration-service-api
  description: Returns information about the schema for the specified endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DescribeSchemas
  tags: Schemas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribeschemas-get-openapi.md
- name: AWS Database Migration Service API Describe Table Statistics
  x-api-slug: aws-database-migration-service-api
  description: Returns table statistics on the database migration task, including
    table name, rows inserted, rows updated, and rows deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=DescribeTableStatistics
  tags: Table Statistics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribetablestatistics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiondescribetablestatistics-get-openapi.md
- name: AWS Database Migration Service API Import Certificate
  x-api-slug: aws-database-migration-service-api
  description: Uploads the specified certificate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=ImportCertificate
  tags: Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actionimportcertificate-get-openapi.md
- name: AWS Database Migration Service API List Tags For Resource
  x-api-slug: aws-database-migration-service-api
  description: Lists all tags for an AWS DMS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=ListTagsForResource
  tags: Resource Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actionlisttagsforresource-get-openapi.md
- name: AWS Database Migration Service API Modify Endpoint
  x-api-slug: aws-database-migration-service-api
  description: Modifies the specified endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=ModifyEndpoint
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actionmodifyendpoint-get-openapi.md
- name: AWS Database Migration Service API Modify Replication Instance
  x-api-slug: aws-database-migration-service-api
  description: Modifies the replication instance to apply new settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=ModifyReplicationInstance
  tags: Replication Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actionmodifyreplicationinstance-get-openapi.md
- name: AWS Database Migration Service API Modify Replication Subnet Group
  x-api-slug: aws-database-migration-service-api
  description: Modifies the settings for the specified replication subnet group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=ModifyReplicationSubnetGroup
  tags: Replication Subnet Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actionmodifyreplicationsubnetgroup-get-openapi.md
- name: AWS Database Migration Service API Modify Replication Task
  x-api-slug: aws-database-migration-service-api
  description: Modifies the specified replication task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=ModifyReplicationTask
  tags: Replication Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actionmodifyreplicationtask-get-openapi.md
- name: AWS Database Migration Service API Refresh Schemas
  x-api-slug: aws-database-migration-service-api
  description: Populates the schema for the specified endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=RefreshSchemas
  tags: Schemas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actionrefreshschemas-get-openapi.md
- name: AWS Database Migration Service API Remove Tags From Resource
  x-api-slug: aws-database-migration-service-api
  description: Removes metadata tags from a DMS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=RemoveTagsFromResource
  tags: Resource Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actionremovetagsfromresource-get-openapi.md
- name: AWS Database Migration Service API Start Replication Task
  x-api-slug: aws-database-migration-service-api
  description: Starts the replication task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=StartReplicationTask
  tags: Replication Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actionstartreplicationtask-get-openapi.md
- name: AWS Database Migration Service API Stop Replication Task
  x-api-slug: aws-database-migration-service-api
  description: Stops the replication task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=StopReplicationTask
  tags: Replication Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actionstopreplicationtask-get-openapi.md
- name: AWS Database Migration Service API Test Connection
  x-api-slug: aws-database-migration-service-api
  description: Tests the connection between the replication instance and the endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: ://///?Action=TestConnection
  tags: Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/actiontestconnection-get-openapi.md
- name: AWS Database Migration Service API
  x-api-slug: aws-database-migration-service-api
  description: AWS Database Migration Service helps you migrate databases to AWS easily
    and securely. The source database remains fully operational during the migration,
    minimizing downtime to applications that rely on the database. The AWS Database
    Migration Service can migrate your data to and from most widely used commercial
    and open-source databases. The service supports homogenous migrations such as
    Oracle to Oracle, as well as heterogeneous migrations between different database
    platforms, such as Oracle to Amazon Aurora or Microsoft SQL Server to MySQL. It
    also allows you to stream data to Amazon Redshift from any of the supported sources
    including Amazon Aurora, PostgreSQL, MySQL, MariaDB, Oracle, SAP ASE and SQL Server,
    enabling consolidation and easy analysis of data in the petabyte-scale data warehouse.
    AWS Database Migration Service can also be used for continuous data replication
    with high-availability.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: AWS Database Migration Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-database-migration-service/master/_listings/aws-database-migration-service/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/dms/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/dms/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/dms/getting-started/
- type: x-partners
  url: https://aws.amazon.com/dms/partners/
- type: x-pricing
  url: https://aws.amazon.com/dms/pricing/
- type: x-schema-conversion
  url: https://aws.amazon.com/dms/#sct
- type: x-testimonials
  url: https://aws.amazon.com/dms/testimonials/
- type: x-website
  url: https://aws.amazon.com/dms/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---