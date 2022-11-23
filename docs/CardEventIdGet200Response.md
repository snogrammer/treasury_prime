# OpenapiClient::CardEventIdGet200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **message_type** | [**Enum**](Enum.md) |  | [optional] |
| **amount** | **String** |  | [optional] |
| **bank_id** | **String** |  | [optional] |
| **org_id** | **String** |  | [optional] |
| **decline_reason** | **String** |  | [optional] |
| **currency** | **String** |  | [optional] |
| **status** | [**Enum**](Enum.md) |  | [optional] |
| **id** | **String** |  | [optional] |
| **card_id** | **String** |  | [optional] |
| **trace_id** | **String** |  | [optional] |
| **network** | [**Enum**](Enum.md) |  | [optional] |
| **network_created_at** | [**Datetime**](Datetime.md) |  | [optional] |
| **merchant** | [**Struct**](Struct.md) |  | [optional] |
| **processor** | [**Enum**](Enum.md) |  | [optional] |
| **networkdata** | **Object** |  | [optional] |
| **atm** | [**Struct**](Struct.md) |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::CardEventIdGet200Response.new(
  message_type: null,
  amount: null,
  bank_id: null,
  org_id: null,
  decline_reason: null,
  currency: null,
  status: null,
  id: null,
  card_id: null,
  trace_id: null,
  network: null,
  network_created_at: null,
  merchant: null,
  processor: null,
  networkdata: null,
  atm: null
)
```

