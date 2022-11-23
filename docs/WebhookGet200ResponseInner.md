# OpenapiClient::WebhookGet200ResponseInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **basic_secret** | **String** |  | [optional] |
| **basic_user** | **String** |  | [optional] |
| **event** | **String** |  | [optional] |
| **status** | [**Enum**](Enum.md) |  | [optional] |
| **id** | **String** |  | [optional] |
| **url** | [**Url**](Url.md) |  | [optional] |
| **error** | **String** |  | [optional] |
| **userdata** | **Object** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::WebhookGet200ResponseInner.new(
  basic_secret: null,
  basic_user: null,
  event: null,
  status: null,
  id: null,
  url: null,
  error: null,
  userdata: null
)
```

