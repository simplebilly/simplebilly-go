# DeliveryDateUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerId** | Pointer to **NullableString** | References the customer entity. | [optional] 
**FulfilledDate** | Pointer to **NullableString** | Date actually delivered (set on fulfillment). | [optional] 
**Note** | Pointer to **NullableString** |  | [optional] 
**OrderNumber** | Pointer to **NullableString** | Sales order number (&#x60;order.order_number&#x60;). | [optional] 
**OriginalDate** | Pointer to **NullableString** | Original date promised before rescheduling. | [optional] 
**ProductId** | Pointer to **NullableString** | Product line item this date applies to, if per-item. References the product entity. | [optional] 
**PromisedDate** | Pointer to **NullableString** | Date promised to the customer. | [optional] 
**Status** | Pointer to [**NullableDeliveryDateStatus**](DeliveryDateStatus.md) | One of: promised | confirmed | rescheduled | fulfilled | late | cancelled | [optional] 

## Methods

### NewDeliveryDateUpdate

`func NewDeliveryDateUpdate() *DeliveryDateUpdate`

NewDeliveryDateUpdate instantiates a new DeliveryDateUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliveryDateUpdateWithDefaults

`func NewDeliveryDateUpdateWithDefaults() *DeliveryDateUpdate`

NewDeliveryDateUpdateWithDefaults instantiates a new DeliveryDateUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerId

`func (o *DeliveryDateUpdate) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *DeliveryDateUpdate) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *DeliveryDateUpdate) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *DeliveryDateUpdate) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *DeliveryDateUpdate) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *DeliveryDateUpdate) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetFulfilledDate

`func (o *DeliveryDateUpdate) GetFulfilledDate() string`

GetFulfilledDate returns the FulfilledDate field if non-nil, zero value otherwise.

### GetFulfilledDateOk

`func (o *DeliveryDateUpdate) GetFulfilledDateOk() (*string, bool)`

GetFulfilledDateOk returns a tuple with the FulfilledDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFulfilledDate

`func (o *DeliveryDateUpdate) SetFulfilledDate(v string)`

SetFulfilledDate sets FulfilledDate field to given value.

### HasFulfilledDate

`func (o *DeliveryDateUpdate) HasFulfilledDate() bool`

HasFulfilledDate returns a boolean if a field has been set.

### SetFulfilledDateNil

`func (o *DeliveryDateUpdate) SetFulfilledDateNil(b bool)`

 SetFulfilledDateNil sets the value for FulfilledDate to be an explicit nil

### UnsetFulfilledDate
`func (o *DeliveryDateUpdate) UnsetFulfilledDate()`

UnsetFulfilledDate ensures that no value is present for FulfilledDate, not even an explicit nil
### GetNote

`func (o *DeliveryDateUpdate) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *DeliveryDateUpdate) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *DeliveryDateUpdate) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *DeliveryDateUpdate) HasNote() bool`

HasNote returns a boolean if a field has been set.

### SetNoteNil

`func (o *DeliveryDateUpdate) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *DeliveryDateUpdate) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetOrderNumber

`func (o *DeliveryDateUpdate) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *DeliveryDateUpdate) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *DeliveryDateUpdate) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *DeliveryDateUpdate) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### SetOrderNumberNil

`func (o *DeliveryDateUpdate) SetOrderNumberNil(b bool)`

 SetOrderNumberNil sets the value for OrderNumber to be an explicit nil

### UnsetOrderNumber
`func (o *DeliveryDateUpdate) UnsetOrderNumber()`

UnsetOrderNumber ensures that no value is present for OrderNumber, not even an explicit nil
### GetOriginalDate

`func (o *DeliveryDateUpdate) GetOriginalDate() string`

GetOriginalDate returns the OriginalDate field if non-nil, zero value otherwise.

### GetOriginalDateOk

`func (o *DeliveryDateUpdate) GetOriginalDateOk() (*string, bool)`

GetOriginalDateOk returns a tuple with the OriginalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalDate

`func (o *DeliveryDateUpdate) SetOriginalDate(v string)`

SetOriginalDate sets OriginalDate field to given value.

### HasOriginalDate

`func (o *DeliveryDateUpdate) HasOriginalDate() bool`

HasOriginalDate returns a boolean if a field has been set.

### SetOriginalDateNil

`func (o *DeliveryDateUpdate) SetOriginalDateNil(b bool)`

 SetOriginalDateNil sets the value for OriginalDate to be an explicit nil

### UnsetOriginalDate
`func (o *DeliveryDateUpdate) UnsetOriginalDate()`

UnsetOriginalDate ensures that no value is present for OriginalDate, not even an explicit nil
### GetProductId

`func (o *DeliveryDateUpdate) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *DeliveryDateUpdate) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *DeliveryDateUpdate) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *DeliveryDateUpdate) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *DeliveryDateUpdate) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *DeliveryDateUpdate) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetPromisedDate

`func (o *DeliveryDateUpdate) GetPromisedDate() string`

GetPromisedDate returns the PromisedDate field if non-nil, zero value otherwise.

### GetPromisedDateOk

`func (o *DeliveryDateUpdate) GetPromisedDateOk() (*string, bool)`

GetPromisedDateOk returns a tuple with the PromisedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromisedDate

`func (o *DeliveryDateUpdate) SetPromisedDate(v string)`

SetPromisedDate sets PromisedDate field to given value.

### HasPromisedDate

`func (o *DeliveryDateUpdate) HasPromisedDate() bool`

HasPromisedDate returns a boolean if a field has been set.

### SetPromisedDateNil

`func (o *DeliveryDateUpdate) SetPromisedDateNil(b bool)`

 SetPromisedDateNil sets the value for PromisedDate to be an explicit nil

### UnsetPromisedDate
`func (o *DeliveryDateUpdate) UnsetPromisedDate()`

UnsetPromisedDate ensures that no value is present for PromisedDate, not even an explicit nil
### GetStatus

`func (o *DeliveryDateUpdate) GetStatus() DeliveryDateStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DeliveryDateUpdate) GetStatusOk() (*DeliveryDateStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DeliveryDateUpdate) SetStatus(v DeliveryDateStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DeliveryDateUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *DeliveryDateUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *DeliveryDateUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


