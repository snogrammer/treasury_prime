# OpenapiClient::WebhookGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **basic_secret** | **String** |  | [optional] |
| **basic_user** | **String** |  | [optional] |
| **event** | **String** |  |  |
| **status** | [**Enum**](Enum.md) |  |  |
| **url** | [**Url**](Url.md) |  |  |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::WebhookGetRequest.new(
  basic_secret: null,
  basic_user: null,
  event: null,
  status: null,
  url: null,
  userdata: null
)
```

