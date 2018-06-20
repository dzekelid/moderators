---
name: SoundCloud
x-slug: soundcloud
description: SoundCloud is a music and podcast streaming platform that lets you listen
  to millions of songs from around the world, or upload your own. Start listening
  now!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
x-kinRank: "9"
x-alexaRank: "114"
tags: Moderators
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/moderators/master/_listings/soundcloud/apis.md
specificationVersion: "0.14"
apis:
- name: Sound Cloud Get Groups Moderators
  x-api-slug: sound-cloud
  description: Returns a collection of moderators of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/moderators.json
  tags: Groups,Moderators
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/moderators/master/_listings/soundcloud/groupsgroup-idmoderators-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/moderators/master/_listings/soundcloud/groupsgroup-idmoderators-json-get-openapi.md
- name: Sound Cloud Get Groups Moderators. Format
  x-api-slug: sound-cloud
  description: Returns a collection of moderators of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/moderators.{format}
  tags: Groups,Moderators,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/moderators/master/_listings/soundcloud/groupsgroup-idmoderators-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/moderators/master/_listings/soundcloud/groupsgroup-idmoderators-format-get-openapi.md
- name: Sound Cloud
  x-api-slug: sound-cloud
  description: SoundCloud is a music and podcast streaming platform that lets you
    listen to millions of songs from around the world, or upload your own. Start listening
    now!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com//
  tags: Moderators
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/moderators/master/_listings/soundcloud/openapi.md
x-common:
- type: x-base
  url: https://api.soundcloud.com
- type: x-blog
  url: http://blog.soundcloud.com
- type: x-blog-rss
  url: http://blog.soundcloud.com/feed/
- type: x-console
  url: https://developers.soundcloud.com/console
- type: x-crunchbase
  url: https://crunchbase.com/organization/soundcloud
- type: x-crunchbase
  url: http://www.crunchbase.com/company/soundcloud
- type: x-developer
  url: http://developers.soundcloud.com
- type: x-github
  url: https://github.com/soundcloud
- type: x-pricing
  url: https://on.soundcloud.com/
- type: x-privacy
  url: https://soundcloud.com/pages/privacy
- type: x-support
  url: https://soundcloud.com/imprint
- type: x-terms-of-service
  url: https://soundcloud.com/terms-of-use
- type: x-twitter
  url: https://twitter.com/soundcloudapi
- type: x-twitter
  url: https://twitter.com/SoundCloud
- type: x-website
  url: http://soundcloud.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---