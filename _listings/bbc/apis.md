---
name: BBC
x-slug: bbc
description: Breaking news, sport, TV, radio and a whole lot more. The BBC informs,
  educates and entertains - wherever you are, whatever your age.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
x-kinRank: "7"
x-alexaRank: "93"
tags: BBC
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/apis.md
specificationVersion: "0.14"
apis:
- name: BBC Nitro Get API definition
  x-api-slug: bbc-nitro
  description: Get API definition
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//
  tags: ""
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/get-openapi.md
- name: BBC Nitro Discover details of on-demand availability for programmes and their
    versions
  x-api-slug: bbc-nitro
  description: Discover details of on-demand availability for programmes and their
    versions
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//availabilities
  tags: Availabilities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/availabilities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/availabilities-get-openapi.md
- name: BBC Nitro Build schedules and find metadata for TV and radio broadcasts
  x-api-slug: bbc-nitro
  description: Fetch metadata about linear Broadcasts and Services, allowing the generation
    of Television and Radio schedules and other datasets for broadcast items. Use
    /schedules instead of this feed as it is more efficient. Broadcasts will be deprecated
    in the future.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//broadcasts
  tags: Broadcasts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/broadcasts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/broadcasts-get-openapi.md
- name: 'BBC Nitro Find metadata for curated groups: seasons, collections, galleries
    or franchises'
  x-api-slug: bbc-nitro
  description: Long-lived curated collections of programmes and more, including Collections,
    Seasons, Franchises and Galleries
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//groups
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/groups-get-openapi.md
- name: BBC Nitro Find metadata for images
  x-api-slug: bbc-nitro
  description: Find metadata for images, particularly those in galleries
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//images
  tags: Images
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/images-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/images-get-openapi.md
- name: 'BBC Nitro Look inside programmes to find segments: chapters, tracks and more'
  x-api-slug: bbc-nitro
  description: 'Look inside programmes to find segments: chapters, tracks and more'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//items
  tags: Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/items-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/items-get-openapi.md
- name: BBC Nitro List all Master Brands
  x-api-slug: bbc-nitro
  description: List all Master Brands
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//master_brands
  tags: Master,Brands
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/master-brands-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/master-brands-get-openapi.md
- name: 'BBC Nitro Find the people behind and in programmes: cast, crew, guests and
    more'
  x-api-slug: bbc-nitro
  description: The People feed allows you to search for the people and groups that
    contribute to programmes. This is the starting point for cast and crew credits,
    as well as finding contributors using external IDs (such as Wikipedia URLs)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//people
  tags: People
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/people-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/people-get-openapi.md
- name: BBC Nitro Look inside pips entities
  x-api-slug: bbc-nitro
  description: Look inside pips entities
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//pips
  tags: Pips
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/pips-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/pips-get-openapi.md
- name: BBC Nitro Exposes programme information for a single pid
  x-api-slug: bbc-nitro
  description: Exposes programme information for a single pid
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//programme_details
  tags: Programme,Details
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/programme-details-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/programme-details-get-openapi.md
- name: 'BBC Nitro Start here for programmes metadata: Brands, Series, Episodes and
    Clips'
  x-api-slug: bbc-nitro
  description: Fetch metadata about Programmes (brands, series, episodes, clips).
    By applying different filter restrictions this feed can be used in many ways,
    for example to retrieve all series belonging to a brand, all the episodes and/or
    clips for a specific series, or any TLEO objects for a masterbrand. Other filters
    permit restricting to specific formats and/or genres, and you can request specific
    versions (for example Signed or Audio-Described). Parameters may be combined in
    any way suitable for your application.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//programmes
  tags: Programmes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/programmes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/programmes-get-openapi.md
- name: BBC Nitro Discover metadata for content promotions
  x-api-slug: bbc-nitro
  description: Details of short-term editorially curated "promotions", for instance
    those programmes featured on iPlayer today
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//promotions
  tags: Promotions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/promotions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/promotions-get-openapi.md
- name: BBC Nitro Build schedules and find metadata for TV and radio broadcasts and
    webcasts
  x-api-slug: bbc-nitro
  description: 'Dates, Times, Schedules: when and where are programmes being shown?'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//schedules
  tags: Schedules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/schedules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/schedules-get-openapi.md
- name: BBC Nitro Get Schema definition
  x-api-slug: bbc-nitro
  description: Get Schema definition
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//schema
  tags: Schema
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/schema-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/schema-get-openapi.md
- name: BBC Nitro Information about the linear services used for broadcast transmissions
  x-api-slug: bbc-nitro
  description: The services feed exposes the linear broadcast "services" from PIPs.
    These are the actual services which broadcast programmes (eg bbc_one_oxford is
    the service for BBC One in Oxford).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//services
  tags: Services
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/services-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/services-get-openapi.md
- name: BBC Nitro Get raw brand
  x-api-slug: bbc-nitro
  description: Get raw brand
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//v1/brands/{pid}
  tags: V1,Brands,Pid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1brandspid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1brandspid-get-openapi.md
- name: BBC Nitro Get raw brand franchise
  x-api-slug: bbc-nitro
  description: Get raw brand franchises
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//v1/brands/{pid}/franchises/
  tags: V1,Brands,Pid,Franchises
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1brandspidfranchises-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1brandspidfranchises-get-openapi.md
- name: BBC Nitro Get raw episode
  x-api-slug: bbc-nitro
  description: Get raw episode
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//v1/episodes/{pid}
  tags: V1,Episodes,Pid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1episodespid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1episodespid-get-openapi.md
- name: BBC Nitro Get raw ancestors
  x-api-slug: bbc-nitro
  description: Get raw ancestors
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//v1/episodes/{pid}/ancestors/
  tags: V1,Episodes,Pid,Ancestors
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1episodespidancestors-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1episodespidancestors-get-openapi.md
- name: BBC Nitro Get raw formats
  x-api-slug: bbc-nitro
  description: Get raw formats
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//v1/episodes/{pid}/formats/
  tags: V1,Episodes,Pid,Formats
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1episodespidformats-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1episodespidformats-get-openapi.md
- name: BBC Nitro Get raw genre groups
  x-api-slug: bbc-nitro
  description: Get raw genre groups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//v1/episodes/{pid}/genre_groups/
  tags: V1,Episodes,Pid,Genre,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1episodespidgenre-groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1episodespidgenre-groups-get-openapi.md
- name: BBC Nitro Get raw image
  x-api-slug: bbc-nitro
  description: Get raw image
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//v1/images/{pid}
  tags: V1,Images,Pid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1imagespid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1imagespid-get-openapi.md
- name: BBC Nitro Get raw masterbrand
  x-api-slug: bbc-nitro
  description: Get raw masterbrand
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//v1/master_brands/{mbid}
  tags: V1,Master,Brands,Mbid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1master-brandsmbid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1master-brandsmbid-get-openapi.md
- name: BBC Nitro Get raw promotion
  x-api-slug: bbc-nitro
  description: Get raw promotion
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//v1/promotions/{pid}
  tags: V1,Promotions,Pid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1promotionspid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/v1promotionspid-get-openapi.md
- name: 'BBC Nitro Metadata on editorial programme versions: original, signed, audio-described,
    etc'
  x-api-slug: bbc-nitro
  description: 'The versions feed exposes editorial "Versions" of programmes. These
    are concepts used to capture different presentations of an overall programme:
    for example, versions of a programme may include one with sign language, one with
    audio description, one edited for content and more. Versions are also important
    to understand for broadcasts: a linear broadcast or an ondemand is always of a
    specific version, not merely of a programme.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//versions
  tags: Versions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/versions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/versions-get-openapi.md
- name: BBC Nitro
  x-api-slug: bbc-nitro
  description: Breaking news, sport, TV, radio and a whole lot more. The BBC informs,
    educates and entertains - wherever you are, whatever your age.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api
  tags: BBC
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bbc/master/_listings/bbc/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/bbc-news
- type: x-email
  url: dataprotection@bbc.com
- type: x-email
  url: bbcworldwidelearning@bbc.com
- type: x-twitter
  url: https://twitter.com/BBCNews
- type: x-website
  url: http://www.bbc.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---