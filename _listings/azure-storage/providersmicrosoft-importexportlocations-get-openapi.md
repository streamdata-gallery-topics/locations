---
swagger: "2.0"
x-collection-name: Azure Storage
x-complete: 0
info:
  title: Azure Storage API List Locations
  version: 1.0.0
  description: Returns a list of locations to which you can ship the disks associated
    with an import or export job. A location is a Microsoft data center region.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /providers/Microsoft.ImportExport/locations:
    get:
      summary: List Locations
      description: Returns a list of locations to which you can ship the disks associated
        with an import or export job. A location is a Microsoft data center region.
      operationId: ListLocations
      x-api-path-slug: providersmicrosoft-importexportlocations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Locations
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