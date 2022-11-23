# OpenapiClient::ApplyAccountApplicationGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_number_reservation_id** | **String** | ID of the [Account Reservation](https://developers.treasuryprime.com/docs/account-application#account-number-reservations0) object for creating the account with a previously-allocated account number. Can be created with /account_number_reservation.  Example: &#x60;anr_123&#x60; | [optional] |
| **account_product_id** | **String** | ID of the [Account Product](https://developers.treasuryprime.com/docs/account-product) being applied for, can be retrieved from /account_product.  Example: &#x60;apt_11ha1payax7042&#x60; | [optional] |
| **bankdata** | **String** | Optional arbitrary data, for the bank&#39;s use. | [optional] |
| **business_application_id** | **String** | ID of the [Business Application](https://developers.treasuryprime.com/guides/open-accounts#2-create-a-business-application) object for the business applying for the account can be created with /apply/business_application.  Example: &#x60;abus_11hb4dzeb572hh&#x60; | [optional] |
| **deposit_id** | **String** | ID of the [Deposit](https://developers.treasuryprime.com/guides/open-accounts#3-create-a-deposit) object that defines the initial funding deposit for the new account. Can be created with /apply/deposit. Example: &#39;adpt_11hb4fexb57yd8&#39; | [optional] |
| **person_applications** | **String** | Array of Person sub-objects describing persons associated with this account application, including the primary person. Always [] for business accounts. Can be created with /apply/person_application | [optional] |
| **primary_person_application_id** | **String** | ID of the [Person Application](https://developers.treasuryprime.com/guides/open-accounts#1-create-a-person-application) object representing the primary person applying for the account.  Example: &#x60;apsn_11hb4cjwb563zt&#x60; | [optional] |
| **userdata** | **String** | Optional arbitrary user data. | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ApplyAccountApplicationGetRequest.new(
  account_number_reservation_id: null,
  account_product_id: null,
  bankdata: null,
  business_application_id: null,
  deposit_id: null,
  person_applications: null,
  primary_person_application_id: null,
  userdata: null
)
```

