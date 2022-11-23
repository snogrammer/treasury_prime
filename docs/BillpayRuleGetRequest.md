# OpenapiClient::BillpayRuleGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **amount** | **String** |  |  |
| **starts_on** | **Date** |  | [optional] |
| **account_id** | **String** |  |  |
| **person_id** | **String** |  |  |
| **ends_on** | **Date** |  | [optional] |
| **status** | **String** |  | [optional] |
| **interval** | [**Enum**](Enum.md) |  |  |
| **billpay_counterparty_id** | **String** |  |  |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::BillpayRuleGetRequest.new(
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

