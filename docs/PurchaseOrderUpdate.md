# PurchaseOrderUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **NullableString** |  | [optional] 
**DeliveryAddress** | Pointer to **interface{}** |  | [optional] 
**ExpectedDeliveryDate** | Pointer to **NullableString** |  | [optional] 
**LineItems** | Pointer to **interface{}** | JSON array of &#x60;{product_id, name, quantity, unit_price_net, tax_rate, delivery_date}&#x60;. | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**OrderDate** | Pointer to **NullableString** |  | [optional] 
**PoNumber** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**NullablePurchaseOrderStatus**](PurchaseOrderStatus.md) | One of: draft | ordered | partially_received | received | cancelled | [optional] 
**SupplierContactId** | Pointer to **NullableString** | References the supplier entity. | [optional] 
**SupplierName** | Pointer to **NullableString** |  | [optional] 
**TotalGrossAmount** | Pointer to **NullableString** |  | [optional] 
**TotalNetAmount** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewPurchaseOrderUpdate

`func NewPurchaseOrderUpdate() *PurchaseOrderUpdate`

NewPurchaseOrderUpdate instantiates a new PurchaseOrderUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrderUpdateWithDefaults

`func NewPurchaseOrderUpdateWithDefaults() *PurchaseOrderUpdate`

NewPurchaseOrderUpdateWithDefaults instantiates a new PurchaseOrderUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *PurchaseOrderUpdate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *PurchaseOrderUpdate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *PurchaseOrderUpdate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *PurchaseOrderUpdate) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *PurchaseOrderUpdate) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *PurchaseOrderUpdate) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetDeliveryAddress

`func (o *PurchaseOrderUpdate) GetDeliveryAddress() interface{}`

GetDeliveryAddress returns the DeliveryAddress field if non-nil, zero value otherwise.

### GetDeliveryAddressOk

`func (o *PurchaseOrderUpdate) GetDeliveryAddressOk() (*interface{}, bool)`

GetDeliveryAddressOk returns a tuple with the DeliveryAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryAddress

`func (o *PurchaseOrderUpdate) SetDeliveryAddress(v interface{})`

SetDeliveryAddress sets DeliveryAddress field to given value.

### HasDeliveryAddress

`func (o *PurchaseOrderUpdate) HasDeliveryAddress() bool`

HasDeliveryAddress returns a boolean if a field has been set.

### SetDeliveryAddressNil

`func (o *PurchaseOrderUpdate) SetDeliveryAddressNil(b bool)`

 SetDeliveryAddressNil sets the value for DeliveryAddress to be an explicit nil

### UnsetDeliveryAddress
`func (o *PurchaseOrderUpdate) UnsetDeliveryAddress()`

UnsetDeliveryAddress ensures that no value is present for DeliveryAddress, not even an explicit nil
### GetExpectedDeliveryDate

`func (o *PurchaseOrderUpdate) GetExpectedDeliveryDate() string`

GetExpectedDeliveryDate returns the ExpectedDeliveryDate field if non-nil, zero value otherwise.

### GetExpectedDeliveryDateOk

`func (o *PurchaseOrderUpdate) GetExpectedDeliveryDateOk() (*string, bool)`

GetExpectedDeliveryDateOk returns a tuple with the ExpectedDeliveryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedDeliveryDate

`func (o *PurchaseOrderUpdate) SetExpectedDeliveryDate(v string)`

SetExpectedDeliveryDate sets ExpectedDeliveryDate field to given value.

### HasExpectedDeliveryDate

`func (o *PurchaseOrderUpdate) HasExpectedDeliveryDate() bool`

HasExpectedDeliveryDate returns a boolean if a field has been set.

### SetExpectedDeliveryDateNil

`func (o *PurchaseOrderUpdate) SetExpectedDeliveryDateNil(b bool)`

 SetExpectedDeliveryDateNil sets the value for ExpectedDeliveryDate to be an explicit nil

### UnsetExpectedDeliveryDate
`func (o *PurchaseOrderUpdate) UnsetExpectedDeliveryDate()`

UnsetExpectedDeliveryDate ensures that no value is present for ExpectedDeliveryDate, not even an explicit nil
### GetLineItems

`func (o *PurchaseOrderUpdate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *PurchaseOrderUpdate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *PurchaseOrderUpdate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *PurchaseOrderUpdate) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *PurchaseOrderUpdate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *PurchaseOrderUpdate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *PurchaseOrderUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *PurchaseOrderUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *PurchaseOrderUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *PurchaseOrderUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *PurchaseOrderUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *PurchaseOrderUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOrderDate

`func (o *PurchaseOrderUpdate) GetOrderDate() string`

GetOrderDate returns the OrderDate field if non-nil, zero value otherwise.

### GetOrderDateOk

`func (o *PurchaseOrderUpdate) GetOrderDateOk() (*string, bool)`

GetOrderDateOk returns a tuple with the OrderDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderDate

`func (o *PurchaseOrderUpdate) SetOrderDate(v string)`

SetOrderDate sets OrderDate field to given value.

### HasOrderDate

`func (o *PurchaseOrderUpdate) HasOrderDate() bool`

HasOrderDate returns a boolean if a field has been set.

### SetOrderDateNil

`func (o *PurchaseOrderUpdate) SetOrderDateNil(b bool)`

 SetOrderDateNil sets the value for OrderDate to be an explicit nil

### UnsetOrderDate
`func (o *PurchaseOrderUpdate) UnsetOrderDate()`

UnsetOrderDate ensures that no value is present for OrderDate, not even an explicit nil
### GetPoNumber

`func (o *PurchaseOrderUpdate) GetPoNumber() string`

GetPoNumber returns the PoNumber field if non-nil, zero value otherwise.

### GetPoNumberOk

`func (o *PurchaseOrderUpdate) GetPoNumberOk() (*string, bool)`

GetPoNumberOk returns a tuple with the PoNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoNumber

`func (o *PurchaseOrderUpdate) SetPoNumber(v string)`

SetPoNumber sets PoNumber field to given value.

### HasPoNumber

`func (o *PurchaseOrderUpdate) HasPoNumber() bool`

HasPoNumber returns a boolean if a field has been set.

### SetPoNumberNil

`func (o *PurchaseOrderUpdate) SetPoNumberNil(b bool)`

 SetPoNumberNil sets the value for PoNumber to be an explicit nil

### UnsetPoNumber
`func (o *PurchaseOrderUpdate) UnsetPoNumber()`

UnsetPoNumber ensures that no value is present for PoNumber, not even an explicit nil
### GetStatus

`func (o *PurchaseOrderUpdate) GetStatus() PurchaseOrderStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PurchaseOrderUpdate) GetStatusOk() (*PurchaseOrderStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PurchaseOrderUpdate) SetStatus(v PurchaseOrderStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PurchaseOrderUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *PurchaseOrderUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *PurchaseOrderUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetSupplierContactId

`func (o *PurchaseOrderUpdate) GetSupplierContactId() string`

GetSupplierContactId returns the SupplierContactId field if non-nil, zero value otherwise.

### GetSupplierContactIdOk

`func (o *PurchaseOrderUpdate) GetSupplierContactIdOk() (*string, bool)`

GetSupplierContactIdOk returns a tuple with the SupplierContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierContactId

`func (o *PurchaseOrderUpdate) SetSupplierContactId(v string)`

SetSupplierContactId sets SupplierContactId field to given value.

### HasSupplierContactId

`func (o *PurchaseOrderUpdate) HasSupplierContactId() bool`

HasSupplierContactId returns a boolean if a field has been set.

### SetSupplierContactIdNil

`func (o *PurchaseOrderUpdate) SetSupplierContactIdNil(b bool)`

 SetSupplierContactIdNil sets the value for SupplierContactId to be an explicit nil

### UnsetSupplierContactId
`func (o *PurchaseOrderUpdate) UnsetSupplierContactId()`

UnsetSupplierContactId ensures that no value is present for SupplierContactId, not even an explicit nil
### GetSupplierName

`func (o *PurchaseOrderUpdate) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *PurchaseOrderUpdate) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *PurchaseOrderUpdate) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.

### HasSupplierName

`func (o *PurchaseOrderUpdate) HasSupplierName() bool`

HasSupplierName returns a boolean if a field has been set.

### SetSupplierNameNil

`func (o *PurchaseOrderUpdate) SetSupplierNameNil(b bool)`

 SetSupplierNameNil sets the value for SupplierName to be an explicit nil

### UnsetSupplierName
`func (o *PurchaseOrderUpdate) UnsetSupplierName()`

UnsetSupplierName ensures that no value is present for SupplierName, not even an explicit nil
### GetTotalGrossAmount

`func (o *PurchaseOrderUpdate) GetTotalGrossAmount() string`

GetTotalGrossAmount returns the TotalGrossAmount field if non-nil, zero value otherwise.

### GetTotalGrossAmountOk

`func (o *PurchaseOrderUpdate) GetTotalGrossAmountOk() (*string, bool)`

GetTotalGrossAmountOk returns a tuple with the TotalGrossAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalGrossAmount

`func (o *PurchaseOrderUpdate) SetTotalGrossAmount(v string)`

SetTotalGrossAmount sets TotalGrossAmount field to given value.

### HasTotalGrossAmount

`func (o *PurchaseOrderUpdate) HasTotalGrossAmount() bool`

HasTotalGrossAmount returns a boolean if a field has been set.

### SetTotalGrossAmountNil

`func (o *PurchaseOrderUpdate) SetTotalGrossAmountNil(b bool)`

 SetTotalGrossAmountNil sets the value for TotalGrossAmount to be an explicit nil

### UnsetTotalGrossAmount
`func (o *PurchaseOrderUpdate) UnsetTotalGrossAmount()`

UnsetTotalGrossAmount ensures that no value is present for TotalGrossAmount, not even an explicit nil
### GetTotalNetAmount

`func (o *PurchaseOrderUpdate) GetTotalNetAmount() string`

GetTotalNetAmount returns the TotalNetAmount field if non-nil, zero value otherwise.

### GetTotalNetAmountOk

`func (o *PurchaseOrderUpdate) GetTotalNetAmountOk() (*string, bool)`

GetTotalNetAmountOk returns a tuple with the TotalNetAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalNetAmount

`func (o *PurchaseOrderUpdate) SetTotalNetAmount(v string)`

SetTotalNetAmount sets TotalNetAmount field to given value.

### HasTotalNetAmount

`func (o *PurchaseOrderUpdate) HasTotalNetAmount() bool`

HasTotalNetAmount returns a boolean if a field has been set.

### SetTotalNetAmountNil

`func (o *PurchaseOrderUpdate) SetTotalNetAmountNil(b bool)`

 SetTotalNetAmountNil sets the value for TotalNetAmount to be an explicit nil

### UnsetTotalNetAmount
`func (o *PurchaseOrderUpdate) UnsetTotalNetAmount()`

UnsetTotalNetAmount ensures that no value is present for TotalNetAmount, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


