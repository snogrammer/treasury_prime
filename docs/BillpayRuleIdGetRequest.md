# OpenapiClient::BillpayRuleIdGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **amount** | **String** |  | [optional] |
| **starts_on** | **Date** |  | [optional] |
| **account_id** | **String** |  | [optional] |
| **person_id** | **String** |  | [optional] |
| **ends_on** | **Date** |  | [optional] |
| **status** | **String** |  | [optional] |
| **interval** | [**Enum**](Enum.md) |  | [optional] |
| **billpay_counterparty_id** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::BillpayRuleIdGetRequest.new(
  amount: null,
  starts_on: null,
  account_id: null,
  person_id: null,
  ends_on: null,
  status: null,
  interval: null,
  billpay_counterparty_id: null,
  userdata: null
)
```

