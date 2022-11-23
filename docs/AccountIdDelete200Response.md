# OpenapiClient::AccountIdDelete200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **address** | [**Struct**](Struct.md) |  | [optional] |
| **account_type** | **String** |  | [optional] |
| **bank_id** | **String** |  | [optional] |
| **person_ids** | **Array** |  | [optional] |
| **available_balance** | **String** |  | [optional] |
| **name** | **String** |  | [optional] |
| **org_id** | **String** |  | [optional] |
| **currency** | [**Enum**](Enum.md) |  | [optional] |
| **routing_number** | [**RountingNumber**](RountingNumber.md) |  | [optional] |
| **status** | **String** |  | [optional] |
| **primary_person_id** | **String** |  | [optional] |
| **account_number** | **String** |  | [optional] |
| **locked** | **Boolean** |  | [optional] |
| **id** | **String** |  | [optional] |
| **funded** | **Boolean** |  | [optional] |
| **business_ids** | **Array** |  | [optional] |
| **current_balance** | **String** |  | [optional] |
| **lock** | [**Struct**](Struct.md) |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AccountIdDelete200Response.new(
  address: null,
  account_type: null,
  bank_id: null,
  person_ids: null,
  available_balance: null,
  name: null,
  org_id: null,
  currency: null,
  routing_number: null,
  status: null,
  primary_person_id: null,
  account_number: null,
  locked: null,
  id: null,
  funded: null,
  business_ids: null,
  current_balance: null,
  lock: null,
  userdata: null
)
```

