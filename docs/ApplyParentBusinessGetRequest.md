# OpenapiClient::ApplyParentBusinessGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **bankdata** | **Object** |  | [optional] |
| **tin** | [**TaxIdNumber**](TaxIdNumber.md) |  |  |
| **legal_structure** | [**Enum**](Enum.md) |  |  |
| **name** | **String** |  |  |
| **incorporation_state** | **String** |  |  |
| **dba** | **String** |  | [optional] |
| **document_ids** | **Array** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ApplyParentBusinessGetRequest.new(
  bankdata: null,
  tin: null,
  legal_structure: null,
  name: null,
  incorporation_state: null,
  dba: null,
  document_ids: null,
  userdata: null
)
```

