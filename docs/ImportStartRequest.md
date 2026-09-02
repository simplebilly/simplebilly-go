# ImportStartRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiKey** | **string** |  | 
**Provider** | **string** |  | 
**Years** | **[]int32** |  | 

## Methods

### NewImportStartRequest

`func NewImportStartRequest(apiKey string, provider string, years []int32, ) *ImportStartRequest`

NewImportStartRequest instantiates a new ImportStartRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImportStartRequestWithDefaults

`func NewImportStartRequestWithDefaults() *ImportStartRequest`

NewImportStartRequestWithDefaults instantiates a new ImportStartRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiKey

`func (o *ImportStartRequest) GetApiKey() string`

GetApiKey returns the ApiKey field if non-nil, zero value otherwise.

### GetApiKeyOk

`func (o *ImportStartRequest) GetApiKeyOk() (*string, bool)`

GetApiKeyOk returns a tuple with the ApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKey

`func (o *ImportStartRequest) SetApiKey(v string)`

SetApiKey sets ApiKey field to given value.


### GetProvider

`func (o *ImportStartRequest) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ImportStartRequest) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ImportStartRequest) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetYears

`func (o *ImportStartRequest) GetYears() []int32`

GetYears returns the Years field if non-nil, zero value otherwise.

### GetYearsOk

`func (o *ImportStartRequest) GetYearsOk() (*[]int32, bool)`

GetYearsOk returns a tuple with the Years field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYears

`func (o *ImportStartRequest) SetYears(v []int32)`

SetYears sets Years field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


