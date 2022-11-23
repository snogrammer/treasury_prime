# OpenapiClient::ApplyPersonApplicationIdGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **first_name** | [**Ascii**](Ascii.md) |  | [optional] |
| **secondary_email_address** | [**Email**](Email.md) |  | [optional] |
| **bankdata** | **Object** |  | [optional] |
| **phone_number** | [**Phone**](Phone.md) |  | [optional] |
| **mailing_address** | [**Struct**](Struct.md) |  | [optional] |
| **occupation** | [**Ascii**](Ascii.md) |  | [optional] |
| **physical_address** | [**Struct**](Struct.md) |  | [optional] |
| **middle_name** | [**Ascii**](Ascii.md) |  | [optional] |
| **gov_id** | **String** |  | [optional] |
| **document_ids** | **Array** |  | [optional] |
| **citizenship** | [**IsoCountryAlpha2**](IsoCountryAlpha2.md) |  | [optional] |
| **date_of_birth** | [**DateOfBirth**](DateOfBirth.md) |  | [optional] |
| **last_name** | [**Ascii**](Ascii.md) |  | [optional] |
| **user_id** | **String** |  | [optional] |
| **email_address** | [**Email**](Email.md) |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ApplyPersonApplicationIdGetRequest.new(
  first_name: null,
  secondary_email_address: null,
  bankdata: null,
  phone_number: null,
  mailing_address: null,
  occupation: null,
  physical_address: null,
  middle_name: null,
  gov_id: null,
  document_ids: null,
  citizenship: null,
  date_of_birth: null,
  last_name: null,
  user_id: null,
  email_address: null,
  userdata: null
)
```

