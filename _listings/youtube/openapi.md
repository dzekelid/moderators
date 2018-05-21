---
swagger: "2.0"
x-collection-name: YouTube
x-complete: 1
info:
  title: YouTube
  description: youtube-allows-users-to-upload-view-rate-share-add-to-favorites-report-comment-on-videos-and-subscribe-to-other-users-it-offers-a-wide-variety-of-usergenerated-and-corporate-media-videos-available-content-includes-video-clips-tv-show-clips-music-videos-short-and-documentary-films-audio-recordings-movie-trailers-live-streams-and-other-content-such-as-video-blogging-short-original-videos-and-educational-videos-most-of-the-content-on-youtube-is-uploaded-by-individuals-but-media-corporations-including-cbs-the-bbc-vevo-and-hulu-offer-some-of-their-material-via-youtube-as-part-of-the-youtube-partnership-program-unregistered-users-can-only-watch-videos-on-the-site-while-registered-users-are-permitted-to-upload-an-unlimited-number-of-videos-and-add-comments-to-videos
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
    parameters:
      summary: Parameters Live Chat Moderators
      description: Parameters livechat moderators
      operationId: parametersLivechatModerators
      x-api-path-slug: livechatmoderators-parameters
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Moderators
    post:
      summary: Add Live Chat Moderators
      description: Adds a new moderator for the chat.
      operationId: postLivechatModerators
      x-api-path-slug: livechatmoderators-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Moderators
---