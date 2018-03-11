---
swagger: "2.0"
info:
  title: AWS Database Migration Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=StopReplicationTask&k=1:
    get:
      summary: ' Stop Replication Task '
      description: Stops the replication task
      operationId: stopReplicationTask
      parameters:
      - in: query
        name: ReplicationTaskArn
        description: The Amazon Resource Number(ARN) of the replication task to be
          stopped
        type: string
      responses:
        200:
          description: OK
      tags:
      - replication tasks
definitions: []
x-collection-name: AWS Database Migration Service
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