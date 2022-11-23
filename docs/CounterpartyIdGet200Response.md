# OpenapiClient::CounterpartyIdGet200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **ach** | [**Struct**](Struct.md) |  | [optional] |
| **wire** | [**Struct**](Struct.md) |  | [optional] |
| **name_on_account** | [**Ascii**](Ascii.md) |  | [optional] |
| **plaid_processor_token** | **String** |  | [optional] |
| **id** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::CounterpartyIdGet200Response.new(
  ach: null,
  wire: null,
  name_on_account: null,
  plaid_processor_token: null,
  id: null,
  userdata: null
)
```

