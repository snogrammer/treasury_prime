# OpenapiClient::BookGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **to_account_id** | **String** |  |  |
| **description** | **String** |  | [optional] |
| **amount** | **String** |  |  |
| **bankdata** | **Object** |  | [optional] |
| **from_account_id** | **String** |  |  |
| **status** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::BookGetRequest.new(
  to_account_id: null,
  description: null,
  amount: null,
  bankdata: null,
  from_account_id: null,
  status: null,
  userdata: null
)
```

