# OpenapiClient::SettingGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **ach_limit_credit** | **String** |  | [optional] |
| **wire_approvals** | **Integer** |  | [optional] |
| **wire_daily_limit** | **String** |  | [optional] |
| **ach_limit_debit** | **String** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::SettingGetRequest.new(
  ach_limit_credit: null,
  wire_approvals: null,
  wire_daily_limit: null,
  ach_limit_debit: null
)
```

