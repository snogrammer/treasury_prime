# OpenapiClient::CheckGet200ResponseInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **amount** | **String** |  | [optional] |
| **bank_id** | **String** |  | [optional] |
| **account_id** | **String** |  | [optional] |
| **org_id** | **String** |  | [optional] |
| **recipient** | [**Struct**](Struct.md) |  | [optional] |
| **status** | **String** |  | [optional] |
| **id** | **String** |  | [optional] |
| **memo** | [**Ascii**](Ascii.md) |  | [optional] |
| **check_number** | **String** |  | [optional] |
| **message** | [**Ascii**](Ascii.md) |  | [optional] |
| **userdata** | **Object** |  | [optional] |
| **check_date** | [**Datetime**](Datetime.md) |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::CheckGet200ResponseInner.new(
  amount: null,
  bank_id: null,
  account_id: null,
  org_id: null,
  recipient: null,
  status: null,
  id: null,
  memo: null,
  check_number: null,
  message: null,
  userdata: null,
  check_date: null
)
```

