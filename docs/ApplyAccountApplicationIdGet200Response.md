# OpenapiClient::ApplyAccountApplicationIdGet200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_product_id** | **String** |  | [optional] |
| **bankdata** | **Object** |  | [optional] |
| **primary_person_application_id** | **String** |  | [optional] |
| **business_application_id** | **String** |  | [optional] |
| **account_id** | **String** |  | [optional] |
| **product** | [**Ascii**](Ascii.md) |  | [optional] |
| **status** | [**Enum**](Enum.md) |  | [optional] |
| **account_number** | **String** |  | [optional] |
| **id** | **String** |  | [optional] |
| **deposit_id** | **String** |  | [optional] |
| **ownership_type** | [**Enum**](Enum.md) |  | [optional] |
| **person_applications** | **Array** |  | [optional] |
| **account_number_reservation_id** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ApplyAccountApplicationIdGet200Response.new(
  account_product_id: null,
  bankdata: null,
  primary_person_application_id: null,
  business_application_id: null,
  account_id: null,
  product: null,
  status: null,
  account_number: null,
  id: null,
  deposit_id: null,
  ownership_type: null,
  person_applications: null,
  account_number_reservation_id: null,
  userdata: null
)
```

