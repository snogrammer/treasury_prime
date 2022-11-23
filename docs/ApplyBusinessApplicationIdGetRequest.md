# OpenapiClient::ApplyBusinessApplicationIdGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **description** | **String** |  | [optional] |
| **urls** | **Array** |  | [optional] |
| **bankdata** | **Object** |  | [optional] |
| **phone_number** | [**UsPhone**](UsPhone.md) |  | [optional] |
| **tin** | [**TaxIdNumber**](TaxIdNumber.md) |  | [optional] |
| **legal_structure** | [**Enum**](Enum.md) |  | [optional] |
| **mailing_address** | [**Struct**](Struct.md) |  | [optional] |
| **naics_description** | **String** |  | [optional] |
| **name** | **String** |  | [optional] |
| **physical_address** | [**Struct**](Struct.md) |  | [optional] |
| **naics** | **String** |  | [optional] |
| **incorporation_state** | **String** |  | [optional] |
| **dba** | **String** |  | [optional] |
| **document_ids** | **Array** |  | [optional] |
| **established_on** | **Date** |  | [optional] |
| **parent_businesses** | **Array** |  | [optional] |
| **person_applications** | **Array** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ApplyBusinessApplicationIdGetRequest.new(
  description: null,
  urls: null,
  bankdata: null,
  phone_number: null,
  tin: null,
  legal_structure: null,
  mailing_address: null,
  naics_description: null,
  name: null,
  physical_address: null,
  naics: null,
  incorporation_state: null,
  dba: null,
  document_ids: null,
  established_on: null,
  parent_businesses: null,
  person_applications: null,
  userdata: null
)
```

