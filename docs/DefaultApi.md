# OpenapiClient::DefaultApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**account_get**](DefaultApi.md#account_get) | **GET** /account | index account.id |
| [**account_id_active_holds_get**](DefaultApi.md#account_id_active_holds_get) | **GET** /account/{id}/active_holds | get account.active_holds |
| [**account_id_average_balance_get**](DefaultApi.md#account_id_average_balance_get) | **GET** /account/{id}/average_balance | get-index account |
| [**account_id_daily_balance_get**](DefaultApi.md#account_id_daily_balance_get) | **GET** /account/{id}/daily_balance | List Daily Balances |
| [**account_id_delete**](DefaultApi.md#account_id_delete) | **DELETE** /account/{id} | delete account |
| [**account_id_get**](DefaultApi.md#account_id_get) | **GET** /account/{id} | get account |
| [**account_id_patch**](DefaultApi.md#account_id_patch) | **PATCH** /account/{id} | update account |
| [**account_id_statement_file_id_get**](DefaultApi.md#account_id_statement_file_id_get) | **GET** /account/{id}/statement/{file_id} | get account.statement.file |
| [**account_id_statement_get**](DefaultApi.md#account_id_statement_get) | **GET** /account/{id}/statement | Retrieve Statements |
| [**account_id_tax_document_file_id_get**](DefaultApi.md#account_id_tax_document_file_id_get) | **GET** /account/{id}/tax_document/{file_id} | get account.tax_document.file |
| [**account_id_tax_document_get**](DefaultApi.md#account_id_tax_document_get) | **GET** /account/{id}/tax_document | get account.tax_document |
| [**account_id_transaction_get**](DefaultApi.md#account_id_transaction_get) | **GET** /account/{id}/transaction | get-index account.transaction |
| [**account_number_post**](DefaultApi.md#account_number_post) | **POST** /account_number | create account-number |
| [**account_number_reservation_get**](DefaultApi.md#account_number_reservation_get) | **GET** /account_number_reservation | Retrieve an Account Number Reservation |
| [**account_number_reservation_id_get**](DefaultApi.md#account_number_reservation_id_get) | **GET** /account_number_reservation/{id} | get account-number-reservation |
| [**account_number_reservation_post**](DefaultApi.md#account_number_reservation_post) | **POST** /account_number_reservation | Create an Account Number Reservation |
| [**account_post**](DefaultApi.md#account_post) | **POST** /account | create account.create |
| [**account_product_get**](DefaultApi.md#account_product_get) | **GET** /account_product | index account_product |
| [**account_product_id_get**](DefaultApi.md#account_product_id_get) | **GET** /account_product/{id} | get account_product |
| [**ach_get**](DefaultApi.md#ach_get) | **GET** /ach | List All ACH Transfers |
| [**ach_id_get**](DefaultApi.md#ach_id_get) | **GET** /ach/{id} | get ach |
| [**ach_id_patch**](DefaultApi.md#ach_id_patch) | **PATCH** /ach/{id} | update ach |
| [**ach_post**](DefaultApi.md#ach_post) | **POST** /ach | Create an ACH |
| [**apply_account_application_get**](DefaultApi.md#apply_account_application_get) | **GET** /apply/account_application | Retrieve All Account Applications |
| [**apply_account_application_id_get**](DefaultApi.md#apply_account_application_id_get) | **GET** /apply/account_application/{id} | get apply.account-application |
| [**apply_account_application_id_patch**](DefaultApi.md#apply_account_application_id_patch) | **PATCH** /apply/account_application/{id} | update apply.account-application |
| [**apply_account_application_post**](DefaultApi.md#apply_account_application_post) | **POST** /apply/account_application | Create Account Application |
| [**apply_additional_person_application_get**](DefaultApi.md#apply_additional_person_application_get) | **GET** /apply/additional_person_application | index apply.additional-person-application |
| [**apply_additional_person_application_id_get**](DefaultApi.md#apply_additional_person_application_id_get) | **GET** /apply/additional_person_application/{id} | Retrieve an Additional Person Application |
| [**apply_additional_person_application_id_patch**](DefaultApi.md#apply_additional_person_application_id_patch) | **PATCH** /apply/additional_person_application/{id} | Update an Additional Person Applications |
| [**apply_additional_person_application_post**](DefaultApi.md#apply_additional_person_application_post) | **POST** /apply/additional_person_application | create apply.additional-person-application |
| [**apply_authorized_user_application_get**](DefaultApi.md#apply_authorized_user_application_get) | **GET** /apply/authorized_user_application | index apply.authorized-user-application |
| [**apply_authorized_user_application_id_get**](DefaultApi.md#apply_authorized_user_application_id_get) | **GET** /apply/authorized_user_application/{id} | get apply.authorized-user-application |
| [**apply_authorized_user_application_id_patch**](DefaultApi.md#apply_authorized_user_application_id_patch) | **PATCH** /apply/authorized_user_application/{id} | update apply.authorized-user-application |
| [**apply_authorized_user_application_post**](DefaultApi.md#apply_authorized_user_application_post) | **POST** /apply/authorized_user_application | create apply.authorized-user-application |
| [**apply_business_application_get**](DefaultApi.md#apply_business_application_get) | **GET** /apply/business_application | index apply.business-application |
| [**apply_business_application_id_get**](DefaultApi.md#apply_business_application_id_get) | **GET** /apply/business_application/{id} | get apply.business-application |
| [**apply_business_application_id_patch**](DefaultApi.md#apply_business_application_id_patch) | **PATCH** /apply/business_application/{id} | update apply.business-application |
| [**apply_business_application_post**](DefaultApi.md#apply_business_application_post) | **POST** /apply/business_application | create apply.business-application |
| [**apply_compliance_get**](DefaultApi.md#apply_compliance_get) | **GET** /apply/compliance | index apply.compliance |
| [**apply_compliance_id_get**](DefaultApi.md#apply_compliance_id_get) | **GET** /apply/compliance/{id} | get apply.compliance |
| [**apply_compliance_post**](DefaultApi.md#apply_compliance_post) | **POST** /apply/compliance | create apply.compliance |
| [**apply_deposit_get**](DefaultApi.md#apply_deposit_get) | **GET** /apply/deposit | index apply.deposit |
| [**apply_deposit_id_get**](DefaultApi.md#apply_deposit_id_get) | **GET** /apply/deposit/{id} | get apply.deposit |
| [**apply_deposit_post**](DefaultApi.md#apply_deposit_post) | **POST** /apply/deposit | create apply.deposit |
| [**apply_kyc_get**](DefaultApi.md#apply_kyc_get) | **GET** /apply/kyc | index apply.kyc |
| [**apply_kyc_id_get**](DefaultApi.md#apply_kyc_id_get) | **GET** /apply/kyc/{id} | get apply.kyc |
| [**apply_kyc_post**](DefaultApi.md#apply_kyc_post) | **POST** /apply/kyc | create apply.kyc |
| [**apply_kyc_product_get**](DefaultApi.md#apply_kyc_product_get) | **GET** /apply/kyc_product | index apply.kyc-product |
| [**apply_kyc_product_id_get**](DefaultApi.md#apply_kyc_product_id_get) | **GET** /apply/kyc_product/{id} | get apply.kyc-product |
| [**apply_kyc_product_id_patch**](DefaultApi.md#apply_kyc_product_id_patch) | **PATCH** /apply/kyc_product/{id} | update apply.kyc-product |
| [**apply_kyc_product_post**](DefaultApi.md#apply_kyc_product_post) | **POST** /apply/kyc_product | create apply.kyc-product |
| [**apply_parent_business_get**](DefaultApi.md#apply_parent_business_get) | **GET** /apply/parent_business | index apply.parent-business |
| [**apply_parent_business_id_get**](DefaultApi.md#apply_parent_business_id_get) | **GET** /apply/parent_business/{id} | get apply.parent-business |
| [**apply_parent_business_id_patch**](DefaultApi.md#apply_parent_business_id_patch) | **PATCH** /apply/parent_business/{id} | update apply.parent-business |
| [**apply_parent_business_post**](DefaultApi.md#apply_parent_business_post) | **POST** /apply/parent_business | create apply.parent-business |
| [**apply_person_application_get**](DefaultApi.md#apply_person_application_get) | **GET** /apply/person_application | index apply.person-application |
| [**apply_person_application_id_get**](DefaultApi.md#apply_person_application_id_get) | **GET** /apply/person_application/{id} | get apply.person-application |
| [**apply_person_application_id_patch**](DefaultApi.md#apply_person_application_id_patch) | **PATCH** /apply/person_application/{id} | update apply.person-application |
| [**apply_person_application_post**](DefaultApi.md#apply_person_application_post) | **POST** /apply/person_application | create apply.person-application |
| [**billpay_counterparty_get**](DefaultApi.md#billpay_counterparty_get) | **GET** /billpay/counterparty | index billpay_counterparty |
| [**billpay_counterparty_id_get**](DefaultApi.md#billpay_counterparty_id_get) | **GET** /billpay/counterparty/{id} | Retrieve a Bill Pay Counterparty |
| [**billpay_counterparty_id_patch**](DefaultApi.md#billpay_counterparty_id_patch) | **PATCH** /billpay/counterparty/{id} | update billpay_counterparty |
| [**billpay_counterparty_post**](DefaultApi.md#billpay_counterparty_post) | **POST** /billpay/counterparty | create billpay_counterparty |
| [**billpay_merchant_get**](DefaultApi.md#billpay_merchant_get) | **GET** /billpay/merchant | get billpay_merchant |
| [**billpay_payment_get**](DefaultApi.md#billpay_payment_get) | **GET** /billpay/payment | index billpay_payment |
| [**billpay_payment_id_get**](DefaultApi.md#billpay_payment_id_get) | **GET** /billpay/payment/{id} | get billpay_payment |
| [**billpay_payment_id_patch**](DefaultApi.md#billpay_payment_id_patch) | **PATCH** /billpay/payment/{id} | update billpay_payment |
| [**billpay_payment_post**](DefaultApi.md#billpay_payment_post) | **POST** /billpay/payment | create billpay_payment |
| [**billpay_rule_get**](DefaultApi.md#billpay_rule_get) | **GET** /billpay/rule | index billpay_rule |
| [**billpay_rule_id_get**](DefaultApi.md#billpay_rule_id_get) | **GET** /billpay/rule/{id} | Retrieve a Rule |
| [**billpay_rule_id_patch**](DefaultApi.md#billpay_rule_id_patch) | **PATCH** /billpay/rule/{id} | Update a Rule |
| [**billpay_rule_post**](DefaultApi.md#billpay_rule_post) | **POST** /billpay/rule | create billpay_rule |
| [**book_get**](DefaultApi.md#book_get) | **GET** /book | index book |
| [**book_id_get**](DefaultApi.md#book_id_get) | **GET** /book/{id} | get book |
| [**book_id_patch**](DefaultApi.md#book_id_patch) | **PATCH** /book/{id} | update book |
| [**book_post**](DefaultApi.md#book_post) | **POST** /book | create book |
| [**business_id_get**](DefaultApi.md#business_id_get) | **GET** /business/{id} | get business |
| [**business_id_patch**](DefaultApi.md#business_id_patch) | **PATCH** /business/{id} | update business |
| [**card_auth_loop_endpoint_get**](DefaultApi.md#card_auth_loop_endpoint_get) | **GET** /card_auth_loop_endpoint | List Card Auth Loop Endpoints |
| [**card_auth_loop_endpoint_id_delete**](DefaultApi.md#card_auth_loop_endpoint_id_delete) | **DELETE** /card_auth_loop_endpoint/{id} | delete card_auth_loop_endpoint |
| [**card_auth_loop_endpoint_id_get**](DefaultApi.md#card_auth_loop_endpoint_id_get) | **GET** /card_auth_loop_endpoint/{id} | get card_auth_loop_endpoint |
| [**card_auth_loop_endpoint_id_patch**](DefaultApi.md#card_auth_loop_endpoint_id_patch) | **PATCH** /card_auth_loop_endpoint/{id} | update card_auth_loop_endpoint |
| [**card_auth_loop_endpoint_post**](DefaultApi.md#card_auth_loop_endpoint_post) | **POST** /card_auth_loop_endpoint | create card_auth_loop_endpoint |
| [**card_card_id_digital_wallet_token_google_pay_post**](DefaultApi.md#card_card_id_digital_wallet_token_google_pay_post) | **POST** /card/{card_id}/digital_wallet_token/google_pay | create google-pay-token-request |
| [**card_charge_get**](DefaultApi.md#card_charge_get) | **GET** /card/charge | index card.charge |
| [**card_charge_id_get**](DefaultApi.md#card_charge_id_get) | **GET** /card/charge/{id} | get card.charge |
| [**card_charge_post**](DefaultApi.md#card_charge_post) | **POST** /card/charge | create card.charge |
| [**card_event_get**](DefaultApi.md#card_event_get) | **GET** /card_event | List Card Events |
| [**card_event_id_get**](DefaultApi.md#card_event_id_get) | **GET** /card_event/{id} | Retrieve a Card Event |
| [**card_get**](DefaultApi.md#card_get) | **GET** /card | index card |
| [**card_id_get**](DefaultApi.md#card_id_get) | **GET** /card/{id} | get card |
| [**card_id_patch**](DefaultApi.md#card_id_patch) | **PATCH** /card/{id} | update card |
| [**card_id_token_get**](DefaultApi.md#card_id_token_get) | **GET** /card/{id}/token | get token |
| [**card_post**](DefaultApi.md#card_post) | **POST** /card | create card |
| [**cardproduct_get**](DefaultApi.md#cardproduct_get) | **GET** /cardproduct | index cardproduct |
| [**cardproduct_id_get**](DefaultApi.md#cardproduct_id_get) | **GET** /cardproduct/{id} | Card Product |
| [**cardproduct_id_patch**](DefaultApi.md#cardproduct_id_patch) | **PATCH** /cardproduct/{id} | update cardproduct |
| [**check_deposit_get**](DefaultApi.md#check_deposit_get) | **GET** /check_deposit | index check_deposit |
| [**check_deposit_id_get**](DefaultApi.md#check_deposit_id_get) | **GET** /check_deposit/{id} | get check_deposit |
| [**check_deposit_person_get**](DefaultApi.md#check_deposit_person_get) | **GET** /check_deposit_person | index check_deposit_person |
| [**check_deposit_person_id_get**](DefaultApi.md#check_deposit_person_id_get) | **GET** /check_deposit_person/{id} | get check_deposit_person |
| [**check_deposit_person_post**](DefaultApi.md#check_deposit_person_post) | **POST** /check_deposit_person | create check_deposit_person |
| [**check_deposit_post**](DefaultApi.md#check_deposit_post) | **POST** /check_deposit | create check_deposit |
| [**check_get**](DefaultApi.md#check_get) | **GET** /check | index check |
| [**check_id_get**](DefaultApi.md#check_id_get) | **GET** /check/{id} | get check |
| [**check_image_get**](DefaultApi.md#check_image_get) | **GET** /check_image | index check_image |
| [**check_image_id_get**](DefaultApi.md#check_image_id_get) | **GET** /check_image/{id} | get check_image |
| [**check_post**](DefaultApi.md#check_post) | **POST** /check | create check |
| [**counterparty_get**](DefaultApi.md#counterparty_get) | **GET** /counterparty | index counterparty |
| [**counterparty_id_get**](DefaultApi.md#counterparty_id_get) | **GET** /counterparty/{id} | get counterparty |
| [**counterparty_id_patch**](DefaultApi.md#counterparty_id_patch) | **PATCH** /counterparty/{id} | update counterparty |
| [**counterparty_post**](DefaultApi.md#counterparty_post) | **POST** /counterparty | create counterparty |
| [**document_get**](DefaultApi.md#document_get) | **GET** /document | index document |
| [**document_id_get**](DefaultApi.md#document_id_get) | **GET** /document/{id} | get document |
| [**document_id_patch**](DefaultApi.md#document_id_patch) | **PATCH** /document/{id} | update document |
| [**document_post**](DefaultApi.md#document_post) | **POST** /document | create document |
| [**file_id_content_get**](DefaultApi.md#file_id_content_get) | **GET** /file/{id}/content | get file |
| [**file_id_get**](DefaultApi.md#file_id_get) | **GET** /file/{id} | get file |
| [**person_id_card_card_id_get**](DefaultApi.md#person_id_card_card_id_get) | **GET** /person/{id}/card/{card_id} | get person.card.index |
| [**person_id_card_get**](DefaultApi.md#person_id_card_get) | **GET** /person/{id}/card | get person.card.index |
| [**person_id_card_post**](DefaultApi.md#person_id_card_post) | **POST** /person/{id}/card | update person.card.in |
| [**person_id_get**](DefaultApi.md#person_id_get) | **GET** /person/{id} | get person |
| [**person_id_patch**](DefaultApi.md#person_id_patch) | **PATCH** /person/{id} | update person |
| [**plaid_exchange_users_auth_token_post**](DefaultApi.md#plaid_exchange_users_auth_token_post) | **POST** /plaid_exchange/users/auth_token | get plaid-exchange.auth |
| [**plaid_exchange_users_user_id2fa_post**](DefaultApi.md#plaid_exchange_users_user_id2fa_post) | **POST** /plaid_exchange/users/{user_id}/2fa | get plaid-exchange.2fa |
| [**plaid_exchange_users_user_id_get**](DefaultApi.md#plaid_exchange_users_user_id_get) | **GET** /plaid_exchange/users/{user_id} | get plaid-exchange.identity |
| [**plaid_exchange_users_user_id_transactions_get**](DefaultApi.md#plaid_exchange_users_user_id_transactions_get) | **GET** /plaid_exchange/users/{user_id}/transactions | get plaid-exchange.transactions |
| [**reserve_get**](DefaultApi.md#reserve_get) | **GET** /reserve | index reserve |
| [**reserve_id_delete**](DefaultApi.md#reserve_id_delete) | **DELETE** /reserve/{id} | delete reserve |
| [**reserve_id_get**](DefaultApi.md#reserve_id_get) | **GET** /reserve/{id} | get reserve |
| [**reserve_id_patch**](DefaultApi.md#reserve_id_patch) | **PATCH** /reserve/{id} | update reserve |
| [**reserve_post**](DefaultApi.md#reserve_post) | **POST** /reserve | create reserve |
| [**search_get**](DefaultApi.md#search_get) | **GET** /search | index search |
| [**setting_get**](DefaultApi.md#setting_get) | **GET** /setting | index setting |
| [**setting_patch**](DefaultApi.md#setting_patch) | **PATCH** /setting | update setting |
| [**simulation_post**](DefaultApi.md#simulation_post) | **POST** /simulation | create simulation |
| [**survey_get**](DefaultApi.md#survey_get) | **GET** /survey | index survey |
| [**survey_id_get**](DefaultApi.md#survey_id_get) | **GET** /survey/{id} | get survey |
| [**third_party_ach_get**](DefaultApi.md#third_party_ach_get) | **GET** /third_party_ach | index third_party_ach |
| [**third_party_ach_id_get**](DefaultApi.md#third_party_ach_id_get) | **GET** /third_party_ach/{id} | get third_party_ach |
| [**third_party_ach_id_patch**](DefaultApi.md#third_party_ach_id_patch) | **PATCH** /third_party_ach/{id} | update third_party_ach |
| [**third_party_ach_post**](DefaultApi.md#third_party_ach_post) | **POST** /third_party_ach | create third_party_ach |
| [**transaction_get**](DefaultApi.md#transaction_get) | **GET** /transaction | index transaction |
| [**transaction_id_get**](DefaultApi.md#transaction_id_get) | **GET** /transaction/{id} | get transaction |
| [**webhook_get**](DefaultApi.md#webhook_get) | **GET** /webhook | index webhook |
| [**webhook_id_delete**](DefaultApi.md#webhook_id_delete) | **DELETE** /webhook/{id} | delete webhook |
| [**webhook_id_get**](DefaultApi.md#webhook_id_get) | **GET** /webhook/{id} | get webhook |
| [**webhook_id_patch**](DefaultApi.md#webhook_id_patch) | **PATCH** /webhook/{id} | update webhook |
| [**webhook_post**](DefaultApi.md#webhook_post) | **POST** /webhook | create webhook |
| [**wire_get**](DefaultApi.md#wire_get) | **GET** /wire | index wire |
| [**wire_id_get**](DefaultApi.md#wire_id_get) | **GET** /wire/{id} | get wire |
| [**wire_id_patch**](DefaultApi.md#wire_id_patch) | **PATCH** /wire/{id} | update wire |
| [**wire_post**](DefaultApi.md#wire_post) | **POST** /wire | create wire |


## account_get

> <Array<AccountGet200ResponseInner>> account_get

index account.id

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index account.id
  result = api_instance.account_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_get: #{e}"
end
```

#### Using the account_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<AccountGet200ResponseInner>>, Integer, Hash)> account_get_with_http_info

```ruby
begin
  # index account.id
  data, status_code, headers = api_instance.account_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<AccountGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;AccountGet200ResponseInner&gt;**](AccountGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_id_active_holds_get

> <AccountIdActiveHoldsGet200Response> account_id_active_holds_get(id)

get account.active_holds

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get account.active_holds
  result = api_instance.account_id_active_holds_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_active_holds_get: #{e}"
end
```

#### Using the account_id_active_holds_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountIdActiveHoldsGet200Response>, Integer, Hash)> account_id_active_holds_get_with_http_info(id)

```ruby
begin
  # get account.active_holds
  data, status_code, headers = api_instance.account_id_active_holds_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountIdActiveHoldsGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_active_holds_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**AccountIdActiveHoldsGet200Response**](AccountIdActiveHoldsGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_id_average_balance_get

> account_id_average_balance_get(id)

get-index account

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get-index account
  api_instance.account_id_average_balance_get(id)
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_average_balance_get: #{e}"
end
```

#### Using the account_id_average_balance_get_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> account_id_average_balance_get_with_http_info(id)

```ruby
begin
  # get-index account
  data, status_code, headers = api_instance.account_id_average_balance_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_average_balance_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

nil (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## account_id_daily_balance_get

> account_id_daily_balance_get(id)

List Daily Balances

The end of day balances are available using the daily_balance endpoint. You can query this endpoint by date range; if no date range is specified, the endpoint will return balances for the most recent 30 days including today.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # List Daily Balances
  api_instance.account_id_daily_balance_get(id)
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_daily_balance_get: #{e}"
end
```

#### Using the account_id_daily_balance_get_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> account_id_daily_balance_get_with_http_info(id)

```ruby
begin
  # List Daily Balances
  data, status_code, headers = api_instance.account_id_daily_balance_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_daily_balance_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

nil (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## account_id_delete

> account_id_delete(id)

delete account

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # delete account
  api_instance.account_id_delete(id)
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_delete: #{e}"
end
```

#### Using the account_id_delete_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> account_id_delete_with_http_info(id)

```ruby
begin
  # delete account
  data, status_code, headers = api_instance.account_id_delete_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_delete_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

nil (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## account_id_get

> <AccountIdDelete200Response> account_id_get(id)

get account

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get account
  result = api_instance.account_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_get: #{e}"
end
```

#### Using the account_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountIdDelete200Response>, Integer, Hash)> account_id_get_with_http_info(id)

```ruby
begin
  # get account
  data, status_code, headers = api_instance.account_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountIdDelete200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**AccountIdDelete200Response**](AccountIdDelete200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_id_patch

> <AccountIdDelete200Response> account_id_patch(id, account_id_delete_request)

update account

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
account_id_delete_request = OpenapiClient::AccountIdDeleteRequest.new # AccountIdDeleteRequest | The account to update

begin
  # update account
  result = api_instance.account_id_patch(id, account_id_delete_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_patch: #{e}"
end
```

#### Using the account_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountIdDelete200Response>, Integer, Hash)> account_id_patch_with_http_info(id, account_id_delete_request)

```ruby
begin
  # update account
  data, status_code, headers = api_instance.account_id_patch_with_http_info(id, account_id_delete_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountIdDelete200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **account_id_delete_request** | [**AccountIdDeleteRequest**](AccountIdDeleteRequest.md) | The account to update |  |

### Return type

[**AccountIdDelete200Response**](AccountIdDelete200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## account_id_statement_file_id_get

> <AccountIdTaxDocumentFileIdGet200Response> account_id_statement_file_id_get(id, file_id)

get account.statement.file

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
file_id = 'file_id_example' # String | 

begin
  # get account.statement.file
  result = api_instance.account_id_statement_file_id_get(id, file_id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_statement_file_id_get: #{e}"
end
```

#### Using the account_id_statement_file_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountIdTaxDocumentFileIdGet200Response>, Integer, Hash)> account_id_statement_file_id_get_with_http_info(id, file_id)

```ruby
begin
  # get account.statement.file
  data, status_code, headers = api_instance.account_id_statement_file_id_get_with_http_info(id, file_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountIdTaxDocumentFileIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_statement_file_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **file_id** | **String** |  |  |

### Return type

[**AccountIdTaxDocumentFileIdGet200Response**](AccountIdTaxDocumentFileIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_id_statement_get

> <AccountIdStatementGet200Response> account_id_statement_get(id)

Retrieve Statements

At the end of every month, statements are generated for every account. The monthly statement lists the transactions for the month, the change in balance, and any interest accrued. This endpoint returns a URL to an account statement, or an error if none are available. The URL will serve a PDF of the statement itself.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # Retrieve Statements
  result = api_instance.account_id_statement_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_statement_get: #{e}"
end
```

#### Using the account_id_statement_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountIdStatementGet200Response>, Integer, Hash)> account_id_statement_get_with_http_info(id)

```ruby
begin
  # Retrieve Statements
  data, status_code, headers = api_instance.account_id_statement_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountIdStatementGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_statement_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**AccountIdStatementGet200Response**](AccountIdStatementGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_id_tax_document_file_id_get

> <AccountIdTaxDocumentFileIdGet200Response> account_id_tax_document_file_id_get(id, file_id)

get account.tax_document.file

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
file_id = 'file_id_example' # String | 

begin
  # get account.tax_document.file
  result = api_instance.account_id_tax_document_file_id_get(id, file_id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_tax_document_file_id_get: #{e}"
end
```

#### Using the account_id_tax_document_file_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountIdTaxDocumentFileIdGet200Response>, Integer, Hash)> account_id_tax_document_file_id_get_with_http_info(id, file_id)

```ruby
begin
  # get account.tax_document.file
  data, status_code, headers = api_instance.account_id_tax_document_file_id_get_with_http_info(id, file_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountIdTaxDocumentFileIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_tax_document_file_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **file_id** | **String** |  |  |

### Return type

[**AccountIdTaxDocumentFileIdGet200Response**](AccountIdTaxDocumentFileIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_id_tax_document_get

> <AccountIdTaxDocumentGet200Response> account_id_tax_document_get(id)

get account.tax_document

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get account.tax_document
  result = api_instance.account_id_tax_document_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_tax_document_get: #{e}"
end
```

#### Using the account_id_tax_document_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountIdTaxDocumentGet200Response>, Integer, Hash)> account_id_tax_document_get_with_http_info(id)

```ruby
begin
  # get account.tax_document
  data, status_code, headers = api_instance.account_id_tax_document_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountIdTaxDocumentGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_tax_document_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**AccountIdTaxDocumentGet200Response**](AccountIdTaxDocumentGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_id_transaction_get

> account_id_transaction_get(id)

get-index account.transaction

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get-index account.transaction
  api_instance.account_id_transaction_get(id)
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_transaction_get: #{e}"
end
```

#### Using the account_id_transaction_get_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> account_id_transaction_get_with_http_info(id)

```ruby
begin
  # get-index account.transaction
  data, status_code, headers = api_instance.account_id_transaction_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_id_transaction_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

nil (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## account_number_post

> <AccountNumberPost200Response> account_number_post(account_number_post_request)

create account-number

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
account_number_post_request = OpenapiClient::AccountNumberPostRequest.new({account_number: 'account_number_example'}) # AccountNumberPostRequest | The account-number to create

begin
  # create account-number
  result = api_instance.account_number_post(account_number_post_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_number_post: #{e}"
end
```

#### Using the account_number_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountNumberPost200Response>, Integer, Hash)> account_number_post_with_http_info(account_number_post_request)

```ruby
begin
  # create account-number
  data, status_code, headers = api_instance.account_number_post_with_http_info(account_number_post_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountNumberPost200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_number_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_number_post_request** | [**AccountNumberPostRequest**](AccountNumberPostRequest.md) | The account-number to create |  |

### Return type

[**AccountNumberPost200Response**](AccountNumberPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## account_number_reservation_get

> <Array<AccountNumberReservationGet200ResponseInner>> account_number_reservation_get

Retrieve an Account Number Reservation

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # Retrieve an Account Number Reservation
  result = api_instance.account_number_reservation_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_number_reservation_get: #{e}"
end
```

#### Using the account_number_reservation_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<AccountNumberReservationGet200ResponseInner>>, Integer, Hash)> account_number_reservation_get_with_http_info

```ruby
begin
  # Retrieve an Account Number Reservation
  data, status_code, headers = api_instance.account_number_reservation_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<AccountNumberReservationGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_number_reservation_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;AccountNumberReservationGet200ResponseInner&gt;**](AccountNumberReservationGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_number_reservation_id_get

> <AccountNumberReservationGet200ResponseInner> account_number_reservation_id_get(id)

get account-number-reservation

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get account-number-reservation
  result = api_instance.account_number_reservation_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_number_reservation_id_get: #{e}"
end
```

#### Using the account_number_reservation_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountNumberReservationGet200ResponseInner>, Integer, Hash)> account_number_reservation_id_get_with_http_info(id)

```ruby
begin
  # get account-number-reservation
  data, status_code, headers = api_instance.account_number_reservation_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountNumberReservationGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_number_reservation_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**AccountNumberReservationGet200ResponseInner**](AccountNumberReservationGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_number_reservation_post

> <AccountNumberReservationGet200ResponseInner> account_number_reservation_post(body)

Create an Account Number Reservation

By default, accounts created through the Treasury Prime API are assigned system-generated account numbers at the time of account creation. However, certain integrations require knowing the account number that will be assigned prior to account creation. For those scenarios the account_number_reservation endpoint can be used to pre-allocate an account number when submitting an account application.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
body = 3.56 # Object | The account-number-reservation to create

begin
  # Create an Account Number Reservation
  result = api_instance.account_number_reservation_post(body)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_number_reservation_post: #{e}"
end
```

#### Using the account_number_reservation_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountNumberReservationGet200ResponseInner>, Integer, Hash)> account_number_reservation_post_with_http_info(body)

```ruby
begin
  # Create an Account Number Reservation
  data, status_code, headers = api_instance.account_number_reservation_post_with_http_info(body)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountNumberReservationGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_number_reservation_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **body** | **Object** | The account-number-reservation to create |  |

### Return type

[**AccountNumberReservationGet200ResponseInner**](AccountNumberReservationGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## account_post

> <AccountGet200Response> account_post(account_get_request)

create account.create

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
account_get_request = OpenapiClient::AccountGetRequest.new({account_number: 'account_number_example', name: 'name_example'}) # AccountGetRequest | The account.create to create

begin
  # create account.create
  result = api_instance.account_post(account_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_post: #{e}"
end
```

#### Using the account_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountGet200Response>, Integer, Hash)> account_post_with_http_info(account_get_request)

```ruby
begin
  # create account.create
  data, status_code, headers = api_instance.account_post_with_http_info(account_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_get_request** | [**AccountGetRequest**](AccountGetRequest.md) | The account.create to create |  |

### Return type

[**AccountGet200Response**](AccountGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## account_product_get

> <Array<AccountProductGet200ResponseInner>> account_product_get

index account_product

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index account_product
  result = api_instance.account_product_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_product_get: #{e}"
end
```

#### Using the account_product_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<AccountProductGet200ResponseInner>>, Integer, Hash)> account_product_get_with_http_info

```ruby
begin
  # index account_product
  data, status_code, headers = api_instance.account_product_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<AccountProductGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_product_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;AccountProductGet200ResponseInner&gt;**](AccountProductGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_product_id_get

> <AccountProductGet200ResponseInner> account_product_id_get

get account_product

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # get account_product
  result = api_instance.account_product_id_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_product_id_get: #{e}"
end
```

#### Using the account_product_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountProductGet200ResponseInner>, Integer, Hash)> account_product_id_get_with_http_info

```ruby
begin
  # get account_product
  data, status_code, headers = api_instance.account_product_id_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountProductGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_product_id_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**AccountProductGet200ResponseInner**](AccountProductGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## ach_get

> <Array<AchGet200ResponseInner>> ach_get

List All ACH Transfers

Returns a list of all existing ACH transfers that you have created, or an empty list if none are available.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # List All ACH Transfers
  result = api_instance.ach_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->ach_get: #{e}"
end
```

#### Using the ach_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<AchGet200ResponseInner>>, Integer, Hash)> ach_get_with_http_info

```ruby
begin
  # List All ACH Transfers
  data, status_code, headers = api_instance.ach_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<AchGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->ach_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;AchGet200ResponseInner&gt;**](AchGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## ach_id_get

> <AchGet200ResponseInner> ach_id_get(id)

get ach

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get ach
  result = api_instance.ach_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->ach_id_get: #{e}"
end
```

#### Using the ach_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AchGet200ResponseInner>, Integer, Hash)> ach_id_get_with_http_info(id)

```ruby
begin
  # get ach
  data, status_code, headers = api_instance.ach_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AchGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->ach_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**AchGet200ResponseInner**](AchGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## ach_id_patch

> <AchGet200ResponseInner> ach_id_patch(id, ach_id_get_request)

update ach

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
ach_id_get_request = OpenapiClient::AchIdGetRequest.new # AchIdGetRequest | The ach to update

begin
  # update ach
  result = api_instance.ach_id_patch(id, ach_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->ach_id_patch: #{e}"
end
```

#### Using the ach_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AchGet200ResponseInner>, Integer, Hash)> ach_id_patch_with_http_info(id, ach_id_get_request)

```ruby
begin
  # update ach
  data, status_code, headers = api_instance.ach_id_patch_with_http_info(id, ach_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AchGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->ach_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **ach_id_get_request** | [**AchIdGetRequest**](AchIdGetRequest.md) | The ach to update |  |

### Return type

[**AchGet200ResponseInner**](AchGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## ach_post

> <AchGet200ResponseInner> ach_post(ach_get_request)

Create an ACH

To initiate a new ACH transfer, you create a new ACH object.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
ach_get_request = OpenapiClient::AchGetRequest.new({amount: 'amount_example', service: TODO, counterparty_id: 'counterparty_id_example', account_id: 'account_id_example', sec_code: TODO, direction: TODO}) # AchGetRequest | The ach to create

begin
  # Create an ACH
  result = api_instance.ach_post(ach_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->ach_post: #{e}"
end
```

#### Using the ach_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AchGet200ResponseInner>, Integer, Hash)> ach_post_with_http_info(ach_get_request)

```ruby
begin
  # Create an ACH
  data, status_code, headers = api_instance.ach_post_with_http_info(ach_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AchGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->ach_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **ach_get_request** | [**AchGetRequest**](AchGetRequest.md) | The ach to create |  |

### Return type

[**AchGet200ResponseInner**](AchGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_account_application_get

> apply_account_application_get(opts)

Retrieve All Account Applications

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
opts = {
  id: '/aact_11hb4gm7b585bh' # String | Application ID
}

begin
  # Retrieve All Account Applications
  api_instance.apply_account_application_get(opts)
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_account_application_get: #{e}"
end
```

#### Using the apply_account_application_get_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> apply_account_application_get_with_http_info(opts)

```ruby
begin
  # Retrieve All Account Applications
  data, status_code, headers = api_instance.apply_account_application_get_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_account_application_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Application ID | [optional] |

### Return type

nil (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## apply_account_application_id_get

> <ApplyAccountApplicationIdGet200Response> apply_account_application_id_get(id)

get apply.account-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get apply.account-application
  result = api_instance.apply_account_application_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_account_application_id_get: #{e}"
end
```

#### Using the apply_account_application_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyAccountApplicationIdGet200Response>, Integer, Hash)> apply_account_application_id_get_with_http_info(id)

```ruby
begin
  # get apply.account-application
  data, status_code, headers = api_instance.apply_account_application_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyAccountApplicationIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_account_application_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**ApplyAccountApplicationIdGet200Response**](ApplyAccountApplicationIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_account_application_id_patch

> <ApplyAccountApplicationIdGet200Response> apply_account_application_id_patch(id, apply_account_application_id_get_request)

update apply.account-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
apply_account_application_id_get_request = OpenapiClient::ApplyAccountApplicationIdGetRequest.new # ApplyAccountApplicationIdGetRequest | The apply.account-application to update

begin
  # update apply.account-application
  result = api_instance.apply_account_application_id_patch(id, apply_account_application_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_account_application_id_patch: #{e}"
end
```

#### Using the apply_account_application_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyAccountApplicationIdGet200Response>, Integer, Hash)> apply_account_application_id_patch_with_http_info(id, apply_account_application_id_get_request)

```ruby
begin
  # update apply.account-application
  data, status_code, headers = api_instance.apply_account_application_id_patch_with_http_info(id, apply_account_application_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyAccountApplicationIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_account_application_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **apply_account_application_id_get_request** | [**ApplyAccountApplicationIdGetRequest**](ApplyAccountApplicationIdGetRequest.md) | The apply.account-application to update |  |

### Return type

[**ApplyAccountApplicationIdGet200Response**](ApplyAccountApplicationIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_account_application_post

> String apply_account_application_post(opts)

Create Account Application

To create an application for a new bank account, create an Account Application object.  This example demonstrates the creation of a Personal account. Business accounts are very similar, but will utilize a few different fields. Please see [https://developers.treasuryprime.com/guides/open-accounts](https://developers.treasuryprime.com/guides/open-accounts) for more information.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
opts = {
  apply_account_application_get_request: OpenapiClient::ApplyAccountApplicationGetRequest.new # ApplyAccountApplicationGetRequest | 
}

begin
  # Create Account Application
  result = api_instance.apply_account_application_post(opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_account_application_post: #{e}"
end
```

#### Using the apply_account_application_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> apply_account_application_post_with_http_info(opts)

```ruby
begin
  # Create Account Application
  data, status_code, headers = api_instance.apply_account_application_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_account_application_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **apply_account_application_get_request** | [**ApplyAccountApplicationGetRequest**](ApplyAccountApplicationGetRequest.md) |  | [optional] |

### Return type

**String**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: text/plain, application/json


## apply_additional_person_application_get

> <Array<ApplyAdditionalPersonApplicationIdGet200Response>> apply_additional_person_application_get

index apply.additional-person-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index apply.additional-person-application
  result = api_instance.apply_additional_person_application_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_additional_person_application_get: #{e}"
end
```

#### Using the apply_additional_person_application_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<ApplyAdditionalPersonApplicationIdGet200Response>>, Integer, Hash)> apply_additional_person_application_get_with_http_info

```ruby
begin
  # index apply.additional-person-application
  data, status_code, headers = api_instance.apply_additional_person_application_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<ApplyAdditionalPersonApplicationIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_additional_person_application_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;ApplyAdditionalPersonApplicationIdGet200Response&gt;**](ApplyAdditionalPersonApplicationIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_additional_person_application_id_get

> <ApplyAdditionalPersonApplicationIdGet200Response> apply_additional_person_application_id_get(id)

Retrieve an Additional Person Application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # Retrieve an Additional Person Application
  result = api_instance.apply_additional_person_application_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_additional_person_application_id_get: #{e}"
end
```

#### Using the apply_additional_person_application_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyAdditionalPersonApplicationIdGet200Response>, Integer, Hash)> apply_additional_person_application_id_get_with_http_info(id)

```ruby
begin
  # Retrieve an Additional Person Application
  data, status_code, headers = api_instance.apply_additional_person_application_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyAdditionalPersonApplicationIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_additional_person_application_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**ApplyAdditionalPersonApplicationIdGet200Response**](ApplyAdditionalPersonApplicationIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_additional_person_application_id_patch

> <ApplyAdditionalPersonApplicationIdGet200Response> apply_additional_person_application_id_patch(id, apply_additional_person_application_id_get_request)

Update an Additional Person Applications

Updates the specified Additional Person Application by setting the values of the passed parameters. Any parameters not provided will be left unchanged. Note: only the userdata parameter is permitted to change.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
apply_additional_person_application_id_get_request = OpenapiClient::ApplyAdditionalPersonApplicationIdGetRequest.new # ApplyAdditionalPersonApplicationIdGetRequest | The apply.additional-person-application to update

begin
  # Update an Additional Person Applications
  result = api_instance.apply_additional_person_application_id_patch(id, apply_additional_person_application_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_additional_person_application_id_patch: #{e}"
end
```

#### Using the apply_additional_person_application_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyAdditionalPersonApplicationIdGet200Response>, Integer, Hash)> apply_additional_person_application_id_patch_with_http_info(id, apply_additional_person_application_id_get_request)

```ruby
begin
  # Update an Additional Person Applications
  data, status_code, headers = api_instance.apply_additional_person_application_id_patch_with_http_info(id, apply_additional_person_application_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyAdditionalPersonApplicationIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_additional_person_application_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **apply_additional_person_application_id_get_request** | [**ApplyAdditionalPersonApplicationIdGetRequest**](ApplyAdditionalPersonApplicationIdGetRequest.md) | The apply.additional-person-application to update |  |

### Return type

[**ApplyAdditionalPersonApplicationIdGet200Response**](ApplyAdditionalPersonApplicationIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_additional_person_application_post

> <ApplyAdditionalPersonApplicationIdGet200Response> apply_additional_person_application_post(apply_additional_person_application_get_request)

create apply.additional-person-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
apply_additional_person_application_get_request = OpenapiClient::ApplyAdditionalPersonApplicationGetRequest.new({role: TODO, account_id: 'account_id_example', person_application_id: 'person_application_id_example'}) # ApplyAdditionalPersonApplicationGetRequest | The apply.additional-person-application to create

begin
  # create apply.additional-person-application
  result = api_instance.apply_additional_person_application_post(apply_additional_person_application_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_additional_person_application_post: #{e}"
end
```

#### Using the apply_additional_person_application_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyAdditionalPersonApplicationIdGet200Response>, Integer, Hash)> apply_additional_person_application_post_with_http_info(apply_additional_person_application_get_request)

```ruby
begin
  # create apply.additional-person-application
  data, status_code, headers = api_instance.apply_additional_person_application_post_with_http_info(apply_additional_person_application_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyAdditionalPersonApplicationIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_additional_person_application_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **apply_additional_person_application_get_request** | [**ApplyAdditionalPersonApplicationGetRequest**](ApplyAdditionalPersonApplicationGetRequest.md) | The apply.additional-person-application to create |  |

### Return type

[**ApplyAdditionalPersonApplicationIdGet200Response**](ApplyAdditionalPersonApplicationIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_authorized_user_application_get

> <Array<ApplyAuthorizedUserApplicationGet200ResponseInner>> apply_authorized_user_application_get

index apply.authorized-user-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index apply.authorized-user-application
  result = api_instance.apply_authorized_user_application_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_authorized_user_application_get: #{e}"
end
```

#### Using the apply_authorized_user_application_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<ApplyAuthorizedUserApplicationGet200ResponseInner>>, Integer, Hash)> apply_authorized_user_application_get_with_http_info

```ruby
begin
  # index apply.authorized-user-application
  data, status_code, headers = api_instance.apply_authorized_user_application_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<ApplyAuthorizedUserApplicationGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_authorized_user_application_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;ApplyAuthorizedUserApplicationGet200ResponseInner&gt;**](ApplyAuthorizedUserApplicationGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_authorized_user_application_id_get

> <ApplyAuthorizedUserApplicationGet200ResponseInner> apply_authorized_user_application_id_get(id)

get apply.authorized-user-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get apply.authorized-user-application
  result = api_instance.apply_authorized_user_application_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_authorized_user_application_id_get: #{e}"
end
```

#### Using the apply_authorized_user_application_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyAuthorizedUserApplicationGet200ResponseInner>, Integer, Hash)> apply_authorized_user_application_id_get_with_http_info(id)

```ruby
begin
  # get apply.authorized-user-application
  data, status_code, headers = api_instance.apply_authorized_user_application_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyAuthorizedUserApplicationGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_authorized_user_application_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**ApplyAuthorizedUserApplicationGet200ResponseInner**](ApplyAuthorizedUserApplicationGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_authorized_user_application_id_patch

> <ApplyAuthorizedUserApplicationGet200ResponseInner> apply_authorized_user_application_id_patch(id, apply_authorized_user_application_id_get_request)

update apply.authorized-user-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
apply_authorized_user_application_id_get_request = OpenapiClient::ApplyAuthorizedUserApplicationIdGetRequest.new # ApplyAuthorizedUserApplicationIdGetRequest | The apply.authorized-user-application to update

begin
  # update apply.authorized-user-application
  result = api_instance.apply_authorized_user_application_id_patch(id, apply_authorized_user_application_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_authorized_user_application_id_patch: #{e}"
end
```

#### Using the apply_authorized_user_application_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyAuthorizedUserApplicationGet200ResponseInner>, Integer, Hash)> apply_authorized_user_application_id_patch_with_http_info(id, apply_authorized_user_application_id_get_request)

```ruby
begin
  # update apply.authorized-user-application
  data, status_code, headers = api_instance.apply_authorized_user_application_id_patch_with_http_info(id, apply_authorized_user_application_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyAuthorizedUserApplicationGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_authorized_user_application_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **apply_authorized_user_application_id_get_request** | [**ApplyAuthorizedUserApplicationIdGetRequest**](ApplyAuthorizedUserApplicationIdGetRequest.md) | The apply.authorized-user-application to update |  |

### Return type

[**ApplyAuthorizedUserApplicationGet200ResponseInner**](ApplyAuthorizedUserApplicationGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_authorized_user_application_post

> <ApplyAuthorizedUserApplicationGet200ResponseInner> apply_authorized_user_application_post(apply_authorized_user_application_get_request)

create apply.authorized-user-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
apply_authorized_user_application_get_request = OpenapiClient::ApplyAuthorizedUserApplicationGetRequest.new({account_id: 'account_id_example', person_application_id: 'person_application_id_example'}) # ApplyAuthorizedUserApplicationGetRequest | The apply.authorized-user-application to create

begin
  # create apply.authorized-user-application
  result = api_instance.apply_authorized_user_application_post(apply_authorized_user_application_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_authorized_user_application_post: #{e}"
end
```

#### Using the apply_authorized_user_application_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyAuthorizedUserApplicationGet200ResponseInner>, Integer, Hash)> apply_authorized_user_application_post_with_http_info(apply_authorized_user_application_get_request)

```ruby
begin
  # create apply.authorized-user-application
  data, status_code, headers = api_instance.apply_authorized_user_application_post_with_http_info(apply_authorized_user_application_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyAuthorizedUserApplicationGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_authorized_user_application_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **apply_authorized_user_application_get_request** | [**ApplyAuthorizedUserApplicationGetRequest**](ApplyAuthorizedUserApplicationGetRequest.md) | The apply.authorized-user-application to create |  |

### Return type

[**ApplyAuthorizedUserApplicationGet200ResponseInner**](ApplyAuthorizedUserApplicationGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_business_application_get

> <Array<ApplyBusinessApplicationIdGet200Response>> apply_business_application_get

index apply.business-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index apply.business-application
  result = api_instance.apply_business_application_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_business_application_get: #{e}"
end
```

#### Using the apply_business_application_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<ApplyBusinessApplicationIdGet200Response>>, Integer, Hash)> apply_business_application_get_with_http_info

```ruby
begin
  # index apply.business-application
  data, status_code, headers = api_instance.apply_business_application_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<ApplyBusinessApplicationIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_business_application_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;ApplyBusinessApplicationIdGet200Response&gt;**](ApplyBusinessApplicationIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_business_application_id_get

> <ApplyBusinessApplicationIdGet200Response> apply_business_application_id_get(id)

get apply.business-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get apply.business-application
  result = api_instance.apply_business_application_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_business_application_id_get: #{e}"
end
```

#### Using the apply_business_application_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyBusinessApplicationIdGet200Response>, Integer, Hash)> apply_business_application_id_get_with_http_info(id)

```ruby
begin
  # get apply.business-application
  data, status_code, headers = api_instance.apply_business_application_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyBusinessApplicationIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_business_application_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**ApplyBusinessApplicationIdGet200Response**](ApplyBusinessApplicationIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_business_application_id_patch

> <ApplyBusinessApplicationIdGet200Response> apply_business_application_id_patch(id, apply_business_application_id_get_request)

update apply.business-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
apply_business_application_id_get_request = OpenapiClient::ApplyBusinessApplicationIdGetRequest.new # ApplyBusinessApplicationIdGetRequest | The apply.business-application to update

begin
  # update apply.business-application
  result = api_instance.apply_business_application_id_patch(id, apply_business_application_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_business_application_id_patch: #{e}"
end
```

#### Using the apply_business_application_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyBusinessApplicationIdGet200Response>, Integer, Hash)> apply_business_application_id_patch_with_http_info(id, apply_business_application_id_get_request)

```ruby
begin
  # update apply.business-application
  data, status_code, headers = api_instance.apply_business_application_id_patch_with_http_info(id, apply_business_application_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyBusinessApplicationIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_business_application_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **apply_business_application_id_get_request** | [**ApplyBusinessApplicationIdGetRequest**](ApplyBusinessApplicationIdGetRequest.md) | The apply.business-application to update |  |

### Return type

[**ApplyBusinessApplicationIdGet200Response**](ApplyBusinessApplicationIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_business_application_post

> <ApplyBusinessApplicationIdGet200Response> apply_business_application_post(apply_business_application_get_request)

create apply.business-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
apply_business_application_get_request = OpenapiClient::ApplyBusinessApplicationGetRequest.new({tin: TODO, legal_structure: TODO, name: 'name_example', incorporation_state: 'incorporation_state_example', person_applications: 3.56}) # ApplyBusinessApplicationGetRequest | The apply.business-application to create

begin
  # create apply.business-application
  result = api_instance.apply_business_application_post(apply_business_application_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_business_application_post: #{e}"
end
```

#### Using the apply_business_application_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyBusinessApplicationIdGet200Response>, Integer, Hash)> apply_business_application_post_with_http_info(apply_business_application_get_request)

```ruby
begin
  # create apply.business-application
  data, status_code, headers = api_instance.apply_business_application_post_with_http_info(apply_business_application_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyBusinessApplicationIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_business_application_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **apply_business_application_get_request** | [**ApplyBusinessApplicationGetRequest**](ApplyBusinessApplicationGetRequest.md) | The apply.business-application to create |  |

### Return type

[**ApplyBusinessApplicationIdGet200Response**](ApplyBusinessApplicationIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_compliance_get

> <Array<ApplyComplianceGet200ResponseInner>> apply_compliance_get

index apply.compliance

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index apply.compliance
  result = api_instance.apply_compliance_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_compliance_get: #{e}"
end
```

#### Using the apply_compliance_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<ApplyComplianceGet200ResponseInner>>, Integer, Hash)> apply_compliance_get_with_http_info

```ruby
begin
  # index apply.compliance
  data, status_code, headers = api_instance.apply_compliance_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<ApplyComplianceGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_compliance_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;ApplyComplianceGet200ResponseInner&gt;**](ApplyComplianceGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_compliance_id_get

> <ApplyComplianceGet200ResponseInner> apply_compliance_id_get(id)

get apply.compliance

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get apply.compliance
  result = api_instance.apply_compliance_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_compliance_id_get: #{e}"
end
```

#### Using the apply_compliance_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyComplianceGet200ResponseInner>, Integer, Hash)> apply_compliance_id_get_with_http_info(id)

```ruby
begin
  # get apply.compliance
  data, status_code, headers = api_instance.apply_compliance_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyComplianceGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_compliance_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**ApplyComplianceGet200ResponseInner**](ApplyComplianceGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_compliance_post

> <ApplyComplianceGet200ResponseInner> apply_compliance_post(apply_compliance_get_request)

create apply.compliance

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
apply_compliance_get_request = OpenapiClient::ApplyComplianceGetRequest.new({object_id: 'object_id_example', name: 'name_example', type: 'type_example', account_application_id: 'account_application_id_example'}) # ApplyComplianceGetRequest | The apply.compliance to create

begin
  # create apply.compliance
  result = api_instance.apply_compliance_post(apply_compliance_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_compliance_post: #{e}"
end
```

#### Using the apply_compliance_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyComplianceGet200ResponseInner>, Integer, Hash)> apply_compliance_post_with_http_info(apply_compliance_get_request)

```ruby
begin
  # create apply.compliance
  data, status_code, headers = api_instance.apply_compliance_post_with_http_info(apply_compliance_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyComplianceGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_compliance_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **apply_compliance_get_request** | [**ApplyComplianceGetRequest**](ApplyComplianceGetRequest.md) | The apply.compliance to create |  |

### Return type

[**ApplyComplianceGet200ResponseInner**](ApplyComplianceGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_deposit_get

> <Array<ApplyDepositIdGet200Response>> apply_deposit_get

index apply.deposit

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index apply.deposit
  result = api_instance.apply_deposit_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_deposit_get: #{e}"
end
```

#### Using the apply_deposit_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<ApplyDepositIdGet200Response>>, Integer, Hash)> apply_deposit_get_with_http_info

```ruby
begin
  # index apply.deposit
  data, status_code, headers = api_instance.apply_deposit_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<ApplyDepositIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_deposit_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;ApplyDepositIdGet200Response&gt;**](ApplyDepositIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_deposit_id_get

> <ApplyDepositIdGet200Response> apply_deposit_id_get(id)

get apply.deposit

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get apply.deposit
  result = api_instance.apply_deposit_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_deposit_id_get: #{e}"
end
```

#### Using the apply_deposit_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyDepositIdGet200Response>, Integer, Hash)> apply_deposit_id_get_with_http_info(id)

```ruby
begin
  # get apply.deposit
  data, status_code, headers = api_instance.apply_deposit_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyDepositIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_deposit_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**ApplyDepositIdGet200Response**](ApplyDepositIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_deposit_post

> <ApplyDepositIdGet200Response> apply_deposit_post(apply_deposit_get_request)

create apply.deposit

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
apply_deposit_get_request = OpenapiClient::ApplyDepositGetRequest.new({amount: 'amount_example', name_on_account: 'name_on_account_example'}) # ApplyDepositGetRequest | The apply.deposit to create

begin
  # create apply.deposit
  result = api_instance.apply_deposit_post(apply_deposit_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_deposit_post: #{e}"
end
```

#### Using the apply_deposit_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyDepositIdGet200Response>, Integer, Hash)> apply_deposit_post_with_http_info(apply_deposit_get_request)

```ruby
begin
  # create apply.deposit
  data, status_code, headers = api_instance.apply_deposit_post_with_http_info(apply_deposit_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyDepositIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_deposit_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **apply_deposit_get_request** | [**ApplyDepositGetRequest**](ApplyDepositGetRequest.md) | The apply.deposit to create |  |

### Return type

[**ApplyDepositIdGet200Response**](ApplyDepositIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_kyc_get

> <Array<ApplyKycIdGet200Response>> apply_kyc_get

index apply.kyc

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index apply.kyc
  result = api_instance.apply_kyc_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_get: #{e}"
end
```

#### Using the apply_kyc_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<ApplyKycIdGet200Response>>, Integer, Hash)> apply_kyc_get_with_http_info

```ruby
begin
  # index apply.kyc
  data, status_code, headers = api_instance.apply_kyc_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<ApplyKycIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;ApplyKycIdGet200Response&gt;**](ApplyKycIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_kyc_id_get

> <ApplyKycIdGet200Response> apply_kyc_id_get(id)

get apply.kyc

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get apply.kyc
  result = api_instance.apply_kyc_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_id_get: #{e}"
end
```

#### Using the apply_kyc_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyKycIdGet200Response>, Integer, Hash)> apply_kyc_id_get_with_http_info(id)

```ruby
begin
  # get apply.kyc
  data, status_code, headers = api_instance.apply_kyc_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyKycIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**ApplyKycIdGet200Response**](ApplyKycIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_kyc_post

> <ApplyKycIdGet200Response> apply_kyc_post(apply_kyc_get_request)

create apply.kyc

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
apply_kyc_get_request = OpenapiClient::ApplyKycGetRequest.new({object_id: 'object_id_example', object_type: TODO}) # ApplyKycGetRequest | The apply.kyc to create

begin
  # create apply.kyc
  result = api_instance.apply_kyc_post(apply_kyc_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_post: #{e}"
end
```

#### Using the apply_kyc_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyKycIdGet200Response>, Integer, Hash)> apply_kyc_post_with_http_info(apply_kyc_get_request)

```ruby
begin
  # create apply.kyc
  data, status_code, headers = api_instance.apply_kyc_post_with_http_info(apply_kyc_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyKycIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **apply_kyc_get_request** | [**ApplyKycGetRequest**](ApplyKycGetRequest.md) | The apply.kyc to create |  |

### Return type

[**ApplyKycIdGet200Response**](ApplyKycIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_kyc_product_get

> <Array<ApplyKycProductGet200ResponseInner>> apply_kyc_product_get

index apply.kyc-product

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index apply.kyc-product
  result = api_instance.apply_kyc_product_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_product_get: #{e}"
end
```

#### Using the apply_kyc_product_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<ApplyKycProductGet200ResponseInner>>, Integer, Hash)> apply_kyc_product_get_with_http_info

```ruby
begin
  # index apply.kyc-product
  data, status_code, headers = api_instance.apply_kyc_product_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<ApplyKycProductGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_product_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;ApplyKycProductGet200ResponseInner&gt;**](ApplyKycProductGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_kyc_product_id_get

> <ApplyKycProductGet200ResponseInner> apply_kyc_product_id_get(id)

get apply.kyc-product

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get apply.kyc-product
  result = api_instance.apply_kyc_product_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_product_id_get: #{e}"
end
```

#### Using the apply_kyc_product_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyKycProductGet200ResponseInner>, Integer, Hash)> apply_kyc_product_id_get_with_http_info(id)

```ruby
begin
  # get apply.kyc-product
  data, status_code, headers = api_instance.apply_kyc_product_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyKycProductGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_product_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**ApplyKycProductGet200ResponseInner**](ApplyKycProductGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_kyc_product_id_patch

> <ApplyKycProductGet200ResponseInner> apply_kyc_product_id_patch(id, apply_kyc_product_id_get_request)

update apply.kyc-product

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
apply_kyc_product_id_get_request = OpenapiClient::ApplyKycProductIdGetRequest.new # ApplyKycProductIdGetRequest | The apply.kyc-product to update

begin
  # update apply.kyc-product
  result = api_instance.apply_kyc_product_id_patch(id, apply_kyc_product_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_product_id_patch: #{e}"
end
```

#### Using the apply_kyc_product_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyKycProductGet200ResponseInner>, Integer, Hash)> apply_kyc_product_id_patch_with_http_info(id, apply_kyc_product_id_get_request)

```ruby
begin
  # update apply.kyc-product
  data, status_code, headers = api_instance.apply_kyc_product_id_patch_with_http_info(id, apply_kyc_product_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyKycProductGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_product_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **apply_kyc_product_id_get_request** | [**ApplyKycProductIdGetRequest**](ApplyKycProductIdGetRequest.md) | The apply.kyc-product to update |  |

### Return type

[**ApplyKycProductGet200ResponseInner**](ApplyKycProductGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_kyc_product_post

> <ApplyKycProductGet200ResponseInner> apply_kyc_product_post(apply_kyc_product_get_request)

create apply.kyc-product

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
apply_kyc_product_get_request = OpenapiClient::ApplyKycProductGetRequest.new({object_type: 'object_type_example', name: 'name_example', is_default: false}) # ApplyKycProductGetRequest | The apply.kyc-product to create

begin
  # create apply.kyc-product
  result = api_instance.apply_kyc_product_post(apply_kyc_product_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_product_post: #{e}"
end
```

#### Using the apply_kyc_product_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyKycProductGet200ResponseInner>, Integer, Hash)> apply_kyc_product_post_with_http_info(apply_kyc_product_get_request)

```ruby
begin
  # create apply.kyc-product
  data, status_code, headers = api_instance.apply_kyc_product_post_with_http_info(apply_kyc_product_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyKycProductGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_kyc_product_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **apply_kyc_product_get_request** | [**ApplyKycProductGetRequest**](ApplyKycProductGetRequest.md) | The apply.kyc-product to create |  |

### Return type

[**ApplyKycProductGet200ResponseInner**](ApplyKycProductGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_parent_business_get

> <Array<ApplyParentBusinessIdGet200Response>> apply_parent_business_get

index apply.parent-business

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index apply.parent-business
  result = api_instance.apply_parent_business_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_parent_business_get: #{e}"
end
```

#### Using the apply_parent_business_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<ApplyParentBusinessIdGet200Response>>, Integer, Hash)> apply_parent_business_get_with_http_info

```ruby
begin
  # index apply.parent-business
  data, status_code, headers = api_instance.apply_parent_business_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<ApplyParentBusinessIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_parent_business_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;ApplyParentBusinessIdGet200Response&gt;**](ApplyParentBusinessIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_parent_business_id_get

> <ApplyParentBusinessIdGet200Response> apply_parent_business_id_get(id)

get apply.parent-business

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get apply.parent-business
  result = api_instance.apply_parent_business_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_parent_business_id_get: #{e}"
end
```

#### Using the apply_parent_business_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyParentBusinessIdGet200Response>, Integer, Hash)> apply_parent_business_id_get_with_http_info(id)

```ruby
begin
  # get apply.parent-business
  data, status_code, headers = api_instance.apply_parent_business_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyParentBusinessIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_parent_business_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**ApplyParentBusinessIdGet200Response**](ApplyParentBusinessIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_parent_business_id_patch

> <ApplyParentBusinessIdGet200Response> apply_parent_business_id_patch(id, apply_parent_business_id_get_request)

update apply.parent-business

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
apply_parent_business_id_get_request = OpenapiClient::ApplyParentBusinessIdGetRequest.new # ApplyParentBusinessIdGetRequest | The apply.parent-business to update

begin
  # update apply.parent-business
  result = api_instance.apply_parent_business_id_patch(id, apply_parent_business_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_parent_business_id_patch: #{e}"
end
```

#### Using the apply_parent_business_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyParentBusinessIdGet200Response>, Integer, Hash)> apply_parent_business_id_patch_with_http_info(id, apply_parent_business_id_get_request)

```ruby
begin
  # update apply.parent-business
  data, status_code, headers = api_instance.apply_parent_business_id_patch_with_http_info(id, apply_parent_business_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyParentBusinessIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_parent_business_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **apply_parent_business_id_get_request** | [**ApplyParentBusinessIdGetRequest**](ApplyParentBusinessIdGetRequest.md) | The apply.parent-business to update |  |

### Return type

[**ApplyParentBusinessIdGet200Response**](ApplyParentBusinessIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_parent_business_post

> <ApplyParentBusinessIdGet200Response> apply_parent_business_post(apply_parent_business_get_request)

create apply.parent-business

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
apply_parent_business_get_request = OpenapiClient::ApplyParentBusinessGetRequest.new({tin: TODO, legal_structure: TODO, name: 'name_example', incorporation_state: 'incorporation_state_example'}) # ApplyParentBusinessGetRequest | The apply.parent-business to create

begin
  # create apply.parent-business
  result = api_instance.apply_parent_business_post(apply_parent_business_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_parent_business_post: #{e}"
end
```

#### Using the apply_parent_business_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyParentBusinessIdGet200Response>, Integer, Hash)> apply_parent_business_post_with_http_info(apply_parent_business_get_request)

```ruby
begin
  # create apply.parent-business
  data, status_code, headers = api_instance.apply_parent_business_post_with_http_info(apply_parent_business_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyParentBusinessIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_parent_business_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **apply_parent_business_get_request** | [**ApplyParentBusinessGetRequest**](ApplyParentBusinessGetRequest.md) | The apply.parent-business to create |  |

### Return type

[**ApplyParentBusinessIdGet200Response**](ApplyParentBusinessIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_person_application_get

> <Array<ApplyPersonApplicationGet200ResponseInner>> apply_person_application_get

index apply.person-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index apply.person-application
  result = api_instance.apply_person_application_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_person_application_get: #{e}"
end
```

#### Using the apply_person_application_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<ApplyPersonApplicationGet200ResponseInner>>, Integer, Hash)> apply_person_application_get_with_http_info

```ruby
begin
  # index apply.person-application
  data, status_code, headers = api_instance.apply_person_application_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<ApplyPersonApplicationGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_person_application_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;ApplyPersonApplicationGet200ResponseInner&gt;**](ApplyPersonApplicationGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_person_application_id_get

> <ApplyPersonApplicationGet200ResponseInner> apply_person_application_id_get(id)

get apply.person-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get apply.person-application
  result = api_instance.apply_person_application_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_person_application_id_get: #{e}"
end
```

#### Using the apply_person_application_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyPersonApplicationGet200ResponseInner>, Integer, Hash)> apply_person_application_id_get_with_http_info(id)

```ruby
begin
  # get apply.person-application
  data, status_code, headers = api_instance.apply_person_application_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyPersonApplicationGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_person_application_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**ApplyPersonApplicationGet200ResponseInner**](ApplyPersonApplicationGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## apply_person_application_id_patch

> <ApplyPersonApplicationGet200ResponseInner> apply_person_application_id_patch(id, apply_person_application_id_get_request)

update apply.person-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
apply_person_application_id_get_request = OpenapiClient::ApplyPersonApplicationIdGetRequest.new # ApplyPersonApplicationIdGetRequest | The apply.person-application to update

begin
  # update apply.person-application
  result = api_instance.apply_person_application_id_patch(id, apply_person_application_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_person_application_id_patch: #{e}"
end
```

#### Using the apply_person_application_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyPersonApplicationGet200ResponseInner>, Integer, Hash)> apply_person_application_id_patch_with_http_info(id, apply_person_application_id_get_request)

```ruby
begin
  # update apply.person-application
  data, status_code, headers = api_instance.apply_person_application_id_patch_with_http_info(id, apply_person_application_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyPersonApplicationGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_person_application_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **apply_person_application_id_get_request** | [**ApplyPersonApplicationIdGetRequest**](ApplyPersonApplicationIdGetRequest.md) | The apply.person-application to update |  |

### Return type

[**ApplyPersonApplicationGet200ResponseInner**](ApplyPersonApplicationGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## apply_person_application_post

> <ApplyPersonApplicationGet200ResponseInner> apply_person_application_post(apply_person_application_get_request)

create apply.person-application

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
apply_person_application_get_request = OpenapiClient::ApplyPersonApplicationGetRequest.new({first_name: TODO, last_name: TODO, email_address: TODO}) # ApplyPersonApplicationGetRequest | The apply.person-application to create

begin
  # create apply.person-application
  result = api_instance.apply_person_application_post(apply_person_application_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_person_application_post: #{e}"
end
```

#### Using the apply_person_application_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplyPersonApplicationGet200ResponseInner>, Integer, Hash)> apply_person_application_post_with_http_info(apply_person_application_get_request)

```ruby
begin
  # create apply.person-application
  data, status_code, headers = api_instance.apply_person_application_post_with_http_info(apply_person_application_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplyPersonApplicationGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->apply_person_application_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **apply_person_application_get_request** | [**ApplyPersonApplicationGetRequest**](ApplyPersonApplicationGetRequest.md) | The apply.person-application to create |  |

### Return type

[**ApplyPersonApplicationGet200ResponseInner**](ApplyPersonApplicationGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## billpay_counterparty_get

> <Array<BillpayCounterpartyIdGet200Response>> billpay_counterparty_get

index billpay_counterparty

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index billpay_counterparty
  result = api_instance.billpay_counterparty_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_counterparty_get: #{e}"
end
```

#### Using the billpay_counterparty_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<BillpayCounterpartyIdGet200Response>>, Integer, Hash)> billpay_counterparty_get_with_http_info

```ruby
begin
  # index billpay_counterparty
  data, status_code, headers = api_instance.billpay_counterparty_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<BillpayCounterpartyIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_counterparty_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;BillpayCounterpartyIdGet200Response&gt;**](BillpayCounterpartyIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## billpay_counterparty_id_get

> <BillpayCounterpartyIdGet200Response> billpay_counterparty_id_get(id)

Retrieve a Bill Pay Counterparty

A Bill Pay Counterparty represents the person or organization receiving the bill payment. Bill Pay Counterparties are similar to ordinary Counterparties but they have some key differences. The biggest difference is that the Bill Pay Counterparty is explicitly linked to a particular Account. Always be sure to use a Bill Pay Counterparty when accessing the Bill Pay APIs. Counterparties may be added manually or pre-populated with a Merchant's payment information. Payments to manually-added counterparties will be sent via direct check, whereas pre-populated merchants will be paid electronically.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # Retrieve a Bill Pay Counterparty
  result = api_instance.billpay_counterparty_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_counterparty_id_get: #{e}"
end
```

#### Using the billpay_counterparty_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BillpayCounterpartyIdGet200Response>, Integer, Hash)> billpay_counterparty_id_get_with_http_info(id)

```ruby
begin
  # Retrieve a Bill Pay Counterparty
  data, status_code, headers = api_instance.billpay_counterparty_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BillpayCounterpartyIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_counterparty_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**BillpayCounterpartyIdGet200Response**](BillpayCounterpartyIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## billpay_counterparty_id_patch

> <BillpayCounterpartyIdGet200Response> billpay_counterparty_id_patch(id, billpay_counterparty_id_get_request)

update billpay_counterparty

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
billpay_counterparty_id_get_request = OpenapiClient::BillpayCounterpartyIdGetRequest.new # BillpayCounterpartyIdGetRequest | The billpay_counterparty to update

begin
  # update billpay_counterparty
  result = api_instance.billpay_counterparty_id_patch(id, billpay_counterparty_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_counterparty_id_patch: #{e}"
end
```

#### Using the billpay_counterparty_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BillpayCounterpartyIdGet200Response>, Integer, Hash)> billpay_counterparty_id_patch_with_http_info(id, billpay_counterparty_id_get_request)

```ruby
begin
  # update billpay_counterparty
  data, status_code, headers = api_instance.billpay_counterparty_id_patch_with_http_info(id, billpay_counterparty_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BillpayCounterpartyIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_counterparty_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **billpay_counterparty_id_get_request** | [**BillpayCounterpartyIdGetRequest**](BillpayCounterpartyIdGetRequest.md) | The billpay_counterparty to update |  |

### Return type

[**BillpayCounterpartyIdGet200Response**](BillpayCounterpartyIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## billpay_counterparty_post

> <BillpayCounterpartyIdGet200Response> billpay_counterparty_post(billpay_counterparty_get_request)

create billpay_counterparty

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
billpay_counterparty_get_request = OpenapiClient::BillpayCounterpartyGetRequest.new({account_id: 'account_id_example'}) # BillpayCounterpartyGetRequest | The billpay_counterparty to create

begin
  # create billpay_counterparty
  result = api_instance.billpay_counterparty_post(billpay_counterparty_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_counterparty_post: #{e}"
end
```

#### Using the billpay_counterparty_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BillpayCounterpartyIdGet200Response>, Integer, Hash)> billpay_counterparty_post_with_http_info(billpay_counterparty_get_request)

```ruby
begin
  # create billpay_counterparty
  data, status_code, headers = api_instance.billpay_counterparty_post_with_http_info(billpay_counterparty_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BillpayCounterpartyIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_counterparty_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **billpay_counterparty_get_request** | [**BillpayCounterpartyGetRequest**](BillpayCounterpartyGetRequest.md) | The billpay_counterparty to create |  |

### Return type

[**BillpayCounterpartyIdGet200Response**](BillpayCounterpartyIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## billpay_merchant_get

> <BillpayMerchantGet200Response> billpay_merchant_get

get billpay_merchant

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # get billpay_merchant
  result = api_instance.billpay_merchant_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_merchant_get: #{e}"
end
```

#### Using the billpay_merchant_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BillpayMerchantGet200Response>, Integer, Hash)> billpay_merchant_get_with_http_info

```ruby
begin
  # get billpay_merchant
  data, status_code, headers = api_instance.billpay_merchant_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BillpayMerchantGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_merchant_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**BillpayMerchantGet200Response**](BillpayMerchantGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## billpay_payment_get

> <Array<BillpayPaymentIdGet200Response>> billpay_payment_get

index billpay_payment

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index billpay_payment
  result = api_instance.billpay_payment_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_payment_get: #{e}"
end
```

#### Using the billpay_payment_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<BillpayPaymentIdGet200Response>>, Integer, Hash)> billpay_payment_get_with_http_info

```ruby
begin
  # index billpay_payment
  data, status_code, headers = api_instance.billpay_payment_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<BillpayPaymentIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_payment_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;BillpayPaymentIdGet200Response&gt;**](BillpayPaymentIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## billpay_payment_id_get

> <BillpayPaymentIdGet200Response> billpay_payment_id_get(id)

get billpay_payment

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get billpay_payment
  result = api_instance.billpay_payment_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_payment_id_get: #{e}"
end
```

#### Using the billpay_payment_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BillpayPaymentIdGet200Response>, Integer, Hash)> billpay_payment_id_get_with_http_info(id)

```ruby
begin
  # get billpay_payment
  data, status_code, headers = api_instance.billpay_payment_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BillpayPaymentIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_payment_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**BillpayPaymentIdGet200Response**](BillpayPaymentIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## billpay_payment_id_patch

> <BillpayPaymentIdGet200Response> billpay_payment_id_patch(id, billpay_payment_id_get_request)

update billpay_payment

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
billpay_payment_id_get_request = OpenapiClient::BillpayPaymentIdGetRequest.new # BillpayPaymentIdGetRequest | The billpay_payment to update

begin
  # update billpay_payment
  result = api_instance.billpay_payment_id_patch(id, billpay_payment_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_payment_id_patch: #{e}"
end
```

#### Using the billpay_payment_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BillpayPaymentIdGet200Response>, Integer, Hash)> billpay_payment_id_patch_with_http_info(id, billpay_payment_id_get_request)

```ruby
begin
  # update billpay_payment
  data, status_code, headers = api_instance.billpay_payment_id_patch_with_http_info(id, billpay_payment_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BillpayPaymentIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_payment_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **billpay_payment_id_get_request** | [**BillpayPaymentIdGetRequest**](BillpayPaymentIdGetRequest.md) | The billpay_payment to update |  |

### Return type

[**BillpayPaymentIdGet200Response**](BillpayPaymentIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## billpay_payment_post

> <BillpayPaymentIdGet200Response> billpay_payment_post(billpay_payment_get_request)

create billpay_payment

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
billpay_payment_get_request = OpenapiClient::BillpayPaymentGetRequest.new # BillpayPaymentGetRequest | The billpay_payment to create

begin
  # create billpay_payment
  result = api_instance.billpay_payment_post(billpay_payment_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_payment_post: #{e}"
end
```

#### Using the billpay_payment_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BillpayPaymentIdGet200Response>, Integer, Hash)> billpay_payment_post_with_http_info(billpay_payment_get_request)

```ruby
begin
  # create billpay_payment
  data, status_code, headers = api_instance.billpay_payment_post_with_http_info(billpay_payment_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BillpayPaymentIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_payment_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **billpay_payment_get_request** | [**BillpayPaymentGetRequest**](BillpayPaymentGetRequest.md) | The billpay_payment to create |  |

### Return type

[**BillpayPaymentIdGet200Response**](BillpayPaymentIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## billpay_rule_get

> <Array<BillpayRuleIdGet200Response>> billpay_rule_get

index billpay_rule

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index billpay_rule
  result = api_instance.billpay_rule_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_rule_get: #{e}"
end
```

#### Using the billpay_rule_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<BillpayRuleIdGet200Response>>, Integer, Hash)> billpay_rule_get_with_http_info

```ruby
begin
  # index billpay_rule
  data, status_code, headers = api_instance.billpay_rule_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<BillpayRuleIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_rule_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;BillpayRuleIdGet200Response&gt;**](BillpayRuleIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## billpay_rule_id_get

> <BillpayRuleIdGet200Response> billpay_rule_id_get(id)

Retrieve a Rule

A Rule represents a template for a recurring bill payment. Each Rule contains all the parameters necessary for creating a Payment plus some additional parameters to control the recurring schedule. The bill pay service periodically runs each rule and determines if a new payment needs to be made; if so, the payment is created and will subsequently appear in calls to /billpay/payment.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # Retrieve a Rule
  result = api_instance.billpay_rule_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_rule_id_get: #{e}"
end
```

#### Using the billpay_rule_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BillpayRuleIdGet200Response>, Integer, Hash)> billpay_rule_id_get_with_http_info(id)

```ruby
begin
  # Retrieve a Rule
  data, status_code, headers = api_instance.billpay_rule_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BillpayRuleIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_rule_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**BillpayRuleIdGet200Response**](BillpayRuleIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## billpay_rule_id_patch

> <BillpayRuleIdGet200Response> billpay_rule_id_patch(id, billpay_rule_id_get_request)

Update a Rule

Updates the specified Bill Payment Rule by setting the values of the passed parameters. Any parameters not provided will be left unchanged.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
billpay_rule_id_get_request = OpenapiClient::BillpayRuleIdGetRequest.new # BillpayRuleIdGetRequest | The billpay_rule to update

begin
  # Update a Rule
  result = api_instance.billpay_rule_id_patch(id, billpay_rule_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_rule_id_patch: #{e}"
end
```

#### Using the billpay_rule_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BillpayRuleIdGet200Response>, Integer, Hash)> billpay_rule_id_patch_with_http_info(id, billpay_rule_id_get_request)

```ruby
begin
  # Update a Rule
  data, status_code, headers = api_instance.billpay_rule_id_patch_with_http_info(id, billpay_rule_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BillpayRuleIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_rule_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **billpay_rule_id_get_request** | [**BillpayRuleIdGetRequest**](BillpayRuleIdGetRequest.md) | The billpay_rule to update |  |

### Return type

[**BillpayRuleIdGet200Response**](BillpayRuleIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## billpay_rule_post

> <BillpayRuleIdGet200Response> billpay_rule_post(billpay_rule_get_request)

create billpay_rule

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
billpay_rule_get_request = OpenapiClient::BillpayRuleGetRequest.new({amount: 'amount_example', account_id: 'account_id_example', person_id: 'person_id_example', interval: TODO, billpay_counterparty_id: 'billpay_counterparty_id_example'}) # BillpayRuleGetRequest | The billpay_rule to create

begin
  # create billpay_rule
  result = api_instance.billpay_rule_post(billpay_rule_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_rule_post: #{e}"
end
```

#### Using the billpay_rule_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BillpayRuleIdGet200Response>, Integer, Hash)> billpay_rule_post_with_http_info(billpay_rule_get_request)

```ruby
begin
  # create billpay_rule
  data, status_code, headers = api_instance.billpay_rule_post_with_http_info(billpay_rule_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BillpayRuleIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->billpay_rule_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **billpay_rule_get_request** | [**BillpayRuleGetRequest**](BillpayRuleGetRequest.md) | The billpay_rule to create |  |

### Return type

[**BillpayRuleIdGet200Response**](BillpayRuleIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## book_get

> <Array<BookGet200ResponseInner>> book_get

index book

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index book
  result = api_instance.book_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->book_get: #{e}"
end
```

#### Using the book_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<BookGet200ResponseInner>>, Integer, Hash)> book_get_with_http_info

```ruby
begin
  # index book
  data, status_code, headers = api_instance.book_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<BookGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->book_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;BookGet200ResponseInner&gt;**](BookGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## book_id_get

> <BookGet200ResponseInner> book_id_get(id)

get book

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get book
  result = api_instance.book_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->book_id_get: #{e}"
end
```

#### Using the book_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BookGet200ResponseInner>, Integer, Hash)> book_id_get_with_http_info(id)

```ruby
begin
  # get book
  data, status_code, headers = api_instance.book_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BookGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->book_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**BookGet200ResponseInner**](BookGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## book_id_patch

> <BookGet200ResponseInner> book_id_patch(id, book_id_get_request)

update book

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
book_id_get_request = OpenapiClient::BookIdGetRequest.new # BookIdGetRequest | The book to update

begin
  # update book
  result = api_instance.book_id_patch(id, book_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->book_id_patch: #{e}"
end
```

#### Using the book_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BookGet200ResponseInner>, Integer, Hash)> book_id_patch_with_http_info(id, book_id_get_request)

```ruby
begin
  # update book
  data, status_code, headers = api_instance.book_id_patch_with_http_info(id, book_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BookGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->book_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **book_id_get_request** | [**BookIdGetRequest**](BookIdGetRequest.md) | The book to update |  |

### Return type

[**BookGet200ResponseInner**](BookGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## book_post

> <BookGet200ResponseInner> book_post(book_get_request)

create book

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
book_get_request = OpenapiClient::BookGetRequest.new({to_account_id: 'to_account_id_example', amount: 'amount_example', from_account_id: 'from_account_id_example'}) # BookGetRequest | The book to create

begin
  # create book
  result = api_instance.book_post(book_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->book_post: #{e}"
end
```

#### Using the book_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BookGet200ResponseInner>, Integer, Hash)> book_post_with_http_info(book_get_request)

```ruby
begin
  # create book
  data, status_code, headers = api_instance.book_post_with_http_info(book_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BookGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->book_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **book_get_request** | [**BookGetRequest**](BookGetRequest.md) | The book to create |  |

### Return type

[**BookGet200ResponseInner**](BookGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## business_id_get

> <BusinessIdGet200Response> business_id_get(id)

get business

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get business
  result = api_instance.business_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->business_id_get: #{e}"
end
```

#### Using the business_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BusinessIdGet200Response>, Integer, Hash)> business_id_get_with_http_info(id)

```ruby
begin
  # get business
  data, status_code, headers = api_instance.business_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BusinessIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->business_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**BusinessIdGet200Response**](BusinessIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## business_id_patch

> <BusinessIdGet200Response> business_id_patch(id, business_id_get_request)

update business

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
business_id_get_request = OpenapiClient::BusinessIdGetRequest.new # BusinessIdGetRequest | The business to update

begin
  # update business
  result = api_instance.business_id_patch(id, business_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->business_id_patch: #{e}"
end
```

#### Using the business_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BusinessIdGet200Response>, Integer, Hash)> business_id_patch_with_http_info(id, business_id_get_request)

```ruby
begin
  # update business
  data, status_code, headers = api_instance.business_id_patch_with_http_info(id, business_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BusinessIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->business_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **business_id_get_request** | [**BusinessIdGetRequest**](BusinessIdGetRequest.md) | The business to update |  |

### Return type

[**BusinessIdGet200Response**](BusinessIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## card_auth_loop_endpoint_get

> <Array<CardAuthLoopEndpointGet200ResponseInner>> card_auth_loop_endpoint_get

List Card Auth Loop Endpoints

Returns a list of Card Auth Loop Endpoint objects, or an empty list if none are available.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # List Card Auth Loop Endpoints
  result = api_instance.card_auth_loop_endpoint_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_auth_loop_endpoint_get: #{e}"
end
```

#### Using the card_auth_loop_endpoint_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<CardAuthLoopEndpointGet200ResponseInner>>, Integer, Hash)> card_auth_loop_endpoint_get_with_http_info

```ruby
begin
  # List Card Auth Loop Endpoints
  data, status_code, headers = api_instance.card_auth_loop_endpoint_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<CardAuthLoopEndpointGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_auth_loop_endpoint_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;CardAuthLoopEndpointGet200ResponseInner&gt;**](CardAuthLoopEndpointGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## card_auth_loop_endpoint_id_delete

> card_auth_loop_endpoint_id_delete(id)

delete card_auth_loop_endpoint

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # delete card_auth_loop_endpoint
  api_instance.card_auth_loop_endpoint_id_delete(id)
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_auth_loop_endpoint_id_delete: #{e}"
end
```

#### Using the card_auth_loop_endpoint_id_delete_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> card_auth_loop_endpoint_id_delete_with_http_info(id)

```ruby
begin
  # delete card_auth_loop_endpoint
  data, status_code, headers = api_instance.card_auth_loop_endpoint_id_delete_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_auth_loop_endpoint_id_delete_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

nil (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## card_auth_loop_endpoint_id_get

> <CardAuthLoopEndpointGet200ResponseInner> card_auth_loop_endpoint_id_get(id)

get card_auth_loop_endpoint

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get card_auth_loop_endpoint
  result = api_instance.card_auth_loop_endpoint_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_auth_loop_endpoint_id_get: #{e}"
end
```

#### Using the card_auth_loop_endpoint_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardAuthLoopEndpointGet200ResponseInner>, Integer, Hash)> card_auth_loop_endpoint_id_get_with_http_info(id)

```ruby
begin
  # get card_auth_loop_endpoint
  data, status_code, headers = api_instance.card_auth_loop_endpoint_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardAuthLoopEndpointGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_auth_loop_endpoint_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**CardAuthLoopEndpointGet200ResponseInner**](CardAuthLoopEndpointGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## card_auth_loop_endpoint_id_patch

> <CardAuthLoopEndpointGet200ResponseInner> card_auth_loop_endpoint_id_patch(id, card_auth_loop_endpoint_id_delete_request)

update card_auth_loop_endpoint

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
card_auth_loop_endpoint_id_delete_request = OpenapiClient::CardAuthLoopEndpointIdDeleteRequest.new # CardAuthLoopEndpointIdDeleteRequest | The card_auth_loop_endpoint to update

begin
  # update card_auth_loop_endpoint
  result = api_instance.card_auth_loop_endpoint_id_patch(id, card_auth_loop_endpoint_id_delete_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_auth_loop_endpoint_id_patch: #{e}"
end
```

#### Using the card_auth_loop_endpoint_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardAuthLoopEndpointGet200ResponseInner>, Integer, Hash)> card_auth_loop_endpoint_id_patch_with_http_info(id, card_auth_loop_endpoint_id_delete_request)

```ruby
begin
  # update card_auth_loop_endpoint
  data, status_code, headers = api_instance.card_auth_loop_endpoint_id_patch_with_http_info(id, card_auth_loop_endpoint_id_delete_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardAuthLoopEndpointGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_auth_loop_endpoint_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **card_auth_loop_endpoint_id_delete_request** | [**CardAuthLoopEndpointIdDeleteRequest**](CardAuthLoopEndpointIdDeleteRequest.md) | The card_auth_loop_endpoint to update |  |

### Return type

[**CardAuthLoopEndpointGet200ResponseInner**](CardAuthLoopEndpointGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## card_auth_loop_endpoint_post

> <CardAuthLoopEndpointGet200ResponseInner> card_auth_loop_endpoint_post(card_auth_loop_endpoint_get_request)

create card_auth_loop_endpoint

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
card_auth_loop_endpoint_get_request = OpenapiClient::CardAuthLoopEndpointGetRequest.new({url: TODO}) # CardAuthLoopEndpointGetRequest | The card_auth_loop_endpoint to create

begin
  # create card_auth_loop_endpoint
  result = api_instance.card_auth_loop_endpoint_post(card_auth_loop_endpoint_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_auth_loop_endpoint_post: #{e}"
end
```

#### Using the card_auth_loop_endpoint_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardAuthLoopEndpointGet200ResponseInner>, Integer, Hash)> card_auth_loop_endpoint_post_with_http_info(card_auth_loop_endpoint_get_request)

```ruby
begin
  # create card_auth_loop_endpoint
  data, status_code, headers = api_instance.card_auth_loop_endpoint_post_with_http_info(card_auth_loop_endpoint_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardAuthLoopEndpointGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_auth_loop_endpoint_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **card_auth_loop_endpoint_get_request** | [**CardAuthLoopEndpointGetRequest**](CardAuthLoopEndpointGetRequest.md) | The card_auth_loop_endpoint to create |  |

### Return type

[**CardAuthLoopEndpointGet200ResponseInner**](CardAuthLoopEndpointGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## card_card_id_digital_wallet_token_google_pay_post

> <CardCardIdDigitalWalletTokenGooglePayPost200Response> card_card_id_digital_wallet_token_google_pay_post(card_id, card_card_id_digital_wallet_token_google_pay_post_request)

create google-pay-token-request

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
card_id = 'card_id_example' # String | 
card_card_id_digital_wallet_token_google_pay_post_request = OpenapiClient::CardCardIdDigitalWalletTokenGooglePayPostRequest.new({provisioning_app_version: 'provisioning_app_version_example', device_type: TODO, card_id: 'card_id_example', device_id: 'device_id_example', wallet_account_id: 'wallet_account_id_example'}) # CardCardIdDigitalWalletTokenGooglePayPostRequest | The google-pay-token-request to create

begin
  # create google-pay-token-request
  result = api_instance.card_card_id_digital_wallet_token_google_pay_post(card_id, card_card_id_digital_wallet_token_google_pay_post_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_card_id_digital_wallet_token_google_pay_post: #{e}"
end
```

#### Using the card_card_id_digital_wallet_token_google_pay_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardCardIdDigitalWalletTokenGooglePayPost200Response>, Integer, Hash)> card_card_id_digital_wallet_token_google_pay_post_with_http_info(card_id, card_card_id_digital_wallet_token_google_pay_post_request)

```ruby
begin
  # create google-pay-token-request
  data, status_code, headers = api_instance.card_card_id_digital_wallet_token_google_pay_post_with_http_info(card_id, card_card_id_digital_wallet_token_google_pay_post_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardCardIdDigitalWalletTokenGooglePayPost200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_card_id_digital_wallet_token_google_pay_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **card_id** | **String** |  |  |
| **card_card_id_digital_wallet_token_google_pay_post_request** | [**CardCardIdDigitalWalletTokenGooglePayPostRequest**](CardCardIdDigitalWalletTokenGooglePayPostRequest.md) | The google-pay-token-request to create |  |

### Return type

[**CardCardIdDigitalWalletTokenGooglePayPost200Response**](CardCardIdDigitalWalletTokenGooglePayPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## card_charge_get

> <Array<CardChargeIdGet200Response>> card_charge_get

index card.charge

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index card.charge
  result = api_instance.card_charge_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_charge_get: #{e}"
end
```

#### Using the card_charge_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<CardChargeIdGet200Response>>, Integer, Hash)> card_charge_get_with_http_info

```ruby
begin
  # index card.charge
  data, status_code, headers = api_instance.card_charge_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<CardChargeIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_charge_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;CardChargeIdGet200Response&gt;**](CardChargeIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## card_charge_id_get

> <CardChargeIdGet200Response> card_charge_id_get(id)

get card.charge

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get card.charge
  result = api_instance.card_charge_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_charge_id_get: #{e}"
end
```

#### Using the card_charge_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardChargeIdGet200Response>, Integer, Hash)> card_charge_id_get_with_http_info(id)

```ruby
begin
  # get card.charge
  data, status_code, headers = api_instance.card_charge_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardChargeIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_charge_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**CardChargeIdGet200Response**](CardChargeIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## card_charge_post

> <CardChargeIdGet200Response> card_charge_post(card_charge_get_request)

create card.charge

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
card_charge_get_request = OpenapiClient::CardChargeGetRequest.new({amount: 'amount_example', account_id: 'account_id_example'}) # CardChargeGetRequest | The card.charge to create

begin
  # create card.charge
  result = api_instance.card_charge_post(card_charge_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_charge_post: #{e}"
end
```

#### Using the card_charge_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardChargeIdGet200Response>, Integer, Hash)> card_charge_post_with_http_info(card_charge_get_request)

```ruby
begin
  # create card.charge
  data, status_code, headers = api_instance.card_charge_post_with_http_info(card_charge_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardChargeIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_charge_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **card_charge_get_request** | [**CardChargeGetRequest**](CardChargeGetRequest.md) | The card.charge to create |  |

### Return type

[**CardChargeIdGet200Response**](CardChargeIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## card_event_get

> <Array<CardEventIdGet200Response>> card_event_get

List Card Events

Returns a list of card event objects, filterable by card_id, or an empty list if none are available.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # List Card Events
  result = api_instance.card_event_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_event_get: #{e}"
end
```

#### Using the card_event_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<CardEventIdGet200Response>>, Integer, Hash)> card_event_get_with_http_info

```ruby
begin
  # List Card Events
  data, status_code, headers = api_instance.card_event_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<CardEventIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_event_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;CardEventIdGet200Response&gt;**](CardEventIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## card_event_id_get

> <CardEventIdGet200Response> card_event_id_get(id)

Retrieve a Card Event

Retrieves the details of an existing card event. Pass a unique ID from the Card Event list.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # Retrieve a Card Event
  result = api_instance.card_event_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_event_id_get: #{e}"
end
```

#### Using the card_event_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardEventIdGet200Response>, Integer, Hash)> card_event_id_get_with_http_info(id)

```ruby
begin
  # Retrieve a Card Event
  data, status_code, headers = api_instance.card_event_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardEventIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_event_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**CardEventIdGet200Response**](CardEventIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## card_get

> <Array<CardGet200ResponseInner>> card_get

index card

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index card
  result = api_instance.card_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_get: #{e}"
end
```

#### Using the card_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<CardGet200ResponseInner>>, Integer, Hash)> card_get_with_http_info

```ruby
begin
  # index card
  data, status_code, headers = api_instance.card_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<CardGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;CardGet200ResponseInner&gt;**](CardGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## card_id_get

> <CardGet200ResponseInner> card_id_get(id)

get card

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get card
  result = api_instance.card_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_id_get: #{e}"
end
```

#### Using the card_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardGet200ResponseInner>, Integer, Hash)> card_id_get_with_http_info(id)

```ruby
begin
  # get card
  data, status_code, headers = api_instance.card_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**CardGet200ResponseInner**](CardGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## card_id_patch

> <CardGet200ResponseInner> card_id_patch(id, card_id_get_request)

update card

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
card_id_get_request = OpenapiClient::CardIdGetRequest.new # CardIdGetRequest | The card to update

begin
  # update card
  result = api_instance.card_id_patch(id, card_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_id_patch: #{e}"
end
```

#### Using the card_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardGet200ResponseInner>, Integer, Hash)> card_id_patch_with_http_info(id, card_id_get_request)

```ruby
begin
  # update card
  data, status_code, headers = api_instance.card_id_patch_with_http_info(id, card_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **card_id_get_request** | [**CardIdGetRequest**](CardIdGetRequest.md) | The card to update |  |

### Return type

[**CardGet200ResponseInner**](CardGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## card_id_token_get

> <CardIdTokenGet200Response> card_id_token_get(id)

get token

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get token
  result = api_instance.card_id_token_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_id_token_get: #{e}"
end
```

#### Using the card_id_token_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardIdTokenGet200Response>, Integer, Hash)> card_id_token_get_with_http_info(id)

```ruby
begin
  # get token
  data, status_code, headers = api_instance.card_id_token_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardIdTokenGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_id_token_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**CardIdTokenGet200Response**](CardIdTokenGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## card_post

> <CardGet200ResponseInner> card_post(card_get_request)

create card

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
card_get_request = OpenapiClient::CardGetRequest.new({account_id: 'account_id_example', person_id: 'person_id_example', card_product_id: 'card_product_id_example'}) # CardGetRequest | The card to create

begin
  # create card
  result = api_instance.card_post(card_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_post: #{e}"
end
```

#### Using the card_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardGet200ResponseInner>, Integer, Hash)> card_post_with_http_info(card_get_request)

```ruby
begin
  # create card
  data, status_code, headers = api_instance.card_post_with_http_info(card_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->card_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **card_get_request** | [**CardGetRequest**](CardGetRequest.md) | The card to create |  |

### Return type

[**CardGet200ResponseInner**](CardGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## cardproduct_get

> <Array<CardproductIdGet200Response>> cardproduct_get

index cardproduct

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index cardproduct
  result = api_instance.cardproduct_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->cardproduct_get: #{e}"
end
```

#### Using the cardproduct_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<CardproductIdGet200Response>>, Integer, Hash)> cardproduct_get_with_http_info

```ruby
begin
  # index cardproduct
  data, status_code, headers = api_instance.cardproduct_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<CardproductIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->cardproduct_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;CardproductIdGet200Response&gt;**](CardproductIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## cardproduct_id_get

> <CardproductIdGet200Response> cardproduct_id_get(id)

Card Product

The Card Product resource represents the program settings, customizations, and behavior of the cards you're issuing. In general, these resources will be configured by Treasury Prime when you set up your card program. This resource is exposed in the API for your reference.

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # Card Product
  result = api_instance.cardproduct_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->cardproduct_id_get: #{e}"
end
```

#### Using the cardproduct_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardproductIdGet200Response>, Integer, Hash)> cardproduct_id_get_with_http_info(id)

```ruby
begin
  # Card Product
  data, status_code, headers = api_instance.cardproduct_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardproductIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->cardproduct_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**CardproductIdGet200Response**](CardproductIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## cardproduct_id_patch

> <CardproductIdGet200Response> cardproduct_id_patch(id, cardproduct_id_get_request)

update cardproduct

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
cardproduct_id_get_request = OpenapiClient::CardproductIdGetRequest.new # CardproductIdGetRequest | The cardproduct to update

begin
  # update cardproduct
  result = api_instance.cardproduct_id_patch(id, cardproduct_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->cardproduct_id_patch: #{e}"
end
```

#### Using the cardproduct_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CardproductIdGet200Response>, Integer, Hash)> cardproduct_id_patch_with_http_info(id, cardproduct_id_get_request)

```ruby
begin
  # update cardproduct
  data, status_code, headers = api_instance.cardproduct_id_patch_with_http_info(id, cardproduct_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CardproductIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->cardproduct_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **cardproduct_id_get_request** | [**CardproductIdGetRequest**](CardproductIdGetRequest.md) | The cardproduct to update |  |

### Return type

[**CardproductIdGet200Response**](CardproductIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## check_deposit_get

> <Array<CheckDepositGet200ResponseInner>> check_deposit_get

index check_deposit

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index check_deposit
  result = api_instance.check_deposit_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_deposit_get: #{e}"
end
```

#### Using the check_deposit_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<CheckDepositGet200ResponseInner>>, Integer, Hash)> check_deposit_get_with_http_info

```ruby
begin
  # index check_deposit
  data, status_code, headers = api_instance.check_deposit_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<CheckDepositGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_deposit_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;CheckDepositGet200ResponseInner&gt;**](CheckDepositGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## check_deposit_id_get

> <CheckDepositGet200ResponseInner> check_deposit_id_get(id)

get check_deposit

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get check_deposit
  result = api_instance.check_deposit_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_deposit_id_get: #{e}"
end
```

#### Using the check_deposit_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CheckDepositGet200ResponseInner>, Integer, Hash)> check_deposit_id_get_with_http_info(id)

```ruby
begin
  # get check_deposit
  data, status_code, headers = api_instance.check_deposit_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CheckDepositGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_deposit_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**CheckDepositGet200ResponseInner**](CheckDepositGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## check_deposit_person_get

> <Array<CheckDepositPersonIdGet200Response>> check_deposit_person_get

index check_deposit_person

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index check_deposit_person
  result = api_instance.check_deposit_person_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_deposit_person_get: #{e}"
end
```

#### Using the check_deposit_person_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<CheckDepositPersonIdGet200Response>>, Integer, Hash)> check_deposit_person_get_with_http_info

```ruby
begin
  # index check_deposit_person
  data, status_code, headers = api_instance.check_deposit_person_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<CheckDepositPersonIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_deposit_person_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;CheckDepositPersonIdGet200Response&gt;**](CheckDepositPersonIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## check_deposit_person_id_get

> <CheckDepositPersonIdGet200Response> check_deposit_person_id_get(id)

get check_deposit_person

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get check_deposit_person
  result = api_instance.check_deposit_person_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_deposit_person_id_get: #{e}"
end
```

#### Using the check_deposit_person_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CheckDepositPersonIdGet200Response>, Integer, Hash)> check_deposit_person_id_get_with_http_info(id)

```ruby
begin
  # get check_deposit_person
  data, status_code, headers = api_instance.check_deposit_person_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CheckDepositPersonIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_deposit_person_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**CheckDepositPersonIdGet200Response**](CheckDepositPersonIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## check_deposit_person_post

> <CheckDepositPersonIdGet200Response> check_deposit_person_post(check_deposit_person_get_request)

create check_deposit_person

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
check_deposit_person_get_request = OpenapiClient::CheckDepositPersonGetRequest.new({account_id: 'account_id_example'}) # CheckDepositPersonGetRequest | The check_deposit_person to create

begin
  # create check_deposit_person
  result = api_instance.check_deposit_person_post(check_deposit_person_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_deposit_person_post: #{e}"
end
```

#### Using the check_deposit_person_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CheckDepositPersonIdGet200Response>, Integer, Hash)> check_deposit_person_post_with_http_info(check_deposit_person_get_request)

```ruby
begin
  # create check_deposit_person
  data, status_code, headers = api_instance.check_deposit_person_post_with_http_info(check_deposit_person_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CheckDepositPersonIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_deposit_person_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **check_deposit_person_get_request** | [**CheckDepositPersonGetRequest**](CheckDepositPersonGetRequest.md) | The check_deposit_person to create |  |

### Return type

[**CheckDepositPersonIdGet200Response**](CheckDepositPersonIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## check_deposit_post

> <CheckDepositGet200ResponseInner> check_deposit_post(check_deposit_get_request)

create check_deposit

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
check_deposit_get_request = OpenapiClient::CheckDepositGetRequest.new({back_image_file_id: 'back_image_file_id_example', amount: 'amount_example', account_id: 'account_id_example', person_id: 'person_id_example', device: TODO, front_image_file_id: 'front_image_file_id_example'}) # CheckDepositGetRequest | The check_deposit to create

begin
  # create check_deposit
  result = api_instance.check_deposit_post(check_deposit_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_deposit_post: #{e}"
end
```

#### Using the check_deposit_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CheckDepositGet200ResponseInner>, Integer, Hash)> check_deposit_post_with_http_info(check_deposit_get_request)

```ruby
begin
  # create check_deposit
  data, status_code, headers = api_instance.check_deposit_post_with_http_info(check_deposit_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CheckDepositGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_deposit_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **check_deposit_get_request** | [**CheckDepositGetRequest**](CheckDepositGetRequest.md) | The check_deposit to create |  |

### Return type

[**CheckDepositGet200ResponseInner**](CheckDepositGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## check_get

> <Array<CheckGet200ResponseInner>> check_get

index check

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index check
  result = api_instance.check_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_get: #{e}"
end
```

#### Using the check_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<CheckGet200ResponseInner>>, Integer, Hash)> check_get_with_http_info

```ruby
begin
  # index check
  data, status_code, headers = api_instance.check_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<CheckGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;CheckGet200ResponseInner&gt;**](CheckGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## check_id_get

> <CheckGet200ResponseInner> check_id_get(id)

get check

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get check
  result = api_instance.check_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_id_get: #{e}"
end
```

#### Using the check_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CheckGet200ResponseInner>, Integer, Hash)> check_id_get_with_http_info(id)

```ruby
begin
  # get check
  data, status_code, headers = api_instance.check_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CheckGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**CheckGet200ResponseInner**](CheckGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## check_image_get

> <Array<CheckImageGet200ResponseInner>> check_image_get

index check_image

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index check_image
  result = api_instance.check_image_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_image_get: #{e}"
end
```

#### Using the check_image_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<CheckImageGet200ResponseInner>>, Integer, Hash)> check_image_get_with_http_info

```ruby
begin
  # index check_image
  data, status_code, headers = api_instance.check_image_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<CheckImageGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_image_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;CheckImageGet200ResponseInner&gt;**](CheckImageGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## check_image_id_get

> <CheckImageGet200ResponseInner> check_image_id_get(id)

get check_image

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get check_image
  result = api_instance.check_image_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_image_id_get: #{e}"
end
```

#### Using the check_image_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CheckImageGet200ResponseInner>, Integer, Hash)> check_image_id_get_with_http_info(id)

```ruby
begin
  # get check_image
  data, status_code, headers = api_instance.check_image_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CheckImageGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_image_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**CheckImageGet200ResponseInner**](CheckImageGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## check_post

> <CheckGet200ResponseInner> check_post(check_get_request)

create check

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
check_get_request = OpenapiClient::CheckGetRequest.new({amount: 'amount_example', account_id: 'account_id_example', recipient: TODO}) # CheckGetRequest | The check to create

begin
  # create check
  result = api_instance.check_post(check_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_post: #{e}"
end
```

#### Using the check_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CheckGet200ResponseInner>, Integer, Hash)> check_post_with_http_info(check_get_request)

```ruby
begin
  # create check
  data, status_code, headers = api_instance.check_post_with_http_info(check_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CheckGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->check_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **check_get_request** | [**CheckGetRequest**](CheckGetRequest.md) | The check to create |  |

### Return type

[**CheckGet200ResponseInner**](CheckGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## counterparty_get

> <Array<CounterpartyIdGet200Response>> counterparty_get

index counterparty

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index counterparty
  result = api_instance.counterparty_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->counterparty_get: #{e}"
end
```

#### Using the counterparty_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<CounterpartyIdGet200Response>>, Integer, Hash)> counterparty_get_with_http_info

```ruby
begin
  # index counterparty
  data, status_code, headers = api_instance.counterparty_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<CounterpartyIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->counterparty_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;CounterpartyIdGet200Response&gt;**](CounterpartyIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## counterparty_id_get

> <CounterpartyIdGet200Response> counterparty_id_get(id)

get counterparty

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get counterparty
  result = api_instance.counterparty_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->counterparty_id_get: #{e}"
end
```

#### Using the counterparty_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CounterpartyIdGet200Response>, Integer, Hash)> counterparty_id_get_with_http_info(id)

```ruby
begin
  # get counterparty
  data, status_code, headers = api_instance.counterparty_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CounterpartyIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->counterparty_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**CounterpartyIdGet200Response**](CounterpartyIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## counterparty_id_patch

> <CounterpartyIdGet200Response> counterparty_id_patch(id, counterparty_id_get_request)

update counterparty

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
counterparty_id_get_request = OpenapiClient::CounterpartyIdGetRequest.new # CounterpartyIdGetRequest | The counterparty to update

begin
  # update counterparty
  result = api_instance.counterparty_id_patch(id, counterparty_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->counterparty_id_patch: #{e}"
end
```

#### Using the counterparty_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CounterpartyIdGet200Response>, Integer, Hash)> counterparty_id_patch_with_http_info(id, counterparty_id_get_request)

```ruby
begin
  # update counterparty
  data, status_code, headers = api_instance.counterparty_id_patch_with_http_info(id, counterparty_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CounterpartyIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->counterparty_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **counterparty_id_get_request** | [**CounterpartyIdGetRequest**](CounterpartyIdGetRequest.md) | The counterparty to update |  |

### Return type

[**CounterpartyIdGet200Response**](CounterpartyIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## counterparty_post

> <CounterpartyIdGet200Response> counterparty_post(counterparty_get_request)

create counterparty

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
counterparty_get_request = OpenapiClient::CounterpartyGetRequest.new({name_on_account: TODO}) # CounterpartyGetRequest | The counterparty to create

begin
  # create counterparty
  result = api_instance.counterparty_post(counterparty_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->counterparty_post: #{e}"
end
```

#### Using the counterparty_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CounterpartyIdGet200Response>, Integer, Hash)> counterparty_post_with_http_info(counterparty_get_request)

```ruby
begin
  # create counterparty
  data, status_code, headers = api_instance.counterparty_post_with_http_info(counterparty_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CounterpartyIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->counterparty_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **counterparty_get_request** | [**CounterpartyGetRequest**](CounterpartyGetRequest.md) | The counterparty to create |  |

### Return type

[**CounterpartyIdGet200Response**](CounterpartyIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## document_get

> <Array<DocumentGet200ResponseInner>> document_get

index document

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index document
  result = api_instance.document_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->document_get: #{e}"
end
```

#### Using the document_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<DocumentGet200ResponseInner>>, Integer, Hash)> document_get_with_http_info

```ruby
begin
  # index document
  data, status_code, headers = api_instance.document_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<DocumentGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->document_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;DocumentGet200ResponseInner&gt;**](DocumentGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## document_id_get

> <DocumentGet200ResponseInner> document_id_get(id)

get document

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get document
  result = api_instance.document_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->document_id_get: #{e}"
end
```

#### Using the document_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<DocumentGet200ResponseInner>, Integer, Hash)> document_id_get_with_http_info(id)

```ruby
begin
  # get document
  data, status_code, headers = api_instance.document_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <DocumentGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->document_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**DocumentGet200ResponseInner**](DocumentGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## document_id_patch

> <DocumentGet200ResponseInner> document_id_patch(id, document_id_get_request)

update document

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
document_id_get_request = OpenapiClient::DocumentIdGetRequest.new # DocumentIdGetRequest | The document to update

begin
  # update document
  result = api_instance.document_id_patch(id, document_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->document_id_patch: #{e}"
end
```

#### Using the document_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<DocumentGet200ResponseInner>, Integer, Hash)> document_id_patch_with_http_info(id, document_id_get_request)

```ruby
begin
  # update document
  data, status_code, headers = api_instance.document_id_patch_with_http_info(id, document_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <DocumentGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->document_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **document_id_get_request** | [**DocumentIdGetRequest**](DocumentIdGetRequest.md) | The document to update |  |

### Return type

[**DocumentGet200ResponseInner**](DocumentGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## document_post

> <DocumentGet200ResponseInner> document_post(document_get_request)

create document

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
document_get_request = OpenapiClient::DocumentGetRequest.new({type: TODO}) # DocumentGetRequest | The document to create

begin
  # create document
  result = api_instance.document_post(document_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->document_post: #{e}"
end
```

#### Using the document_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<DocumentGet200ResponseInner>, Integer, Hash)> document_post_with_http_info(document_get_request)

```ruby
begin
  # create document
  data, status_code, headers = api_instance.document_post_with_http_info(document_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <DocumentGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->document_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **document_get_request** | [**DocumentGetRequest**](DocumentGetRequest.md) | The document to create |  |

### Return type

[**DocumentGet200ResponseInner**](DocumentGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## file_id_content_get

> <FileIdContentGet200Response> file_id_content_get(id)

get file

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get file
  result = api_instance.file_id_content_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->file_id_content_get: #{e}"
end
```

#### Using the file_id_content_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<FileIdContentGet200Response>, Integer, Hash)> file_id_content_get_with_http_info(id)

```ruby
begin
  # get file
  data, status_code, headers = api_instance.file_id_content_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <FileIdContentGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->file_id_content_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**FileIdContentGet200Response**](FileIdContentGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## file_id_get

> <FileIdContentGet200Response> file_id_get(id)

get file

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get file
  result = api_instance.file_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->file_id_get: #{e}"
end
```

#### Using the file_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<FileIdContentGet200Response>, Integer, Hash)> file_id_get_with_http_info(id)

```ruby
begin
  # get file
  data, status_code, headers = api_instance.file_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <FileIdContentGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->file_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**FileIdContentGet200Response**](FileIdContentGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## person_id_card_card_id_get

> <PersonIdCardGet200Response> person_id_card_card_id_get(id, card_id)

get person.card.index

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
card_id = 'card_id_example' # String | 

begin
  # get person.card.index
  result = api_instance.person_id_card_card_id_get(id, card_id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->person_id_card_card_id_get: #{e}"
end
```

#### Using the person_id_card_card_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<PersonIdCardGet200Response>, Integer, Hash)> person_id_card_card_id_get_with_http_info(id, card_id)

```ruby
begin
  # get person.card.index
  data, status_code, headers = api_instance.person_id_card_card_id_get_with_http_info(id, card_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <PersonIdCardGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->person_id_card_card_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **card_id** | **String** |  |  |

### Return type

[**PersonIdCardGet200Response**](PersonIdCardGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## person_id_card_get

> <PersonIdCardGet200Response> person_id_card_get(id)

get person.card.index

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get person.card.index
  result = api_instance.person_id_card_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->person_id_card_get: #{e}"
end
```

#### Using the person_id_card_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<PersonIdCardGet200Response>, Integer, Hash)> person_id_card_get_with_http_info(id)

```ruby
begin
  # get person.card.index
  data, status_code, headers = api_instance.person_id_card_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <PersonIdCardGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->person_id_card_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**PersonIdCardGet200Response**](PersonIdCardGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## person_id_card_post

> <PersonIdCardGet200Response1> person_id_card_post(id, person_id_card_get_request)

update person.card.in

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
person_id_card_get_request = OpenapiClient::PersonIdCardGetRequest.new # PersonIdCardGetRequest | The person.card.in to update

begin
  # update person.card.in
  result = api_instance.person_id_card_post(id, person_id_card_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->person_id_card_post: #{e}"
end
```

#### Using the person_id_card_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<PersonIdCardGet200Response1>, Integer, Hash)> person_id_card_post_with_http_info(id, person_id_card_get_request)

```ruby
begin
  # update person.card.in
  data, status_code, headers = api_instance.person_id_card_post_with_http_info(id, person_id_card_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <PersonIdCardGet200Response1>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->person_id_card_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **person_id_card_get_request** | [**PersonIdCardGetRequest**](PersonIdCardGetRequest.md) | The person.card.in to update |  |

### Return type

[**PersonIdCardGet200Response1**](PersonIdCardGet200Response1.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## person_id_get

> <PersonIdGet200Response> person_id_get(id)

get person

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get person
  result = api_instance.person_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->person_id_get: #{e}"
end
```

#### Using the person_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<PersonIdGet200Response>, Integer, Hash)> person_id_get_with_http_info(id)

```ruby
begin
  # get person
  data, status_code, headers = api_instance.person_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <PersonIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->person_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**PersonIdGet200Response**](PersonIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## person_id_patch

> <PersonIdGet200Response> person_id_patch(id, person_id_get_request)

update person

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
person_id_get_request = OpenapiClient::PersonIdGetRequest.new # PersonIdGetRequest | The person to update

begin
  # update person
  result = api_instance.person_id_patch(id, person_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->person_id_patch: #{e}"
end
```

#### Using the person_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<PersonIdGet200Response>, Integer, Hash)> person_id_patch_with_http_info(id, person_id_get_request)

```ruby
begin
  # update person
  data, status_code, headers = api_instance.person_id_patch_with_http_info(id, person_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <PersonIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->person_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **person_id_get_request** | [**PersonIdGetRequest**](PersonIdGetRequest.md) | The person to update |  |

### Return type

[**PersonIdGet200Response**](PersonIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## plaid_exchange_users_auth_token_post

> <PlaidExchangeUsersAuthTokenPost200Response> plaid_exchange_users_auth_token_post

get plaid-exchange.auth

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # get plaid-exchange.auth
  result = api_instance.plaid_exchange_users_auth_token_post
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->plaid_exchange_users_auth_token_post: #{e}"
end
```

#### Using the plaid_exchange_users_auth_token_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<PlaidExchangeUsersAuthTokenPost200Response>, Integer, Hash)> plaid_exchange_users_auth_token_post_with_http_info

```ruby
begin
  # get plaid-exchange.auth
  data, status_code, headers = api_instance.plaid_exchange_users_auth_token_post_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <PlaidExchangeUsersAuthTokenPost200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->plaid_exchange_users_auth_token_post_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**PlaidExchangeUsersAuthTokenPost200Response**](PlaidExchangeUsersAuthTokenPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## plaid_exchange_users_user_id2fa_post

> <PlaidExchangeUsersUserId2faPost200Response> plaid_exchange_users_user_id2fa_post(user_id)

get plaid-exchange.2fa

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
user_id = 'user_id_example' # String | 

begin
  # get plaid-exchange.2fa
  result = api_instance.plaid_exchange_users_user_id2fa_post(user_id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->plaid_exchange_users_user_id2fa_post: #{e}"
end
```

#### Using the plaid_exchange_users_user_id2fa_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<PlaidExchangeUsersUserId2faPost200Response>, Integer, Hash)> plaid_exchange_users_user_id2fa_post_with_http_info(user_id)

```ruby
begin
  # get plaid-exchange.2fa
  data, status_code, headers = api_instance.plaid_exchange_users_user_id2fa_post_with_http_info(user_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <PlaidExchangeUsersUserId2faPost200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->plaid_exchange_users_user_id2fa_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_id** | **String** |  |  |

### Return type

[**PlaidExchangeUsersUserId2faPost200Response**](PlaidExchangeUsersUserId2faPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## plaid_exchange_users_user_id_get

> <PlaidExchangeUsersUserIdGet200Response> plaid_exchange_users_user_id_get(user_id)

get plaid-exchange.identity

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
user_id = 'user_id_example' # String | 

begin
  # get plaid-exchange.identity
  result = api_instance.plaid_exchange_users_user_id_get(user_id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->plaid_exchange_users_user_id_get: #{e}"
end
```

#### Using the plaid_exchange_users_user_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<PlaidExchangeUsersUserIdGet200Response>, Integer, Hash)> plaid_exchange_users_user_id_get_with_http_info(user_id)

```ruby
begin
  # get plaid-exchange.identity
  data, status_code, headers = api_instance.plaid_exchange_users_user_id_get_with_http_info(user_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <PlaidExchangeUsersUserIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->plaid_exchange_users_user_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_id** | **String** |  |  |

### Return type

[**PlaidExchangeUsersUserIdGet200Response**](PlaidExchangeUsersUserIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## plaid_exchange_users_user_id_transactions_get

> <PlaidExchangeUsersUserIdTransactionsGet200Response> plaid_exchange_users_user_id_transactions_get(user_id)

get plaid-exchange.transactions

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
user_id = 'user_id_example' # String | 

begin
  # get plaid-exchange.transactions
  result = api_instance.plaid_exchange_users_user_id_transactions_get(user_id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->plaid_exchange_users_user_id_transactions_get: #{e}"
end
```

#### Using the plaid_exchange_users_user_id_transactions_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<PlaidExchangeUsersUserIdTransactionsGet200Response>, Integer, Hash)> plaid_exchange_users_user_id_transactions_get_with_http_info(user_id)

```ruby
begin
  # get plaid-exchange.transactions
  data, status_code, headers = api_instance.plaid_exchange_users_user_id_transactions_get_with_http_info(user_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <PlaidExchangeUsersUserIdTransactionsGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->plaid_exchange_users_user_id_transactions_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_id** | **String** |  |  |

### Return type

[**PlaidExchangeUsersUserIdTransactionsGet200Response**](PlaidExchangeUsersUserIdTransactionsGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reserve_get

> <Array<ReserveGet200ResponseInner>> reserve_get

index reserve

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index reserve
  result = api_instance.reserve_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->reserve_get: #{e}"
end
```

#### Using the reserve_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<ReserveGet200ResponseInner>>, Integer, Hash)> reserve_get_with_http_info

```ruby
begin
  # index reserve
  data, status_code, headers = api_instance.reserve_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<ReserveGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->reserve_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;ReserveGet200ResponseInner&gt;**](ReserveGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reserve_id_delete

> reserve_id_delete(id)

delete reserve

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # delete reserve
  api_instance.reserve_id_delete(id)
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->reserve_id_delete: #{e}"
end
```

#### Using the reserve_id_delete_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> reserve_id_delete_with_http_info(id)

```ruby
begin
  # delete reserve
  data, status_code, headers = api_instance.reserve_id_delete_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->reserve_id_delete_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

nil (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## reserve_id_get

> <ReserveGet200ResponseInner> reserve_id_get(id)

get reserve

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get reserve
  result = api_instance.reserve_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->reserve_id_get: #{e}"
end
```

#### Using the reserve_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ReserveGet200ResponseInner>, Integer, Hash)> reserve_id_get_with_http_info(id)

```ruby
begin
  # get reserve
  data, status_code, headers = api_instance.reserve_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ReserveGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->reserve_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**ReserveGet200ResponseInner**](ReserveGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reserve_id_patch

> <ReserveGet200ResponseInner> reserve_id_patch(id, reserve_id_delete_request)

update reserve

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
reserve_id_delete_request = OpenapiClient::ReserveIdDeleteRequest.new # ReserveIdDeleteRequest | The reserve to update

begin
  # update reserve
  result = api_instance.reserve_id_patch(id, reserve_id_delete_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->reserve_id_patch: #{e}"
end
```

#### Using the reserve_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ReserveGet200ResponseInner>, Integer, Hash)> reserve_id_patch_with_http_info(id, reserve_id_delete_request)

```ruby
begin
  # update reserve
  data, status_code, headers = api_instance.reserve_id_patch_with_http_info(id, reserve_id_delete_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ReserveGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->reserve_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **reserve_id_delete_request** | [**ReserveIdDeleteRequest**](ReserveIdDeleteRequest.md) | The reserve to update |  |

### Return type

[**ReserveGet200ResponseInner**](ReserveGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## reserve_post

> <ReserveGet200ResponseInner> reserve_post(reserve_get_request)

create reserve

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
reserve_get_request = OpenapiClient::ReserveGetRequest.new({amount: 'amount_example', account_id: 'account_id_example', reserve_account_id: 'reserve_account_id_example', upper_limit: 'upper_limit_example'}) # ReserveGetRequest | To mark an account as having reserve protection, create a reserve object.

begin
  # create reserve
  result = api_instance.reserve_post(reserve_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->reserve_post: #{e}"
end
```

#### Using the reserve_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ReserveGet200ResponseInner>, Integer, Hash)> reserve_post_with_http_info(reserve_get_request)

```ruby
begin
  # create reserve
  data, status_code, headers = api_instance.reserve_post_with_http_info(reserve_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ReserveGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->reserve_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **reserve_get_request** | [**ReserveGetRequest**](ReserveGetRequest.md) | To mark an account as having reserve protection, create a reserve object. |  |

### Return type

[**ReserveGet200ResponseInner**](ReserveGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## search_get

> <Array<SearchGet200ResponseInner>> search_get

index search

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index search
  result = api_instance.search_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->search_get: #{e}"
end
```

#### Using the search_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<SearchGet200ResponseInner>>, Integer, Hash)> search_get_with_http_info

```ruby
begin
  # index search
  data, status_code, headers = api_instance.search_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<SearchGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->search_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;SearchGet200ResponseInner&gt;**](SearchGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## setting_get

> <Array<SettingGet200ResponseInner>> setting_get

index setting

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index setting
  result = api_instance.setting_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->setting_get: #{e}"
end
```

#### Using the setting_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<SettingGet200ResponseInner>>, Integer, Hash)> setting_get_with_http_info

```ruby
begin
  # index setting
  data, status_code, headers = api_instance.setting_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<SettingGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->setting_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;SettingGet200ResponseInner&gt;**](SettingGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## setting_patch

> <SettingGet200ResponseInner> setting_patch(setting_get_request)

update setting

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
setting_get_request = OpenapiClient::SettingGetRequest.new # SettingGetRequest | The setting to update

begin
  # update setting
  result = api_instance.setting_patch(setting_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->setting_patch: #{e}"
end
```

#### Using the setting_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SettingGet200ResponseInner>, Integer, Hash)> setting_patch_with_http_info(setting_get_request)

```ruby
begin
  # update setting
  data, status_code, headers = api_instance.setting_patch_with_http_info(setting_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SettingGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->setting_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **setting_get_request** | [**SettingGetRequest**](SettingGetRequest.md) | The setting to update |  |

### Return type

[**SettingGet200ResponseInner**](SettingGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## simulation_post

> <SimulationPost200Response> simulation_post(simulation_post_request)

create simulation

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
simulation_post_request = OpenapiClient::SimulationPostRequest.new({type: 'type_example', simulation: 3.56}) # SimulationPostRequest | The simulation to create

begin
  # create simulation
  result = api_instance.simulation_post(simulation_post_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->simulation_post: #{e}"
end
```

#### Using the simulation_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SimulationPost200Response>, Integer, Hash)> simulation_post_with_http_info(simulation_post_request)

```ruby
begin
  # create simulation
  data, status_code, headers = api_instance.simulation_post_with_http_info(simulation_post_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SimulationPost200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->simulation_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **simulation_post_request** | [**SimulationPostRequest**](SimulationPostRequest.md) | The simulation to create |  |

### Return type

[**SimulationPost200Response**](SimulationPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## survey_get

> <Array<SurveyGet200ResponseInner>> survey_get

index survey

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index survey
  result = api_instance.survey_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->survey_get: #{e}"
end
```

#### Using the survey_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<SurveyGet200ResponseInner>>, Integer, Hash)> survey_get_with_http_info

```ruby
begin
  # index survey
  data, status_code, headers = api_instance.survey_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<SurveyGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->survey_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;SurveyGet200ResponseInner&gt;**](SurveyGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## survey_id_get

> <SurveyGet200ResponseInner> survey_id_get(id)

get survey

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get survey
  result = api_instance.survey_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->survey_id_get: #{e}"
end
```

#### Using the survey_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SurveyGet200ResponseInner>, Integer, Hash)> survey_id_get_with_http_info(id)

```ruby
begin
  # get survey
  data, status_code, headers = api_instance.survey_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SurveyGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->survey_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**SurveyGet200ResponseInner**](SurveyGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## third_party_ach_get

> <Array<ThirdPartyAchGet200ResponseInner>> third_party_ach_get

index third_party_ach

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index third_party_ach
  result = api_instance.third_party_ach_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->third_party_ach_get: #{e}"
end
```

#### Using the third_party_ach_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<ThirdPartyAchGet200ResponseInner>>, Integer, Hash)> third_party_ach_get_with_http_info

```ruby
begin
  # index third_party_ach
  data, status_code, headers = api_instance.third_party_ach_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<ThirdPartyAchGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->third_party_ach_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;ThirdPartyAchGet200ResponseInner&gt;**](ThirdPartyAchGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## third_party_ach_id_get

> <ThirdPartyAchGet200ResponseInner> third_party_ach_id_get(id)

get third_party_ach

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get third_party_ach
  result = api_instance.third_party_ach_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->third_party_ach_id_get: #{e}"
end
```

#### Using the third_party_ach_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ThirdPartyAchGet200ResponseInner>, Integer, Hash)> third_party_ach_id_get_with_http_info(id)

```ruby
begin
  # get third_party_ach
  data, status_code, headers = api_instance.third_party_ach_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ThirdPartyAchGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->third_party_ach_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**ThirdPartyAchGet200ResponseInner**](ThirdPartyAchGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## third_party_ach_id_patch

> <ThirdPartyAchGet200ResponseInner> third_party_ach_id_patch(id, third_party_ach_id_get_request)

update third_party_ach

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
third_party_ach_id_get_request = OpenapiClient::ThirdPartyAchIdGetRequest.new # ThirdPartyAchIdGetRequest | The third_party_ach to update

begin
  # update third_party_ach
  result = api_instance.third_party_ach_id_patch(id, third_party_ach_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->third_party_ach_id_patch: #{e}"
end
```

#### Using the third_party_ach_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ThirdPartyAchGet200ResponseInner>, Integer, Hash)> third_party_ach_id_patch_with_http_info(id, third_party_ach_id_get_request)

```ruby
begin
  # update third_party_ach
  data, status_code, headers = api_instance.third_party_ach_id_patch_with_http_info(id, third_party_ach_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ThirdPartyAchGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->third_party_ach_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **third_party_ach_id_get_request** | [**ThirdPartyAchIdGetRequest**](ThirdPartyAchIdGetRequest.md) | The third_party_ach to update |  |

### Return type

[**ThirdPartyAchGet200ResponseInner**](ThirdPartyAchGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## third_party_ach_post

> <ThirdPartyAchGet200ResponseInner> third_party_ach_post(third_party_ach_get_request)

create third_party_ach

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
third_party_ach_get_request = OpenapiClient::ThirdPartyAchGetRequest.new({amount: 'amount_example', service: TODO, credit_counterparty_id: 'credit_counterparty_id_example', debit_counterparty_id: 'debit_counterparty_id_example'}) # ThirdPartyAchGetRequest | The third_party_ach to create

begin
  # create third_party_ach
  result = api_instance.third_party_ach_post(third_party_ach_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->third_party_ach_post: #{e}"
end
```

#### Using the third_party_ach_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ThirdPartyAchGet200ResponseInner>, Integer, Hash)> third_party_ach_post_with_http_info(third_party_ach_get_request)

```ruby
begin
  # create third_party_ach
  data, status_code, headers = api_instance.third_party_ach_post_with_http_info(third_party_ach_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ThirdPartyAchGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->third_party_ach_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **third_party_ach_get_request** | [**ThirdPartyAchGetRequest**](ThirdPartyAchGetRequest.md) | The third_party_ach to create |  |

### Return type

[**ThirdPartyAchGet200ResponseInner**](ThirdPartyAchGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## transaction_get

> <Array<TransactionIdGet200Response>> transaction_get

index transaction

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index transaction
  result = api_instance.transaction_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->transaction_get: #{e}"
end
```

#### Using the transaction_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<TransactionIdGet200Response>>, Integer, Hash)> transaction_get_with_http_info

```ruby
begin
  # index transaction
  data, status_code, headers = api_instance.transaction_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<TransactionIdGet200Response>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->transaction_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;TransactionIdGet200Response&gt;**](TransactionIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## transaction_id_get

> <TransactionIdGet200Response> transaction_id_get(id)

get transaction

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get transaction
  result = api_instance.transaction_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->transaction_id_get: #{e}"
end
```

#### Using the transaction_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TransactionIdGet200Response>, Integer, Hash)> transaction_id_get_with_http_info(id)

```ruby
begin
  # get transaction
  data, status_code, headers = api_instance.transaction_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TransactionIdGet200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->transaction_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**TransactionIdGet200Response**](TransactionIdGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## webhook_get

> <Array<WebhookGet200ResponseInner>> webhook_get

index webhook

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index webhook
  result = api_instance.webhook_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->webhook_get: #{e}"
end
```

#### Using the webhook_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<WebhookGet200ResponseInner>>, Integer, Hash)> webhook_get_with_http_info

```ruby
begin
  # index webhook
  data, status_code, headers = api_instance.webhook_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<WebhookGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->webhook_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;WebhookGet200ResponseInner&gt;**](WebhookGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## webhook_id_delete

> webhook_id_delete(id)

delete webhook

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # delete webhook
  api_instance.webhook_id_delete(id)
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->webhook_id_delete: #{e}"
end
```

#### Using the webhook_id_delete_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> webhook_id_delete_with_http_info(id)

```ruby
begin
  # delete webhook
  data, status_code, headers = api_instance.webhook_id_delete_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->webhook_id_delete_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

nil (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## webhook_id_get

> <WebhookGet200ResponseInner> webhook_id_get(id)

get webhook

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get webhook
  result = api_instance.webhook_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->webhook_id_get: #{e}"
end
```

#### Using the webhook_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<WebhookGet200ResponseInner>, Integer, Hash)> webhook_id_get_with_http_info(id)

```ruby
begin
  # get webhook
  data, status_code, headers = api_instance.webhook_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <WebhookGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->webhook_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**WebhookGet200ResponseInner**](WebhookGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## webhook_id_patch

> <WebhookGet200ResponseInner> webhook_id_patch(id, webhook_id_delete_request)

update webhook

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
webhook_id_delete_request = OpenapiClient::WebhookIdDeleteRequest.new # WebhookIdDeleteRequest | The webhook to update

begin
  # update webhook
  result = api_instance.webhook_id_patch(id, webhook_id_delete_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->webhook_id_patch: #{e}"
end
```

#### Using the webhook_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<WebhookGet200ResponseInner>, Integer, Hash)> webhook_id_patch_with_http_info(id, webhook_id_delete_request)

```ruby
begin
  # update webhook
  data, status_code, headers = api_instance.webhook_id_patch_with_http_info(id, webhook_id_delete_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <WebhookGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->webhook_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **webhook_id_delete_request** | [**WebhookIdDeleteRequest**](WebhookIdDeleteRequest.md) | The webhook to update |  |

### Return type

[**WebhookGet200ResponseInner**](WebhookGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## webhook_post

> <WebhookGet200ResponseInner> webhook_post(webhook_get_request)

create webhook

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
webhook_get_request = OpenapiClient::WebhookGetRequest.new({event: 'event_example', status: TODO, url: TODO}) # WebhookGetRequest | The webhook to create

begin
  # create webhook
  result = api_instance.webhook_post(webhook_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->webhook_post: #{e}"
end
```

#### Using the webhook_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<WebhookGet200ResponseInner>, Integer, Hash)> webhook_post_with_http_info(webhook_get_request)

```ruby
begin
  # create webhook
  data, status_code, headers = api_instance.webhook_post_with_http_info(webhook_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <WebhookGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->webhook_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **webhook_get_request** | [**WebhookGetRequest**](WebhookGetRequest.md) | The webhook to create |  |

### Return type

[**WebhookGet200ResponseInner**](WebhookGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## wire_get

> <Array<WireGet200ResponseInner>> wire_get

index wire

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new

begin
  # index wire
  result = api_instance.wire_get
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->wire_get: #{e}"
end
```

#### Using the wire_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<WireGet200ResponseInner>>, Integer, Hash)> wire_get_with_http_info

```ruby
begin
  # index wire
  data, status_code, headers = api_instance.wire_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<WireGet200ResponseInner>>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->wire_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;WireGet200ResponseInner&gt;**](WireGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## wire_id_get

> <WireGet200ResponseInner> wire_id_get(id)

get wire

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 

begin
  # get wire
  result = api_instance.wire_id_get(id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->wire_id_get: #{e}"
end
```

#### Using the wire_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<WireGet200ResponseInner>, Integer, Hash)> wire_id_get_with_http_info(id)

```ruby
begin
  # get wire
  data, status_code, headers = api_instance.wire_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <WireGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->wire_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**WireGet200ResponseInner**](WireGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## wire_id_patch

> <WireGet200ResponseInner> wire_id_patch(id, wire_id_get_request)

update wire

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
id = 'id_example' # String | 
wire_id_get_request = OpenapiClient::WireIdGetRequest.new # WireIdGetRequest | The wire to update

begin
  # update wire
  result = api_instance.wire_id_patch(id, wire_id_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->wire_id_patch: #{e}"
end
```

#### Using the wire_id_patch_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<WireGet200ResponseInner>, Integer, Hash)> wire_id_patch_with_http_info(id, wire_id_get_request)

```ruby
begin
  # update wire
  data, status_code, headers = api_instance.wire_id_patch_with_http_info(id, wire_id_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <WireGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->wire_id_patch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **wire_id_get_request** | [**WireIdGetRequest**](WireIdGetRequest.md) | The wire to update |  |

### Return type

[**WireGet200ResponseInner**](WireGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## wire_post

> <WireGet200ResponseInner> wire_post(wire_get_request)

create wire

### Examples

```ruby
require 'time'
require 'openapi_client'

api_instance = OpenapiClient::DefaultApi.new
wire_get_request = OpenapiClient::WireGetRequest.new({amount: 'amount_example', counterparty_id: 'counterparty_id_example', account_id: 'account_id_example'}) # WireGetRequest | The wire to create

begin
  # create wire
  result = api_instance.wire_post(wire_get_request)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->wire_post: #{e}"
end
```

#### Using the wire_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<WireGet200ResponseInner>, Integer, Hash)> wire_post_with_http_info(wire_get_request)

```ruby
begin
  # create wire
  data, status_code, headers = api_instance.wire_post_with_http_info(wire_get_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <WireGet200ResponseInner>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->wire_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **wire_get_request** | [**WireGetRequest**](WireGetRequest.md) | The wire to create |  |

### Return type

[**WireGet200ResponseInner**](WireGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

