{
  "info": {
    "name": "BBC Nitro Look inside pips entities",
    "_postman_id": "81db7603-a4b6-45c0-b2ae-2dd6912e1f90",
    "description": "Look inside pips entities",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Folder",
      "item": [
        {
          "id": "b598b63e-ebc3-417b-8d54-680ac4a88bb6",
          "name": "getAPI",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get API definition"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77b77681-ca9d-4b13-8eba-291ac44bea05"
            }
          ]
        }
      ]
    },
    {
      "name": "Availabilities",
      "item": [
        {
          "id": "2a4726af-6fd3-48b8-9aff-9c49df064bde",
          "name": "listAvailability",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/availabilities?availability=%7B%7D&debug=%7B%7D&descendants_of=%7B%7D&media_set=%7B%7D&page=%7B%7D&page_size=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D&territory=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Discover details of on-demand availability for programmes and their versions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f212314-de6c-4384-a9af-a66caad3aa4f"
            }
          ]
        }
      ]
    },
    {
      "name": "Broadcasts",
      "item": [
        {
          "id": "86601a20-7394-4a8a-af36-f11fa9b7d48c",
          "name": "listBroadcasts",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/broadcasts?authority=%7B%7D&descendants_of=%7B%7D&end_from=%7B%7D&end_to=%7B%7D&format=%7B%7D&genre=%7B%7D&id=%7B%7D&item=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&people=%7B%7D&pid=%7B%7D&q=%7B%7D&schedule_day=%7B%7D&schedule_day_from=%7B%7D&schedule_day_to=%7B%7D&service_master_brand=%7B%7D&sid=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D&start_from=%7B%7D&start_to=%7B%7D&version=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Fetch metadata about linear Broadcasts and Services, allowing the generation of Television and Radio schedules and other datasets for broadcast items. Use /schedules instead of this feed as it is more efficient. Broadcasts will be deprecated in the future."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6fd37db7-8368-4f25-85bf-228962ca0b8f"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "b45f55ad-2039-43b8-84f4-cf84d2d83f90",
          "name": "listGroups",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/groups?embargoed=%7B%7D&for_descendants_of=%7B%7D&for_programme=%7B%7D&group=%7B%7D&group_type=%7B%7D&member=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&pid=%7B%7D&q=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Long-lived curated collections of programmes and more, including Collections, Seasons, Franchises and Galleries"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13470ee5-85e9-477a-9690-59741d55b24e"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "e45d51d1-71e2-40f7-be1f-2a24c1eb2861",
          "name": "listImages",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/images?embargoed=%7B%7D&group=%7B%7D&image_type=%7B%7D&is_alternate_image_for=%7B%7D&is_image_for=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&pid=%7B%7D&q=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Find metadata for images, particularly those in galleries"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a7e7d16b-5ae3-4bb0-9bc8-28981c05972e"
            }
          ]
        }
      ]
    },
    {
      "name": "Items",
      "item": [
        {
          "id": "374aa4c5-787b-41c5-9301-9c224a288f61",
          "name": "listItems",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/items?authority=%7B%7D&id=%7B%7D&id_type=%7B%7D&item_type=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&people=%7B%7D&pid=%7B%7D&programme=%7B%7D&q=%7B%7D&segment_event=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Look inside programmes to find segments: chapters, tracks and more"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a282921-4f53-4414-bbf8-271d2391286f"
            }
          ]
        }
      ]
    },
    {
      "name": "Master",
      "item": [
        {
          "id": "0f6358e7-229a-416b-b033-d8f6de42e41e",
          "name": "listMasterbrands",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/master_brands?mid=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&q=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all Master Brands"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "28f4d0fd-918a-4898-9e3f-8effe63ec8a3"
            }
          ]
        }
      ]
    },
    {
      "name": "People",
      "item": [
        {
          "id": "17f82920-2d75-4896-a332-e891426efd72",
          "name": "listPeople",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/people?authority=%7B%7D&has_external_id=%7B%7D&id=%7B%7D&id_type=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&pid=%7B%7D&programme=%7B%7D&q=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The People feed allows you to search for the people and groups that contribute to programmes. This is the starting point for cast and crew credits, as well as finding contributors using external IDs (such as Wikipedia URLs)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da014cc7-bfee-4b1c-8cda-6504c8c2ffc8"
            }
          ]
        }
      ]
    },
    {
      "name": "Pips",
      "item": [
        {
          "id": "ad8ed5f9-9f5f-40c5-89d0-96669661f5a7",
          "name": "listPips",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/pips?page=%7B%7D&page_size=%7B%7D&q=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Look inside pips entities"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eaa2be63-ab7e-40c1-bfd2-f283675b32fb"
            }
          ]
        }
      ]
    }
  ]
}