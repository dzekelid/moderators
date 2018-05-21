---
swagger: "2.0"
x-collection-name: YouTube
x-complete: 0
info:
  title: Youtube Get Live Chat Moderators
  description: Lists moderators for a live chat.
  termsOfService: https://developers.google.com/terms/
  contact:
    name: Google
    url: https://google.com
  version: 1.0.0
host: www.googleapis.com
basePath: /youtube/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /liveChat/moderators:
    delete:
      summary: Delete Live Chat Moderators
      description: Delete livechat moderators
      operationId: deleteLivechatModerators
      x-api-path-slug: livechatmoderators-delete
      parameters:
      - in: query
        name: id
        description: The id parameter identifies the chat moderator to remove
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Moderators
    get:
      summary: Get Live Chat Moderators
      description: Lists moderators for a live chat.
      operationId: getLivechatModerators
      x-api-path-slug: livechatmoderators-get
      parameters:
      - in: query
        name: liveChatId
        description: The liveChatId parameter specifies the YouTube live chat for
          which the API should return moderators
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of items
          that should be returned in the result set
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: part
        description: The part parameter specifies the liveChatModerator resource parts
          that the API response will include
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Moderators
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