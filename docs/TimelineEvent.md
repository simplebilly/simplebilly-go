# TimelineEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** | RFC3339 UTC timestamp for sorting. | 
**Detail** | Pointer to **NullableString** |  | [optional] 
**Id** | **string** | Source record id (stringified). | 
**Status** | Pointer to **NullableString** |  | [optional] 
**Title** | **string** |  | 
**Type** | **string** | Source module: communication | quotation | order | invoice | attachment. | 

## Methods

### NewTimelineEvent

`func NewTimelineEvent(date string, id string, title string, type_ string, ) *TimelineEvent`

NewTimelineEvent instantiates a new TimelineEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimelineEventWithDefaults

`func NewTimelineEventWithDefaults() *TimelineEvent`

NewTimelineEventWithDefaults instantiates a new TimelineEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *TimelineEvent) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *TimelineEvent) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *TimelineEvent) SetDate(v string)`

SetDate sets Date field to given value.


### GetDetail

`func (o *TimelineEvent) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *TimelineEvent) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *TimelineEvent) SetDetail(v string)`

SetDetail sets Detail field to given value.

### HasDetail

`func (o *TimelineEvent) HasDetail() bool`

HasDetail returns a boolean if a field has been set.

### SetDetailNil

`func (o *TimelineEvent) SetDetailNil(b bool)`

 SetDetailNil sets the value for Detail to be an explicit nil

### UnsetDetail
`func (o *TimelineEvent) UnsetDetail()`

UnsetDetail ensures that no value is present for Detail, not even an explicit nil
### GetId

`func (o *TimelineEvent) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TimelineEvent) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TimelineEvent) SetId(v string)`

SetId sets Id field to given value.


### GetStatus

`func (o *TimelineEvent) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TimelineEvent) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TimelineEvent) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TimelineEvent) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *TimelineEvent) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *TimelineEvent) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetTitle

`func (o *TimelineEvent) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *TimelineEvent) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *TimelineEvent) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetType

`func (o *TimelineEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TimelineEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TimelineEvent) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


