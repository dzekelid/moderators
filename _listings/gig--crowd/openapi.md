swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/admin/moderator/statistic:
    get:
      summary: Get Admin Moderator Statistic
      description: Get admin moderator statistic.
      operationId: getApiV1AdminModeratorStatistic
      x-api-path-slug: apiv1adminmoderatorstatistic-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Moderator
      - Statistic