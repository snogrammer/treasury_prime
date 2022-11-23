# OpenapiClient::ApplyAccountApplicationIdGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_product_id** | **String** |  | [optional] |
| **bankdata** | **Object** |  | [optional] |
| **primary_person_application_id** | **String** |  | [optional] |
| **business_application_id** | **String** |  | [optional] |
| **product** | [**Ascii**](Ascii.md) |  | [optional] |
| **deposit_id** | **String** |  | [optional] |
| **person_applications** | **Array** |  | [optional] |
| **account_number_reservation_id** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ApplyAccountApplicationIdGetRequest.new(
  account_product_id: null,
  bankdata: null,
  primary_person_application_id: null,
  business_application_id: null,
  product: null,
  deposit_id: null,
  person_applications: null,
  account_number_reservation_id: null,
  userdata: null
)
```

