---
name: Stride
x-slug: stride
description: Stride is a cloud-based team business communication and collaboration
  tool, launched by Atlassian to replace the cloud-based version of HipChat. Stride
  software is available to download onto computers running Windows, Mac or Linux,
  as well as Android, iOS smartphones, and tablets
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
x-kinRank: "8"
x-alexaRank: "40723"
tags: Sites
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/apis.md
specificationVersion: "0.14"
apis:
- name: Stride - Get conversation list for site
  x-api-slug: sitecloudidconversation-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversation-get-openapi.md
- name: Stride - Create conversation
  x-api-slug: sitecloudidconversation-post
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversation-post-openapi.md
- name: Stride - Send message to user
  x-api-slug: sitecloudidconversationuseruseridmessage-post
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationuseruseridmessage-post-openapi.md
- name: Stride - Get conversation details
  x-api-slug: sitecloudidconversationconversationid-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationid-get-openapi.md
- name: Stride - Update conversation
  x-api-slug: sitecloudidconversationconversationid-patch
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationid-patch-openapi.md
- name: Stride - Archive conversation
  x-api-slug: sitecloudidconversationconversationidarchive-put
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidarchive-put-openapi.md
- name: Stride - Upload a file
  x-api-slug: sitecloudidconversationconversationidmedia-post
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmedia-post-openapi.md
- name: Stride - Get a file
  x-api-slug: sitecloudidconversationconversationidmediamediaid-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmediamediaid-get-openapi.md
- name: Stride - Get conversation history
  x-api-slug: sitecloudidconversationconversationidmessage-get
  description: |-
    Authentication required, with scope participate:conversation

    This method returns messages after/before a given messageIDs or/and timestamps.
    If these parameters are omitted the method returns conversation???s latest messages.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessage-get-openapi.md
- name: Stride - Send a message to a conversation
  x-api-slug: sitecloudidconversationconversationidmessage-post
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessage-post-openapi.md
- name: Stride - Get latest messages for conversation
  x-api-slug: sitecloudidconversationconversationidmessagerecent-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessagerecent-get-openapi.md
- name: Stride - Get message by id
  x-api-slug: sitecloudidconversationconversationidmessagemessageid-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessagemessageid-get-openapi.md
- name: Stride - Get conversation history contextually
  x-api-slug: sitecloudidconversationconversationidmessagemessageidcontext-get
  description: |-
    Authentication required, with scope participate:conversation

    This method returns messages after and/or before a given messageID including the message itself.
    Default value for 'after' and 'before' query parameters is 0.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessagemessageidcontext-get-openapi.md
- name: Stride - Get conversation roster
  x-api-slug: sitecloudidconversationconversationidroster-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidroster-get-openapi.md
- name: Stride - Unarchive conversation
  x-api-slug: sitecloudidconversationconversationidunarchive-put
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidunarchive-put-openapi.md
- name: Stride - Get conversation list for site
  x-api-slug: sitecloudidconversation-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversation-get-openapi.md
- name: Stride - Create conversation
  x-api-slug: sitecloudidconversation-post
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversation-post-openapi.md
- name: Stride - Send message to user
  x-api-slug: sitecloudidconversationuseruseridmessage-post
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationuseruseridmessage-post-openapi.md
- name: Stride - Get conversation details
  x-api-slug: sitecloudidconversationconversationid-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationid-get-openapi.md
- name: Stride - Update conversation
  x-api-slug: sitecloudidconversationconversationid-patch
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationid-patch-openapi.md
- name: Stride - Archive conversation
  x-api-slug: sitecloudidconversationconversationidarchive-put
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidarchive-put-openapi.md
- name: Stride - Upload a file
  x-api-slug: sitecloudidconversationconversationidmedia-post
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmedia-post-openapi.md
- name: Stride - Get a file
  x-api-slug: sitecloudidconversationconversationidmediamediaid-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmediamediaid-get-openapi.md
- name: Stride - Get conversation history
  x-api-slug: sitecloudidconversationconversationidmessage-get
  description: |-
    Authentication required, with scope participate:conversation

    This method returns messages after/before a given messageIDs or/and timestamps.
    If these parameters are omitted the method returns conversation???s latest messages.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessage-get-openapi.md
- name: Stride - Send a message to a conversation
  x-api-slug: sitecloudidconversationconversationidmessage-post
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessage-post-openapi.md
- name: Stride - Get latest messages for conversation
  x-api-slug: sitecloudidconversationconversationidmessagerecent-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessagerecent-get-openapi.md
- name: Stride - Get message by id
  x-api-slug: sitecloudidconversationconversationidmessagemessageid-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessagemessageid-get-openapi.md
- name: Stride - Get conversation history contextually
  x-api-slug: sitecloudidconversationconversationidmessagemessageidcontext-get
  description: |-
    Authentication required, with scope participate:conversation

    This method returns messages after and/or before a given messageID including the message itself.
    Default value for 'after' and 'before' query parameters is 0.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessagemessageidcontext-get-openapi.md
- name: Stride - Get conversation roster
  x-api-slug: sitecloudidconversationconversationidroster-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidroster-get-openapi.md
- name: Stride - Unarchive conversation
  x-api-slug: sitecloudidconversationconversationidunarchive-put
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidunarchive-put-openapi.md
- name: Stride - Unarchive conversation
  x-api-slug: sitecloudidconversationconversationidunarchive-put
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidunarchive-put-openapi.md
- name: Stride - Get conversation roster
  x-api-slug: sitecloudidconversationconversationidroster-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidroster-get-openapi.md
- name: Stride - Get conversation history contextually
  x-api-slug: sitecloudidconversationconversationidmessagemessageidcontext-get
  description: |-
    Authentication required, with scope participate:conversation

    This method returns messages after and/or before a given messageID including the message itself.
    Default value for 'after' and 'before' query parameters is 0.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessagemessageidcontext-get-openapi.md
- name: Stride - Get message by id
  x-api-slug: sitecloudidconversationconversationidmessagemessageid-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessagemessageid-get-openapi.md
- name: Stride - Get latest messages for conversation
  x-api-slug: sitecloudidconversationconversationidmessagerecent-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessagerecent-get-openapi.md
- name: Stride - Send a message to a conversation
  x-api-slug: sitecloudidconversationconversationidmessage-post
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessage-post-openapi.md
- name: Stride - Get conversation history
  x-api-slug: sitecloudidconversationconversationidmessage-get
  description: |-
    Authentication required, with scope participate:conversation

    This method returns messages after/before a given messageIDs or/and timestamps.
    If these parameters are omitted the method returns conversation???s latest messages.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmessage-get-openapi.md
- name: Stride - Get a file
  x-api-slug: sitecloudidconversationconversationidmediamediaid-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmediamediaid-get-openapi.md
- name: Stride - Upload a file
  x-api-slug: sitecloudidconversationconversationidmedia-post
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidmedia-post-openapi.md
- name: Stride - Archive conversation
  x-api-slug: sitecloudidconversationconversationidarchive-put
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationidarchive-put-openapi.md
- name: Stride - Update conversation
  x-api-slug: sitecloudidconversationconversationid-patch
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationid-patch-openapi.md
- name: Stride - Get conversation details
  x-api-slug: sitecloudidconversationconversationid-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationconversationid-get-openapi.md
- name: Stride - Send message to user
  x-api-slug: sitecloudidconversationuseruseridmessage-post
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversationuseruseridmessage-post-openapi.md
- name: Stride - Create conversation
  x-api-slug: sitecloudidconversation-post
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversation-post-openapi.md
- name: Stride - Get conversation list for site
  x-api-slug: sitecloudidconversation-get
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Technology, Mobile, SaaS, Chats, Messages, Relative Data, Service API, Relative
    StreamRank, Streams, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/stride/sitecloudidconversation-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://strava.api.gallery.streamdata.io
- type: x-api-stack
  url: http://stride.stack.network
- type: x-authentication
  url: https://developer.atlassian.com/cloud/stride/security/authentication/
- type: x-blog
  url: https://blog.stride.com/
- type: x-buttons
  url: https://developer.atlassian.com/cloud/stride/blocks/stride-button/
- type: x-crunchbase
  url: https://crunchbase.com/organization/stride
- type: x-developer
  url: https://developer.atlassian.com/cloud/stride/
- type: x-getting-started
  url: https://developer.atlassian.com/cloud/stride/getting-started/
- type: x-pricing
  url: https://www.stride.com/pricing
- type: x-security
  url: https://developer.atlassian.com/cloud/stride/security/security-overview/
- type: x-support
  url: https://www.stride.com/help-center
- type: x-twitter
  url: https://twitter.com/atlassianstride
- type: x-website
  url: https://www.stride.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---