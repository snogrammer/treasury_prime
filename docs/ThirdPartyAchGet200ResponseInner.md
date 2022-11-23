# OpenapiClient::ThirdPartyAchGet200ResponseInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **description** | [**Ascii**](Ascii.md) |  | [optional] |
| **amount** | **String** |  | [optional] |
| **service** | [**Enum**](Enum.md) |  | [optional] |
| **bankdata** | **Object** |  | [optional] |
| **bank_id** | **String** |  | [optional] |
| **addenda** | **Array** |  | [optional] |
| **org_id** | **String** |  | [optional] |
| **effective_date** | **Date** |  | [optional] |
| **status** | **String** |  | [optional] |
| **id** | **String** |  | [optional] |
| **credit_counterparty_id** | **String** |  | [optional] |
| **error** | **String** |  | [optional] |
| **debit_counterparty_id** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ThirdPartyAchGet200ResponseInner.new(
  description: null,
  amount: null,
  service: null,
  bankdata: null,
  bank_id: null,
  addenda: null,
  org_id: null,
  effective_date: null,
  status: null,
  id: null,
  credit_counterparty_id: null,
  error: null,
  debit_counterparty_id: null,
  userdata: null
)
```

