# OpenapiClient::ApplyDepositGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **amount** | **String** |  |  |
| **ach** | [**Struct**](Struct.md) |  | [optional] |
| **name_on_account** | **String** |  |  |
| **card** | [**Struct**](Struct.md) |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ApplyDepositGetRequest.new(
  amount: null,
  ach: null,
  name_on_account: null,
  card: null,
  userdata: null
)
```

