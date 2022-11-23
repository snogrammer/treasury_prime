# OpenapiClient::AchGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **description** | [**Ascii**](Ascii.md) |  | [optional] |
| **amount** | **String** |  |  |
| **service** | [**Enum**](Enum.md) |  |  |
| **counterparty_id** | **String** |  |  |
| **bankdata** | **Object** |  | [optional] |
| **account_id** | **String** |  |  |
| **addenda** | **Array** |  | [optional] |
| **batch_key** | **String** |  | [optional] |
| **status** | **String** |  | [optional] |
| **sec_code** | [**Enum**](Enum.md) |  |  |
| **direction** | [**Enum**](Enum.md) |  |  |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AchGetRequest.new(
  description: null,
  amount: null,
  service: null,
  counterparty_id: null,
  bankdata: null,
  account_id: null,
  addenda: null,
  batch_key: null,
  status: null,
  sec_code: null,
  direction: null,
  userdata: null
)
```

