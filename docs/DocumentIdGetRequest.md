# OpenapiClient::DocumentIdGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **description** | **String** |  | [optional] |
| **bankdata** | **Object** |  | [optional] |
| **name** | [**Filename**](Filename.md) |  | [optional] |
| **fields** | **Object** |  | [optional] |
| **type** | [**Enum**](Enum.md) |  | [optional] |
| **file_id** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::DocumentIdGetRequest.new(
  description: null,
  bankdata: null,
  name: null,
  fields: null,
  type: null,
  file_id: null,
  userdata: null
)
```

