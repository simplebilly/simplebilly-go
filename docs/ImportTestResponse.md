# ImportTestResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to **NullableString** |  | [optional] 
**Ok** | **bool** |  | 

## Methods

### NewImportTestResponse

`func NewImportTestResponse(ok bool, ) *ImportTestResponse`

NewImportTestResponse instantiates a new ImportTestResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImportTestResponseWithDefaults

`func NewImportTestResponseWithDefaults() *ImportTestResponse`

NewImportTestResponseWithDefaults instantiates a new ImportTestResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ImportTestResponse) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ImportTestResponse) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ImportTestResponse) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ImportTestResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ImportTestResponse) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ImportTestResponse) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetOk

`func (o *ImportTestResponse) GetOk() bool`

GetOk returns the Ok field if non-nil, zero value otherwise.

### GetOkOk

`func (o *ImportTestResponse) GetOkOk() (*bool, bool)`

GetOkOk returns a tuple with the Ok field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOk

`func (o *ImportTestResponse) SetOk(v bool)`

SetOk sets Ok field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


