# OpenapiClient::BillpayRuleIdGet200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **amount** | **String** |  | [optional] |
| **starts_on** | **Date** |  | [optional] |
| **bank_id** | **String** |  | [optional] |
| **account_id** | **String** |  | [optional] |
| **org_id** | **String** |  | [optional] |
| **person_id** | **String** |  | [optional] |
| **ends_on** | **Date** |  | [optional] |
| **status** | **String** |  | [optional] |
| **id** | **String** |  | [optional] |
| **interval** | [**Enum**](Enum.md) |  | [optional] |
| **billpay_counterparty_id** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::BillpayRuleIdGet200Response.new(
  amount: null,
  starts_on: null,
  bank_id: null,
  account_id: null,
  org_id: null,
  person_id: null,
  ends_on: null,
  status: null,
  id: null,
  interval: null,
  billpay_counterparty_id: null,
  userdata: null
)
```

