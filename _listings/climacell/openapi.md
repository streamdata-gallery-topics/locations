---
swagger: "2.0"
x-collection-name: ClimaCell
x-complete: 1
info:
  title: ClimaCell API
  description: the-climacell-rest-api-provides-access-to-high-resolution-weather-data-for-locations-across-the-u-s--with-global-data-coming-soon--it-uses-https-and-requires-an-access-token-key--the-api-requests-carry-query-parameters-and-the-responses-return-results-in-json-format-
  version: 1.0.0
host: api2.climacell.co
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /locations:
    get:
      summary: Get Locations
      description: |-
        ### List all Locations
        Pages through the list of the Locations for your user account. You can specify the maximum number of results to be retuned, and from which result to start.
      operationId: -list-all-locationspages-through-the-list-of-the-locations-for-your-user-account-you-can-specify-the
      x-api-path-slug: locations-get
      parameters:
      - in: query
        name: limit
        description: The maximum number of records to load
      - in: query
        name: offset
        description: The number of records to skip
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
    post:
      summary: Post Locations
      description: |-
        ### Create a Location

        Creates a new Location in your organization, and name it. The name of the location is used in the notifications for triggered alerts at the location.
        ###
        The system attaches a unique ID to each location you create. This ID is used to refer to the location and manage it in the following ```locations``` API calls.
      operationId: -create-a-locationcreates-a-new-location-in-your-organization-and-name-it-the-name-of-the-location-i
      x-api-path-slug: locations-post
      parameters:
      - in: body
        name: location
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
  /locations/{location_id}:
    get:
      summary: Get Locations Location
      description: |-
        ### Retrieve a Location

        Get a single location back with its information by specifying its ```location_id```.
      operationId: -retrieve-a-locationget-a-single-location-back-with-its-information-by-specifying-its-location-id
      x-api-path-slug: locationslocation-id-get
      parameters:
      - in: path
        name: location_id
        description: UUID of the Location
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
      - Location
    put:
      summary: Put Locations Location
      description: |-
        ### Update a Location

        Updates the details of a Location designated by its ```location_id```.
      operationId: -update-a-locationupdates-the-details-of-a-location-designated-by-its-location-id
      x-api-path-slug: locationslocation-id-put
      parameters:
      - in: body
        name: location
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: UUID of the Location
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
      - Location
    delete:
      summary: Delete Locations Location
      description: |-
        ### Delete a Location

        Removes a location with the ```location_id``` from the system. If the location was part of any alert, the alert is removed.
      operationId: -delete-a-locationremoves-a-location-with-the-location-id-from-the-system-if-the-location-was-part-o
      x-api-path-slug: locationslocation-id-delete
      parameters:
      - in: path
        name: location_id
        description: UUID of the Location
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
      - Location
---