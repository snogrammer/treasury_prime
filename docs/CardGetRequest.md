# OpenapiClient::CardGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_id** | **String** |  |  |
| **person_id** | **String** |  |  |
| **card_product_id** | **String** |  |  |
| **card_controls** | [**Struct**](Struct.md) |  | [optional] |
| **status** | [**Enum**](Enum.md) |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::CardGetRequest.new(
  account_id: null,
  person_id: null,
  card_product_id: null,
  card_controls: null,
  status: null,
  userdata: null
)
```

