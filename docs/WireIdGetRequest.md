# OpenapiClient::WireIdGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **amount** | **String** |  | [optional] |
| **counterparty_id** | **String** |  | [optional] |
| **bankdata** | **Object** |  | [optional] |
| **account_id** | **String** |  | [optional] |
| **instructions** | **String** |  | [optional] |
| **intermediary** | [**Struct**](Struct.md) |  | [optional] |
| **status** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::WireIdGetRequest.new(
  amount: null,
  counterparty_id: null,
  bankdata: null,
  account_id: null,
  instructions: null,
  intermediary: null,
  status: null,
  userdata: null
)
```

