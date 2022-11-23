# OpenapiClient::WireGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **amount** | **String** |  |  |
| **counterparty_id** | **String** |  |  |
| **bankdata** | **Object** |  | [optional] |
| **account_id** | **String** |  |  |
| **instructions** | **String** |  | [optional] |
| **intermediary** | [**Struct**](Struct.md) |  | [optional] |
| **status** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::WireGetRequest.new(
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

