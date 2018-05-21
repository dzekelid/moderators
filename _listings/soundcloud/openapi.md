---
swagger: "2.0"
x-collection-name: SoundCloud
x-complete: 1
info:
  title: SoundCloud
  description: access-host-upload-and-comment-on-audio
  version: 1.0.0
host: api.soundcloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /groups/{group_id}/moderators.json:
    get:
      summary: Get Group Moderators
      description: Returns a collection of moderators of the group with group id
      operationId: groups.group_id.moderators.json.get
      x-api-path-slug: groupsgroup-idmoderatorsjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Groups
      - Moderators
---