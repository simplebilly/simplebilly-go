# GdprUsageEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** |  | 
**EventType** | **string** |  | 
**Id** | **string** |  | 
**Quantity** | **int32** |  | 
**TenantId** | **string** |  | 

## Methods

### NewGdprUsageEvent

`func NewGdprUsageEvent(createdAt time.Time, eventType string, id string, quantity int32, tenantId string, ) *GdprUsageEvent`

NewGdprUsageEvent instantiates a new GdprUsageEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGdprUsageEventWithDefaults

`func NewGdprUsageEventWithDefaults() *GdprUsageEvent`

NewGdprUsageEventWithDefaults instantiates a new GdprUsageEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *GdprUsageEvent) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GdprUsageEvent) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GdprUsageEvent) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetEventType

`func (o *GdprUsageEvent) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *GdprUsageEvent) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *GdprUsageEvent) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetId

`func (o *GdprUsageEvent) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GdprUsageEvent) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GdprUsageEvent) SetId(v string)`

SetId sets Id field to given value.


### GetQuantity

`func (o *GdprUsageEvent) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *GdprUsageEvent) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *GdprUsageEvent) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.


### GetTenantId

`func (o *GdprUsageEvent) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *GdprUsageEvent) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *GdprUsageEvent) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


