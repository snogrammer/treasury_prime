# OpenapiClient::WebhookIdDeleteRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **basic_secret** | **String** |  | [optional] |
| **basic_user** | **String** |  | [optional] |
| **event** | **String** |  | [optional] |
| **status** | [**Enum**](Enum.md) |  | [optional] |
| **url** | [**Url**](Url.md) |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::WebhookIdDeleteRequest.new(
  basic_secret: null,
  basic_user: null,
  event: null,
  status: null,
  url: null,
  userdata: null
)
```

