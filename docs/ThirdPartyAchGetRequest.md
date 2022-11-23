# OpenapiClient::ThirdPartyAchGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **description** | [**Ascii**](Ascii.md) |  | [optional] |
| **amount** | **String** |  |  |
| **service** | [**Enum**](Enum.md) |  |  |
| **bankdata** | **Object** |  | [optional] |
| **addenda** | **Array** |  | [optional] |
| **status** | **String** |  | [optional] |
| **credit_counterparty_id** | **String** |  |  |
| **debit_counterparty_id** | **String** |  |  |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ThirdPartyAchGetRequest.new(
  description: null,
  amount: null,
  service: null,
  bankdata: null,
  addenda: null,
  status: null,
  credit_counterparty_id: null,
  debit_counterparty_id: null,
  userdata: null
)
```

