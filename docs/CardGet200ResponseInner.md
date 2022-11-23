# OpenapiClient::CardGet200ResponseInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **cvv** | **String** |  | [optional] |
| **account_id** | **String** |  | [optional] |
| **pan** | **String** |  | [optional] |
| **expiration** | **String** |  | [optional] |
| **person_id** | **String** |  | [optional] |
| **last4** | **String** |  | [optional] |
| **card_product_id** | **String** |  | [optional] |
| **card_controls** | [**Struct**](Struct.md) |  | [optional] |
| **status** | [**Enum**](Enum.md) |  | [optional] |
| **fulfillment** | [**Struct**](Struct.md) |  | [optional] |
| **id** | **String** |  | [optional] |
| **pin_is_set** | **Boolean** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::CardGet200ResponseInner.new(
  cvv: null,
  account_id: null,
  pan: null,
  expiration: null,
  person_id: null,
  last4: null,
  card_product_id: null,
  card_controls: null,
  status: null,
  fulfillment: null,
  id: null,
  pin_is_set: null,
  userdata: null
)
```

