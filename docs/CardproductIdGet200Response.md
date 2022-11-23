# OpenapiClient::CardproductIdGet200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **card_back_image_file_id** | **String** |  | [optional] |
| **type** | [**Enum**](Enum.md) |  | [optional] |
| **card_front_image_file_id** | **String** |  | [optional] |
| **card_controls** | [**Struct**](Struct.md) |  | [optional] |
| **status** | [**Enum**](Enum.md) |  | [optional] |
| **id** | **String** |  | [optional] |
| **card_auth_loop_endpoint_id** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::CardproductIdGet200Response.new(
  card_back_image_file_id: null,
  type: null,
  card_front_image_file_id: null,
  card_controls: null,
  status: null,
  id: null,
  card_auth_loop_endpoint_id: null,
  userdata: null
)
```

