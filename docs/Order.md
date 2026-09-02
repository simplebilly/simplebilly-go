# Order

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuditLog** | Pointer to **interface{}** |  | [optional] 
**Currency** | **string** |  | 
**CustomerId** | **string** | References the customer entity. | 
**ExternalReference** | Pointer to **NullableString** |  | [optional] 
**InvoiceAddress** | Pointer to **interface{}** |  | [optional] 
**Items** | Pointer to **interface{}** |  | [optional] 
**Language** | Pointer to [**LanguageCode**](LanguageCode.md) |  | [optional] 
**OrderStatus** | [**OrderStatus**](OrderStatus.md) |  | 
**PaymentMethod** | [**PaymentMethod**](PaymentMethod.md) |  | 
**ShippingAddress** | Pointer to **interface{}** |  | [optional] 
**ShippingCost** | **string** |  | 
**ShippingMethod** | **string** |  | 
**ShippingWeight** | **string** |  | 
**Tags** | **[]string** |  | 
**TotalCost** | **string** |  | 

## Methods

### NewOrder

`func NewOrder(currency string, customerId string, orderStatus OrderStatus, paymentMethod PaymentMethod, shippingCost string, shippingMethod string, shippingWeight string, tags []string, totalCost string, ) *Order`

NewOrder instantiates a new Order object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderWithDefaults

`func NewOrderWithDefaults() *Order`

NewOrderWithDefaults instantiates a new Order object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuditLog

`func (o *Order) GetAuditLog() interface{}`

GetAuditLog returns the AuditLog field if non-nil, zero value otherwise.

### GetAuditLogOk

`func (o *Order) GetAuditLogOk() (*interface{}, bool)`

GetAuditLogOk returns a tuple with the AuditLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditLog

`func (o *Order) SetAuditLog(v interface{})`

SetAuditLog sets AuditLog field to given value.

### HasAuditLog

`func (o *Order) HasAuditLog() bool`

HasAuditLog returns a boolean if a field has been set.

### SetAuditLogNil

`func (o *Order) SetAuditLogNil(b bool)`

 SetAuditLogNil sets the value for AuditLog to be an explicit nil

### UnsetAuditLog
`func (o *Order) UnsetAuditLog()`

UnsetAuditLog ensures that no value is present for AuditLog, not even an explicit nil
### GetCurrency

`func (o *Order) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Order) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Order) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetCustomerId

`func (o *Order) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *Order) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *Order) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.


### GetExternalReference

`func (o *Order) GetExternalReference() string`

GetExternalReference returns the ExternalReference field if non-nil, zero value otherwise.

### GetExternalReferenceOk

`func (o *Order) GetExternalReferenceOk() (*string, bool)`

GetExternalReferenceOk returns a tuple with the ExternalReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalReference

`func (o *Order) SetExternalReference(v string)`

SetExternalReference sets ExternalReference field to given value.

### HasExternalReference

`func (o *Order) HasExternalReference() bool`

HasExternalReference returns a boolean if a field has been set.

### SetExternalReferenceNil

`func (o *Order) SetExternalReferenceNil(b bool)`

 SetExternalReferenceNil sets the value for ExternalReference to be an explicit nil

### UnsetExternalReference
`func (o *Order) UnsetExternalReference()`

UnsetExternalReference ensures that no value is present for ExternalReference, not even an explicit nil
### GetInvoiceAddress

`func (o *Order) GetInvoiceAddress() interface{}`

GetInvoiceAddress returns the InvoiceAddress field if non-nil, zero value otherwise.

### GetInvoiceAddressOk

`func (o *Order) GetInvoiceAddressOk() (*interface{}, bool)`

GetInvoiceAddressOk returns a tuple with the InvoiceAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceAddress

`func (o *Order) SetInvoiceAddress(v interface{})`

SetInvoiceAddress sets InvoiceAddress field to given value.

### HasInvoiceAddress

`func (o *Order) HasInvoiceAddress() bool`

HasInvoiceAddress returns a boolean if a field has been set.

### SetInvoiceAddressNil

`func (o *Order) SetInvoiceAddressNil(b bool)`

 SetInvoiceAddressNil sets the value for InvoiceAddress to be an explicit nil

### UnsetInvoiceAddress
`func (o *Order) UnsetInvoiceAddress()`

UnsetInvoiceAddress ensures that no value is present for InvoiceAddress, not even an explicit nil
### GetItems

`func (o *Order) GetItems() interface{}`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *Order) GetItemsOk() (*interface{}, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *Order) SetItems(v interface{})`

SetItems sets Items field to given value.

### HasItems

`func (o *Order) HasItems() bool`

HasItems returns a boolean if a field has been set.

### SetItemsNil

`func (o *Order) SetItemsNil(b bool)`

 SetItemsNil sets the value for Items to be an explicit nil

### UnsetItems
`func (o *Order) UnsetItems()`

UnsetItems ensures that no value is present for Items, not even an explicit nil
### GetLanguage

`func (o *Order) GetLanguage() LanguageCode`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *Order) GetLanguageOk() (*LanguageCode, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *Order) SetLanguage(v LanguageCode)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *Order) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetOrderStatus

`func (o *Order) GetOrderStatus() OrderStatus`

GetOrderStatus returns the OrderStatus field if non-nil, zero value otherwise.

### GetOrderStatusOk

`func (o *Order) GetOrderStatusOk() (*OrderStatus, bool)`

GetOrderStatusOk returns a tuple with the OrderStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderStatus

`func (o *Order) SetOrderStatus(v OrderStatus)`

SetOrderStatus sets OrderStatus field to given value.


### GetPaymentMethod

`func (o *Order) GetPaymentMethod() PaymentMethod`

GetPaymentMethod returns the PaymentMethod field if non-nil, zero value otherwise.

### GetPaymentMethodOk

`func (o *Order) GetPaymentMethodOk() (*PaymentMethod, bool)`

GetPaymentMethodOk returns a tuple with the PaymentMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentMethod

`func (o *Order) SetPaymentMethod(v PaymentMethod)`

SetPaymentMethod sets PaymentMethod field to given value.


### GetShippingAddress

`func (o *Order) GetShippingAddress() interface{}`

GetShippingAddress returns the ShippingAddress field if non-nil, zero value otherwise.

### GetShippingAddressOk

`func (o *Order) GetShippingAddressOk() (*interface{}, bool)`

GetShippingAddressOk returns a tuple with the ShippingAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingAddress

`func (o *Order) SetShippingAddress(v interface{})`

SetShippingAddress sets ShippingAddress field to given value.

### HasShippingAddress

`func (o *Order) HasShippingAddress() bool`

HasShippingAddress returns a boolean if a field has been set.

### SetShippingAddressNil

`func (o *Order) SetShippingAddressNil(b bool)`

 SetShippingAddressNil sets the value for ShippingAddress to be an explicit nil

### UnsetShippingAddress
`func (o *Order) UnsetShippingAddress()`

UnsetShippingAddress ensures that no value is present for ShippingAddress, not even an explicit nil
### GetShippingCost

`func (o *Order) GetShippingCost() string`

GetShippingCost returns the ShippingCost field if non-nil, zero value otherwise.

### GetShippingCostOk

`func (o *Order) GetShippingCostOk() (*string, bool)`

GetShippingCostOk returns a tuple with the ShippingCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingCost

`func (o *Order) SetShippingCost(v string)`

SetShippingCost sets ShippingCost field to given value.


### GetShippingMethod

`func (o *Order) GetShippingMethod() string`

GetShippingMethod returns the ShippingMethod field if non-nil, zero value otherwise.

### GetShippingMethodOk

`func (o *Order) GetShippingMethodOk() (*string, bool)`

GetShippingMethodOk returns a tuple with the ShippingMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingMethod

`func (o *Order) SetShippingMethod(v string)`

SetShippingMethod sets ShippingMethod field to given value.


### GetShippingWeight

`func (o *Order) GetShippingWeight() string`

GetShippingWeight returns the ShippingWeight field if non-nil, zero value otherwise.

### GetShippingWeightOk

`func (o *Order) GetShippingWeightOk() (*string, bool)`

GetShippingWeightOk returns a tuple with the ShippingWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingWeight

`func (o *Order) SetShippingWeight(v string)`

SetShippingWeight sets ShippingWeight field to given value.


### GetTags

`func (o *Order) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *Order) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *Order) SetTags(v []string)`

SetTags sets Tags field to given value.


### GetTotalCost

`func (o *Order) GetTotalCost() string`

GetTotalCost returns the TotalCost field if non-nil, zero value otherwise.

### GetTotalCostOk

`func (o *Order) GetTotalCostOk() (*string, bool)`

GetTotalCostOk returns a tuple with the TotalCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCost

`func (o *Order) SetTotalCost(v string)`

SetTotalCost sets TotalCost field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


