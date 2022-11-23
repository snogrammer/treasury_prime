# OpenapiClient::AchIdGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **description** | [**Ascii**](Ascii.md) |  | [optional] |
| **amount** | **String** |  | [optional] |
| **service** | [**Enum**](Enum.md) |  | [optional] |
| **counterparty_id** | **String** |  | [optional] |
| **bankdata** | **Object** |  | [optional] |
| **account_id** | **String** |  | [optional] |
| **addenda** | **Array** |  | [optional] |
| **batch_key** | **String** |  | [optional] |
| **status** | **String** |  | [optional] |
| **sec_code** | [**Enum**](Enum.md) |  | [optional] |
| **direction** | [**Enum**](Enum.md) |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AchIdGetRequest.new(
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

