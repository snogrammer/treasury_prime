# OpenapiClient::CheckGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **amount** | **String** |  |  |
| **account_id** | **String** |  |  |
| **recipient** | [**Struct**](Struct.md) |  |  |
| **memo** | [**Ascii**](Ascii.md) |  | [optional] |
| **message** | [**Ascii**](Ascii.md) |  | [optional] |
| **userdata** | **Object** |  | [optional] |
| **check_date** | [**Datetime**](Datetime.md) |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::CheckGetRequest.new(
  amount: null,
  account_id: null,
  recipient: null,
  memo: null,
  message: null,
  userdata: null,
  check_date: null
)
```

