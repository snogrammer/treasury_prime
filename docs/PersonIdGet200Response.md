# OpenapiClient::PersonIdGet200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **suffix** | **String** |  | [optional] |
| **address** | [**Struct**](Struct.md) |  | [optional] |
| **email** | **String** |  | [optional] |
| **first_name** | **String** |  | [optional] |
| **bankdata** | **Object** |  | [optional] |
| **phone_number** | [**UsPhone**](UsPhone.md) |  | [optional] |
| **mailing_address** | [**Struct**](Struct.md) |  | [optional] |
| **physical_address** | [**Struct**](Struct.md) |  | [optional] |
| **middle_name** | **String** |  | [optional] |
| **tin_last4** | **String** |  | [optional] |
| **account_ids** | **Array** |  | [optional] |
| **id** | **String** |  | [optional] |
| **last_name** | **String** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::PersonIdGet200Response.new(
  suffix: null,
  address: null,
  email: null,
  first_name: null,
  bankdata: null,
  phone_number: null,
  mailing_address: null,
  physical_address: null,
  middle_name: null,
  tin_last4: null,
  account_ids: null,
  id: null,
  last_name: null
)
```

