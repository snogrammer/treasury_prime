# OpenapiClient::PersonIdGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **address** | [**Struct**](Struct.md) |  | [optional] |
| **email** | **String** |  | [optional] |
| **phone_number** | [**UsPhone**](UsPhone.md) |  | [optional] |
| **mailing_address** | [**Struct**](Struct.md) |  | [optional] |
| **physical_address** | [**Struct**](Struct.md) |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::PersonIdGetRequest.new(
  address: null,
  email: null,
  phone_number: null,
  mailing_address: null,
  physical_address: null
)
```

