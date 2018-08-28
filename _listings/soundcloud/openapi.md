swagger: "2.0"
x-collection-name: SoundCloud
x-complete: 1
info:
  title: Sound Cloud
  description: access-host-upload-and-comment-on-audio-
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
      summary: Get Groups Moderators
      description: Returns a collection of moderators of the group with group id
      operationId: getGroupsGroupModerators.json
      x-api-path-slug: groupsgroup-idmoderators-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Moderators
  /groups/{group_id}/moderators.{format}:
    get:
      summary: Get Groups Moderators. Format
      description: Returns a collection of moderators of the group with group id
      operationId: getGroupsGroupModerators.Format
      x-api-path-slug: groupsgroup-idmoderators-format-get
      parameters:
      - in: query
        name: consumer_key
        description: Access, host, upload, and comment on audio
      - in: query
        name: playlist_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Moderators
      - ""
      - Format