# OpenapiClient::ApplyParentBusinessIdGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **bankdata** | **Object** |  | [optional] |
| **tin** | [**TaxIdNumber**](TaxIdNumber.md) |  | [optional] |
| **legal_structure** | [**Enum**](Enum.md) |  | [optional] |
| **name** | **String** |  | [optional] |
| **incorporation_state** | **String** |  | [optional] |
| **dba** | **String** |  | [optional] |
| **document_ids** | **Array** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ApplyParentBusinessIdGetRequest.new(
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

