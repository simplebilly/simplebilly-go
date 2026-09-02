# DeliveryDate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerId** | Pointer to **NullableString** | References the customer entity. | [optional] 
**FulfilledDate** | Pointer to **NullableString** | Date actually delivered (set on fulfillment). | [optional] 
**Note** | Pointer to **NullableString** |  | [optional] 
**OrderNumber** | **string** | Sales order number (&#x60;order.order_number&#x60;). | 
**OriginalDate** | Pointer to **NullableString** | Original date promised before rescheduling. | [optional] 
**ProductId** | Pointer to **NullableString** | Product line item this date applies to, if per-item. References the product entity. | [optional] 
**PromisedDate** | **string** | Date promised to the customer. | 
**Status** | [**NullableDeliveryDateStatus**](DeliveryDateStatus.md) | One of: promised | confirmed | rescheduled | fulfilled | late | cancelled | 

## Methods

### NewDeliveryDate

`func NewDeliveryDate(orderNumber string, promisedDate string, status NullableDeliveryDateStatus, ) *DeliveryDate`

NewDeliveryDate instantiates a new DeliveryDate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliveryDateWithDefaults

`func NewDeliveryDateWithDefaults() *DeliveryDate`

NewDeliveryDateWithDefaults instantiates a new DeliveryDate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerId

`func (o *DeliveryDate) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *DeliveryDate) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *DeliveryDate) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *DeliveryDate) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *DeliveryDate) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *DeliveryDate) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetFulfilledDate

`func (o *DeliveryDate) GetFulfilledDate() string`

GetFulfilledDate returns the FulfilledDate field if non-nil, zero value otherwise.

### GetFulfilledDateOk

`func (o *DeliveryDate) GetFulfilledDateOk() (*string, bool)`

GetFulfilledDateOk returns a tuple with the FulfilledDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFulfilledDate

`func (o *DeliveryDate) SetFulfilledDate(v string)`

SetFulfilledDate sets FulfilledDate field to given value.

### HasFulfilledDate

`func (o *DeliveryDate) HasFulfilledDate() bool`

HasFulfilledDate returns a boolean if a field has been set.

### SetFulfilledDateNil

`func (o *DeliveryDate) SetFulfilledDateNil(b bool)`

 SetFulfilledDateNil sets the value for FulfilledDate to be an explicit nil

### UnsetFulfilledDate
`func (o *DeliveryDate) UnsetFulfilledDate()`

UnsetFulfilledDate ensures that no value is present for FulfilledDate, not even an explicit nil
### GetNote

`func (o *DeliveryDate) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *DeliveryDate) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *DeliveryDate) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *DeliveryDate) HasNote() bool`

HasNote returns a boolean if a field has been set.

### SetNoteNil

`func (o *DeliveryDate) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *DeliveryDate) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetOrderNumber

`func (o *DeliveryDate) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *DeliveryDate) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *DeliveryDate) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.


### GetOriginalDate

`func (o *DeliveryDate) GetOriginalDate() string`

GetOriginalDate returns the OriginalDate field if non-nil, zero value otherwise.

### GetOriginalDateOk

`func (o *DeliveryDate) GetOriginalDateOk() (*string, bool)`

GetOriginalDateOk returns a tuple with the OriginalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalDate

`func (o *DeliveryDate) SetOriginalDate(v string)`

SetOriginalDate sets OriginalDate field to given value.

### HasOriginalDate

`func (o *DeliveryDate) HasOriginalDate() bool`

HasOriginalDate returns a boolean if a field has been set.

### SetOriginalDateNil

`func (o *DeliveryDate) SetOriginalDateNil(b bool)`

 SetOriginalDateNil sets the value for OriginalDate to be an explicit nil

### UnsetOriginalDate
`func (o *DeliveryDate) UnsetOriginalDate()`

UnsetOriginalDate ensures that no value is present for OriginalDate, not even an explicit nil
### GetProductId

`func (o *DeliveryDate) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *DeliveryDate) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *DeliveryDate) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *DeliveryDate) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *DeliveryDate) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *DeliveryDate) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetPromisedDate

`func (o *DeliveryDate) GetPromisedDate() string`

GetPromisedDate returns the PromisedDate field if non-nil, zero value otherwise.

### GetPromisedDateOk

`func (o *DeliveryDate) GetPromisedDateOk() (*string, bool)`

GetPromisedDateOk returns a tuple with the PromisedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromisedDate

`func (o *DeliveryDate) SetPromisedDate(v string)`

SetPromisedDate sets PromisedDate field to given value.


### GetStatus

`func (o *DeliveryDate) GetStatus() DeliveryDateStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DeliveryDate) GetStatusOk() (*DeliveryDateStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DeliveryDate) SetStatus(v DeliveryDateStatus)`

SetStatus sets Status field to given value.


### SetStatusNil

`func (o *DeliveryDate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *DeliveryDate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


