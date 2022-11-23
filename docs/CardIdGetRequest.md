# OpenapiClient::CardIdGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_id** | **String** |  | [optional] |
| **person_id** | **String** |  | [optional] |
| **card_product_id** | **String** |  | [optional] |
| **card_controls** | [**Struct**](Struct.md) |  | [optional] |
| **status** | [**Enum**](Enum.md) |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::CardIdGetRequest.new(
  account_id: null,
  person_id: null,
  card_product_id: null,
  card_controls: null,
  status: null,
  userdata: null
)
```

