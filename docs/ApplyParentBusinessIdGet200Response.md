# OpenapiClient::ApplyParentBusinessIdGet200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **bankdata** | **Object** |  | [optional] |
| **bank_id** | **String** |  | [optional] |
| **tin** | [**TaxIdNumber**](TaxIdNumber.md) |  | [optional] |
| **legal_structure** | [**Enum**](Enum.md) |  | [optional] |
| **name** | **String** |  | [optional] |
| **org_id** | **String** |  | [optional] |
| **incorporation_state** | **String** |  | [optional] |
| **dba** | **String** |  | [optional] |
| **document_ids** | **Array** |  | [optional] |
| **id** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ApplyParentBusinessIdGet200Response.new(
  bankdata: null,
  bank_id: null,
  tin: null,
  legal_structure: null,
  name: null,
  org_id: null,
  incorporation_state: null,
  dba: null,
  document_ids: null,
  id: null,
  userdata: null
)
```

