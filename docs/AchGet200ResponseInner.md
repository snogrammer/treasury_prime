# OpenapiClient::AchGet200ResponseInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **description** | [**Ascii**](Ascii.md) |  | [optional] |
| **amount** | **String** |  | [optional] |
| **service** | [**Enum**](Enum.md) |  | [optional] |
| **counterparty_id** | **String** |  | [optional] |
| **bankdata** | **Object** |  | [optional] |
| **bank_id** | **String** |  | [optional] |
| **account_id** | **String** |  | [optional] |
| **addenda** | **Array** |  | [optional] |
| **org_id** | **String** |  | [optional] |
| **batch_key** | **String** |  | [optional] |
| **effective_date** | **Date** |  | [optional] |
| **status** | **String** |  | [optional] |
| **id** | **String** |  | [optional] |
| **error** | **String** |  | [optional] |
| **sec_code** | [**Enum**](Enum.md) |  | [optional] |
| **scheduled_settlement** | [**Datetime**](Datetime.md) |  | [optional] |
| **direction** | [**Enum**](Enum.md) |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AchGet200ResponseInner.new(
  description: null,
  amount: null,
  service: null,
  counterparty_id: null,
  bankdata: null,
  bank_id: null,
  account_id: null,
  addenda: null,
  org_id: null,
  batch_key: null,
  effective_date: null,
  status: null,
  id: null,
  error: null,
  sec_code: null,
  scheduled_settlement: null,
  direction: null,
  userdata: null
)
```

