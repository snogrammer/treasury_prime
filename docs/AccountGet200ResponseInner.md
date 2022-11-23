# OpenapiClient::AccountGet200ResponseInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_type** | **String** |  | [optional] |
| **bank_id** | **String** |  | [optional] |
| **org_id** | **String** |  | [optional] |
| **currency** | [**Enum**](Enum.md) |  | [optional] |
| **routing_number** | [**RountingNumber**](RountingNumber.md) |  | [optional] |
| **account_number** | **String** |  | [optional] |
| **id** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AccountGet200ResponseInner.new(
  account_type: null,
  bank_id: null,
  org_id: null,
  currency: null,
  routing_number: null,
  account_number: null,
  id: null,
  userdata: null
)
```

