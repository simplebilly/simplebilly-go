# OrderUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuditLog** | Pointer to **interface{}** |  | [optional] 
**Currency** | Pointer to **NullableString** |  | [optional] 
**CustomerId** | Pointer to **NullableString** | References the customer entity. | [optional] 
**ExternalReference** | Pointer to **NullableString** |  | [optional] 
**InvoiceAddress** | Pointer to **interface{}** |  | [optional] 
**Items** | Pointer to **interface{}** |  | [optional] 
**Language** | Pointer to [**NullableLanguageCode**](LanguageCode.md) |  | [optional] 
**OrderStatus** | Pointer to [**NullableOrderStatus**](OrderStatus.md) |  | [optional] 
**PaymentMethod** | Pointer to [**NullablePaymentMethod**](PaymentMethod.md) |  | [optional] 
**ShippingAddress** | Pointer to **interface{}** |  | [optional] 
**ShippingCost** | Pointer to **NullableString** |  | [optional] 
**ShippingMethod** | Pointer to **NullableString** |  | [optional] 
**ShippingWeight** | Pointer to **NullableString** |  | [optional] 
**Tags** | Pointer to **[]string** |  | [optional] 
**TotalCost** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewOrderUpdate

`func NewOrderUpdate() *OrderUpdate`

NewOrderUpdate instantiates a new OrderUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderUpdateWithDefaults

`func NewOrderUpdateWithDefaults() *OrderUpdate`

NewOrderUpdateWithDefaults instantiates a new OrderUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuditLog

`func (o *OrderUpdate) GetAuditLog() interface{}`

GetAuditLog returns the AuditLog field if non-nil, zero value otherwise.

### GetAuditLogOk

`func (o *OrderUpdate) GetAuditLogOk() (*interface{}, bool)`

GetAuditLogOk returns a tuple with the AuditLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditLog

`func (o *OrderUpdate) SetAuditLog(v interface{})`

SetAuditLog sets AuditLog field to given value.

### HasAuditLog

`func (o *OrderUpdate) HasAuditLog() bool`

HasAuditLog returns a boolean if a field has been set.

### SetAuditLogNil

`func (o *OrderUpdate) SetAuditLogNil(b bool)`

 SetAuditLogNil sets the value for AuditLog to be an explicit nil

### UnsetAuditLog
`func (o *OrderUpdate) UnsetAuditLog()`

UnsetAuditLog ensures that no value is present for AuditLog, not even an explicit nil
### GetCurrency

`func (o *OrderUpdate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *OrderUpdate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *OrderUpdate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *OrderUpdate) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *OrderUpdate) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *OrderUpdate) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetCustomerId

`func (o *OrderUpdate) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *OrderUpdate) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *OrderUpdate) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *OrderUpdate) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *OrderUpdate) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *OrderUpdate) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetExternalReference

`func (o *OrderUpdate) GetExternalReference() string`

GetExternalReference returns the ExternalReference field if non-nil, zero value otherwise.

### GetExternalReferenceOk

`func (o *OrderUpdate) GetExternalReferenceOk() (*string, bool)`

GetExternalReferenceOk returns a tuple with the ExternalReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalReference

`func (o *OrderUpdate) SetExternalReference(v string)`

SetExternalReference sets ExternalReference field to given value.

### HasExternalReference

`func (o *OrderUpdate) HasExternalReference() bool`

HasExternalReference returns a boolean if a field has been set.

### SetExternalReferenceNil

`func (o *OrderUpdate) SetExternalReferenceNil(b bool)`

 SetExternalReferenceNil sets the value for ExternalReference to be an explicit nil

### UnsetExternalReference
`func (o *OrderUpdate) UnsetExternalReference()`

UnsetExternalReference ensures that no value is present for ExternalReference, not even an explicit nil
### GetInvoiceAddress

`func (o *OrderUpdate) GetInvoiceAddress() interface{}`

GetInvoiceAddress returns the InvoiceAddress field if non-nil, zero value otherwise.

### GetInvoiceAddressOk

`func (o *OrderUpdate) GetInvoiceAddressOk() (*interface{}, bool)`

GetInvoiceAddressOk returns a tuple with the InvoiceAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceAddress

`func (o *OrderUpdate) SetInvoiceAddress(v interface{})`

SetInvoiceAddress sets InvoiceAddress field to given value.

### HasInvoiceAddress

`func (o *OrderUpdate) HasInvoiceAddress() bool`

HasInvoiceAddress returns a boolean if a field has been set.

### SetInvoiceAddressNil

`func (o *OrderUpdate) SetInvoiceAddressNil(b bool)`

 SetInvoiceAddressNil sets the value for InvoiceAddress to be an explicit nil

### UnsetInvoiceAddress
`func (o *OrderUpdate) UnsetInvoiceAddress()`

UnsetInvoiceAddress ensures that no value is present for InvoiceAddress, not even an explicit nil
### GetItems

`func (o *OrderUpdate) GetItems() interface{}`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *OrderUpdate) GetItemsOk() (*interface{}, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *OrderUpdate) SetItems(v interface{})`

SetItems sets Items field to given value.

### HasItems

`func (o *OrderUpdate) HasItems() bool`

HasItems returns a boolean if a field has been set.

### SetItemsNil

`func (o *OrderUpdate) SetItemsNil(b bool)`

 SetItemsNil sets the value for Items to be an explicit nil

### UnsetItems
`func (o *OrderUpdate) UnsetItems()`

UnsetItems ensures that no value is present for Items, not even an explicit nil
### GetLanguage

`func (o *OrderUpdate) GetLanguage() LanguageCode`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *OrderUpdate) GetLanguageOk() (*LanguageCode, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *OrderUpdate) SetLanguage(v LanguageCode)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *OrderUpdate) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### SetLanguageNil

`func (o *OrderUpdate) SetLanguageNil(b bool)`

 SetLanguageNil sets the value for Language to be an explicit nil

### UnsetLanguage
`func (o *OrderUpdate) UnsetLanguage()`

UnsetLanguage ensures that no value is present for Language, not even an explicit nil
### GetOrderStatus

`func (o *OrderUpdate) GetOrderStatus() OrderStatus`

GetOrderStatus returns the OrderStatus field if non-nil, zero value otherwise.

### GetOrderStatusOk

`func (o *OrderUpdate) GetOrderStatusOk() (*OrderStatus, bool)`

GetOrderStatusOk returns a tuple with the OrderStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderStatus

`func (o *OrderUpdate) SetOrderStatus(v OrderStatus)`

SetOrderStatus sets OrderStatus field to given value.

### HasOrderStatus

`func (o *OrderUpdate) HasOrderStatus() bool`

HasOrderStatus returns a boolean if a field has been set.

### SetOrderStatusNil

`func (o *OrderUpdate) SetOrderStatusNil(b bool)`

 SetOrderStatusNil sets the value for OrderStatus to be an explicit nil

### UnsetOrderStatus
`func (o *OrderUpdate) UnsetOrderStatus()`

UnsetOrderStatus ensures that no value is present for OrderStatus, not even an explicit nil
### GetPaymentMethod

`func (o *OrderUpdate) GetPaymentMethod() PaymentMethod`

GetPaymentMethod returns the PaymentMethod field if non-nil, zero value otherwise.

### GetPaymentMethodOk

`func (o *OrderUpdate) GetPaymentMethodOk() (*PaymentMethod, bool)`

GetPaymentMethodOk returns a tuple with the PaymentMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentMethod

`func (o *OrderUpdate) SetPaymentMethod(v PaymentMethod)`

SetPaymentMethod sets PaymentMethod field to given value.

### HasPaymentMethod

`func (o *OrderUpdate) HasPaymentMethod() bool`

HasPaymentMethod returns a boolean if a field has been set.

### SetPaymentMethodNil

`func (o *OrderUpdate) SetPaymentMethodNil(b bool)`

 SetPaymentMethodNil sets the value for PaymentMethod to be an explicit nil

### UnsetPaymentMethod
`func (o *OrderUpdate) UnsetPaymentMethod()`

UnsetPaymentMethod ensures that no value is present for PaymentMethod, not even an explicit nil
### GetShippingAddress

`func (o *OrderUpdate) GetShippingAddress() interface{}`

GetShippingAddress returns the ShippingAddress field if non-nil, zero value otherwise.

### GetShippingAddressOk

`func (o *OrderUpdate) GetShippingAddressOk() (*interface{}, bool)`

GetShippingAddressOk returns a tuple with the ShippingAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingAddress

`func (o *OrderUpdate) SetShippingAddress(v interface{})`

SetShippingAddress sets ShippingAddress field to given value.

### HasShippingAddress

`func (o *OrderUpdate) HasShippingAddress() bool`

HasShippingAddress returns a boolean if a field has been set.

### SetShippingAddressNil

`func (o *OrderUpdate) SetShippingAddressNil(b bool)`

 SetShippingAddressNil sets the value for ShippingAddress to be an explicit nil

### UnsetShippingAddress
`func (o *OrderUpdate) UnsetShippingAddress()`

UnsetShippingAddress ensures that no value is present for ShippingAddress, not even an explicit nil
### GetShippingCost

`func (o *OrderUpdate) GetShippingCost() string`

GetShippingCost returns the ShippingCost field if non-nil, zero value otherwise.

### GetShippingCostOk

`func (o *OrderUpdate) GetShippingCostOk() (*string, bool)`

GetShippingCostOk returns a tuple with the ShippingCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingCost

`func (o *OrderUpdate) SetShippingCost(v string)`

SetShippingCost sets ShippingCost field to given value.

### HasShippingCost

`func (o *OrderUpdate) HasShippingCost() bool`

HasShippingCost returns a boolean if a field has been set.

### SetShippingCostNil

`func (o *OrderUpdate) SetShippingCostNil(b bool)`

 SetShippingCostNil sets the value for ShippingCost to be an explicit nil

### UnsetShippingCost
`func (o *OrderUpdate) UnsetShippingCost()`

UnsetShippingCost ensures that no value is present for ShippingCost, not even an explicit nil
### GetShippingMethod

`func (o *OrderUpdate) GetShippingMethod() string`

GetShippingMethod returns the ShippingMethod field if non-nil, zero value otherwise.

### GetShippingMethodOk

`func (o *OrderUpdate) GetShippingMethodOk() (*string, bool)`

GetShippingMethodOk returns a tuple with the ShippingMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingMethod

`func (o *OrderUpdate) SetShippingMethod(v string)`

SetShippingMethod sets ShippingMethod field to given value.

### HasShippingMethod

`func (o *OrderUpdate) HasShippingMethod() bool`

HasShippingMethod returns a boolean if a field has been set.

### SetShippingMethodNil

`func (o *OrderUpdate) SetShippingMethodNil(b bool)`

 SetShippingMethodNil sets the value for ShippingMethod to be an explicit nil

### UnsetShippingMethod
`func (o *OrderUpdate) UnsetShippingMethod()`

UnsetShippingMethod ensures that no value is present for ShippingMethod, not even an explicit nil
### GetShippingWeight

`func (o *OrderUpdate) GetShippingWeight() string`

GetShippingWeight returns the ShippingWeight field if non-nil, zero value otherwise.

### GetShippingWeightOk

`func (o *OrderUpdate) GetShippingWeightOk() (*string, bool)`

GetShippingWeightOk returns a tuple with the ShippingWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingWeight

`func (o *OrderUpdate) SetShippingWeight(v string)`

SetShippingWeight sets ShippingWeight field to given value.

### HasShippingWeight

`func (o *OrderUpdate) HasShippingWeight() bool`

HasShippingWeight returns a boolean if a field has been set.

### SetShippingWeightNil

`func (o *OrderUpdate) SetShippingWeightNil(b bool)`

 SetShippingWeightNil sets the value for ShippingWeight to be an explicit nil

### UnsetShippingWeight
`func (o *OrderUpdate) UnsetShippingWeight()`

UnsetShippingWeight ensures that no value is present for ShippingWeight, not even an explicit nil
### GetTags

`func (o *OrderUpdate) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *OrderUpdate) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *OrderUpdate) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *OrderUpdate) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *OrderUpdate) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *OrderUpdate) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTotalCost

`func (o *OrderUpdate) GetTotalCost() string`

GetTotalCost returns the TotalCost field if non-nil, zero value otherwise.

### GetTotalCostOk

`func (o *OrderUpdate) GetTotalCostOk() (*string, bool)`

GetTotalCostOk returns a tuple with the TotalCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCost

`func (o *OrderUpdate) SetTotalCost(v string)`

SetTotalCost sets TotalCost field to given value.

### HasTotalCost

`func (o *OrderUpdate) HasTotalCost() bool`

HasTotalCost returns a boolean if a field has been set.

### SetTotalCostNil

`func (o *OrderUpdate) SetTotalCostNil(b bool)`

 SetTotalCostNil sets the value for TotalCost to be an explicit nil

### UnsetTotalCost
`func (o *OrderUpdate) UnsetTotalCost()`

UnsetTotalCost ensures that no value is present for TotalCost, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


