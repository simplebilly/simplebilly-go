# OrderCreate

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

### NewOrderCreate

`func NewOrderCreate(currency string, customerId string, orderStatus OrderStatus, paymentMethod PaymentMethod, shippingCost string, shippingMethod string, shippingWeight string, tags []string, totalCost string, ) *OrderCreate`

NewOrderCreate instantiates a new OrderCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderCreateWithDefaults

`func NewOrderCreateWithDefaults() *OrderCreate`

NewOrderCreateWithDefaults instantiates a new OrderCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuditLog

`func (o *OrderCreate) GetAuditLog() interface{}`

GetAuditLog returns the AuditLog field if non-nil, zero value otherwise.

### GetAuditLogOk

`func (o *OrderCreate) GetAuditLogOk() (*interface{}, bool)`

GetAuditLogOk returns a tuple with the AuditLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditLog

`func (o *OrderCreate) SetAuditLog(v interface{})`

SetAuditLog sets AuditLog field to given value.

### HasAuditLog

`func (o *OrderCreate) HasAuditLog() bool`

HasAuditLog returns a boolean if a field has been set.

### SetAuditLogNil

`func (o *OrderCreate) SetAuditLogNil(b bool)`

 SetAuditLogNil sets the value for AuditLog to be an explicit nil

### UnsetAuditLog
`func (o *OrderCreate) UnsetAuditLog()`

UnsetAuditLog ensures that no value is present for AuditLog, not even an explicit nil
### GetCurrency

`func (o *OrderCreate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *OrderCreate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *OrderCreate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetCustomerId

`func (o *OrderCreate) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *OrderCreate) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *OrderCreate) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.


### GetExternalReference

`func (o *OrderCreate) GetExternalReference() string`

GetExternalReference returns the ExternalReference field if non-nil, zero value otherwise.

### GetExternalReferenceOk

`func (o *OrderCreate) GetExternalReferenceOk() (*string, bool)`

GetExternalReferenceOk returns a tuple with the ExternalReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalReference

`func (o *OrderCreate) SetExternalReference(v string)`

SetExternalReference sets ExternalReference field to given value.

### HasExternalReference

`func (o *OrderCreate) HasExternalReference() bool`

HasExternalReference returns a boolean if a field has been set.

### SetExternalReferenceNil

`func (o *OrderCreate) SetExternalReferenceNil(b bool)`

 SetExternalReferenceNil sets the value for ExternalReference to be an explicit nil

### UnsetExternalReference
`func (o *OrderCreate) UnsetExternalReference()`

UnsetExternalReference ensures that no value is present for ExternalReference, not even an explicit nil
### GetInvoiceAddress

`func (o *OrderCreate) GetInvoiceAddress() interface{}`

GetInvoiceAddress returns the InvoiceAddress field if non-nil, zero value otherwise.

### GetInvoiceAddressOk

`func (o *OrderCreate) GetInvoiceAddressOk() (*interface{}, bool)`

GetInvoiceAddressOk returns a tuple with the InvoiceAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceAddress

`func (o *OrderCreate) SetInvoiceAddress(v interface{})`

SetInvoiceAddress sets InvoiceAddress field to given value.

### HasInvoiceAddress

`func (o *OrderCreate) HasInvoiceAddress() bool`

HasInvoiceAddress returns a boolean if a field has been set.

### SetInvoiceAddressNil

`func (o *OrderCreate) SetInvoiceAddressNil(b bool)`

 SetInvoiceAddressNil sets the value for InvoiceAddress to be an explicit nil

### UnsetInvoiceAddress
`func (o *OrderCreate) UnsetInvoiceAddress()`

UnsetInvoiceAddress ensures that no value is present for InvoiceAddress, not even an explicit nil
### GetItems

`func (o *OrderCreate) GetItems() interface{}`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *OrderCreate) GetItemsOk() (*interface{}, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *OrderCreate) SetItems(v interface{})`

SetItems sets Items field to given value.

### HasItems

`func (o *OrderCreate) HasItems() bool`

HasItems returns a boolean if a field has been set.

### SetItemsNil

`func (o *OrderCreate) SetItemsNil(b bool)`

 SetItemsNil sets the value for Items to be an explicit nil

### UnsetItems
`func (o *OrderCreate) UnsetItems()`

UnsetItems ensures that no value is present for Items, not even an explicit nil
### GetLanguage

`func (o *OrderCreate) GetLanguage() LanguageCode`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *OrderCreate) GetLanguageOk() (*LanguageCode, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *OrderCreate) SetLanguage(v LanguageCode)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *OrderCreate) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetOrderStatus

`func (o *OrderCreate) GetOrderStatus() OrderStatus`

GetOrderStatus returns the OrderStatus field if non-nil, zero value otherwise.

### GetOrderStatusOk

`func (o *OrderCreate) GetOrderStatusOk() (*OrderStatus, bool)`

GetOrderStatusOk returns a tuple with the OrderStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderStatus

`func (o *OrderCreate) SetOrderStatus(v OrderStatus)`

SetOrderStatus sets OrderStatus field to given value.


### GetPaymentMethod

`func (o *OrderCreate) GetPaymentMethod() PaymentMethod`

GetPaymentMethod returns the PaymentMethod field if non-nil, zero value otherwise.

### GetPaymentMethodOk

`func (o *OrderCreate) GetPaymentMethodOk() (*PaymentMethod, bool)`

GetPaymentMethodOk returns a tuple with the PaymentMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentMethod

`func (o *OrderCreate) SetPaymentMethod(v PaymentMethod)`

SetPaymentMethod sets PaymentMethod field to given value.


### GetShippingAddress

`func (o *OrderCreate) GetShippingAddress() interface{}`

GetShippingAddress returns the ShippingAddress field if non-nil, zero value otherwise.

### GetShippingAddressOk

`func (o *OrderCreate) GetShippingAddressOk() (*interface{}, bool)`

GetShippingAddressOk returns a tuple with the ShippingAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingAddress

`func (o *OrderCreate) SetShippingAddress(v interface{})`

SetShippingAddress sets ShippingAddress field to given value.

### HasShippingAddress

`func (o *OrderCreate) HasShippingAddress() bool`

HasShippingAddress returns a boolean if a field has been set.

### SetShippingAddressNil

`func (o *OrderCreate) SetShippingAddressNil(b bool)`

 SetShippingAddressNil sets the value for ShippingAddress to be an explicit nil

### UnsetShippingAddress
`func (o *OrderCreate) UnsetShippingAddress()`

UnsetShippingAddress ensures that no value is present for ShippingAddress, not even an explicit nil
### GetShippingCost

`func (o *OrderCreate) GetShippingCost() string`

GetShippingCost returns the ShippingCost field if non-nil, zero value otherwise.

### GetShippingCostOk

`func (o *OrderCreate) GetShippingCostOk() (*string, bool)`

GetShippingCostOk returns a tuple with the ShippingCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingCost

`func (o *OrderCreate) SetShippingCost(v string)`

SetShippingCost sets ShippingCost field to given value.


### GetShippingMethod

`func (o *OrderCreate) GetShippingMethod() string`

GetShippingMethod returns the ShippingMethod field if non-nil, zero value otherwise.

### GetShippingMethodOk

`func (o *OrderCreate) GetShippingMethodOk() (*string, bool)`

GetShippingMethodOk returns a tuple with the ShippingMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingMethod

`func (o *OrderCreate) SetShippingMethod(v string)`

SetShippingMethod sets ShippingMethod field to given value.


### GetShippingWeight

`func (o *OrderCreate) GetShippingWeight() string`

GetShippingWeight returns the ShippingWeight field if non-nil, zero value otherwise.

### GetShippingWeightOk

`func (o *OrderCreate) GetShippingWeightOk() (*string, bool)`

GetShippingWeightOk returns a tuple with the ShippingWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingWeight

`func (o *OrderCreate) SetShippingWeight(v string)`

SetShippingWeight sets ShippingWeight field to given value.


### GetTags

`func (o *OrderCreate) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *OrderCreate) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *OrderCreate) SetTags(v []string)`

SetTags sets Tags field to given value.


### GetTotalCost

`func (o *OrderCreate) GetTotalCost() string`

GetTotalCost returns the TotalCost field if non-nil, zero value otherwise.

### GetTotalCostOk

`func (o *OrderCreate) GetTotalCostOk() (*string, bool)`

GetTotalCostOk returns a tuple with the TotalCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCost

`func (o *OrderCreate) SetTotalCost(v string)`

SetTotalCost sets TotalCost field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


