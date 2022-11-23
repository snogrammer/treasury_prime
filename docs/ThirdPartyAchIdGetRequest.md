# OpenapiClient::ThirdPartyAchIdGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **description** | [**Ascii**](Ascii.md) |  | [optional] |
| **amount** | **String** |  | [optional] |
| **service** | [**Enum**](Enum.md) |  | [optional] |
| **bankdata** | **Object** |  | [optional] |
| **addenda** | **Array** |  | [optional] |
| **status** | **String** |  | [optional] |
| **credit_counterparty_id** | **String** |  | [optional] |
| **debit_counterparty_id** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ThirdPartyAchIdGetRequest.new(
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

