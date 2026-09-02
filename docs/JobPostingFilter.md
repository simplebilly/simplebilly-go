# JobPostingFilter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Page** | Pointer to **NullableInt32** |  | [optional] 
**PageSize** | Pointer to **NullableInt32** |  | [optional] 
**Status** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewJobPostingFilter

`func NewJobPostingFilter() *JobPostingFilter`

NewJobPostingFilter instantiates a new JobPostingFilter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobPostingFilterWithDefaults

`func NewJobPostingFilterWithDefaults() *JobPostingFilter`

NewJobPostingFilterWithDefaults instantiates a new JobPostingFilter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPage

`func (o *JobPostingFilter) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *JobPostingFilter) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *JobPostingFilter) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *JobPostingFilter) HasPage() bool`

HasPage returns a boolean if a field has been set.

### SetPageNil

`func (o *JobPostingFilter) SetPageNil(b bool)`

 SetPageNil sets the value for Page to be an explicit nil

### UnsetPage
`func (o *JobPostingFilter) UnsetPage()`

UnsetPage ensures that no value is present for Page, not even an explicit nil
### GetPageSize

`func (o *JobPostingFilter) GetPageSize() int32`

GetPageSize returns the PageSize field if non-nil, zero value otherwise.

### GetPageSizeOk

`func (o *JobPostingFilter) GetPageSizeOk() (*int32, bool)`

GetPageSizeOk returns a tuple with the PageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageSize

`func (o *JobPostingFilter) SetPageSize(v int32)`

SetPageSize sets PageSize field to given value.

### HasPageSize

`func (o *JobPostingFilter) HasPageSize() bool`

HasPageSize returns a boolean if a field has been set.

### SetPageSizeNil

`func (o *JobPostingFilter) SetPageSizeNil(b bool)`

 SetPageSizeNil sets the value for PageSize to be an explicit nil

### UnsetPageSize
`func (o *JobPostingFilter) UnsetPageSize()`

UnsetPageSize ensures that no value is present for PageSize, not even an explicit nil
### GetStatus

`func (o *JobPostingFilter) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *JobPostingFilter) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *JobPostingFilter) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *JobPostingFilter) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *JobPostingFilter) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *JobPostingFilter) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


